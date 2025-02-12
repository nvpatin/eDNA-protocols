# About Project
This table was extracted from a PDF of a monograph published in *Zootaxa* titled  *"Checklist of marine and estuarine fishes from the Alaska–Yukon Border, Beaufort Sea, to Cabo San Lucas, Mexico"* by Milton S. Love and others (https://doi.org/10.11646/zootaxa.5053.1.1) using the Claude API.

The data initially in PDF format has been processed and converted into a CSV table for future tasks. It includes fields for **species name, latitude, longitude, location description, and depth range**

<ins> It's important to note that the data from the monograph may not be comprehensive, but represents the best possible collection of available information. </ins> 

The Python code below was used to extract the data from the PDF. It uses claude-3-haiku-20240307 as the model and assumes an .env file with Claude API Key exists in the working directory. 

### Code
```python
import dotenv
dotenv.load_dotenv()
import anthropic
from PyPDF2 import PdfReader

def extract_text_from_pdf(pdf_path):
    """Extract text content from a PDF file."""
    reader = PdfReader(pdf_path)
    text = ""
    for page in reader.pages:
        text += page.extract_text()
    return text

def extract_species_locations(text, client):
    """
    Extract species information from text using Claude 3 Haiku.
    Returns data in CSV format containing species and location data.
    """
    # Prompt engineering to get structured data from Claude
    prompt = f"""Extract all species names and their associated latitude/longitude coordinates from the following text.
    Format your response as a CSV file where each line contains these fields:
    species_name,latitude,longitude,location_description,depth_range

    Important:
    - Keep all latitude and longitude values in their EXACT original format as they appear in the text
    - For location_description, include ALL relevant context about where the species was observed
    - Use NA if a field is not found

    Text to analyze: {text}"""

    message = client.messages.create(
        model="claude-3-haiku-20240307",
        max_tokens=4096,
        temperature=0,
        messages=[ 
            {"role": "user", "content": prompt}
        ]
    )

    response_text = message.content[0].text
    return response_text

def main():
    # Initialize Anthropic client
    client = anthropic.Client()

    # Process PDF
    pdf_path = "Love_et_al_2021_FishesoftheNEPacific.pdf"
    text = extract_text_from_pdf(pdf_path)

    # Extract species locations
    locations = extract_species_locations(text, client)
    print(locations)

if __name__ == "__main__":
    main()
```
### Example Output
```
Eptatretus deani,NA,NA,South-eastern Alaska to Islas San Benito, central Baja California,52-2743 m
...
Eptatretus stoutii,52°38'N, 26°37.2'N,130°00'W,Hecate Strait, British Columbia to southern Baja California,16-1247 m
