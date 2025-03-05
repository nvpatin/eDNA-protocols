---
# MIOP terms
methodology_category: sample extraction and purification
project: CalCOFI 'Omics Lab Protocols
purpose: biodiversity assessment objective [OBI:0001969]
analyses: DNA extraction [OBI:0000257]
geographic_location: North East Pacific Ocean [GAZ:00013765]
broad_scale_environmental_context:oceanic epipelagic zone biome [ENVO:01000035], marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
environmental_medium: sea water [ENVO:00002149]
target: environmental DNA [NCIT:C169106]
creator: Nastassia Patin, Julie Dinasquet
materials_required: fume hood [CHMO:0010020], vortexer [OBI:0400118], centrifuge [OBI:0400106] 
time_required: 1440
personnel_required: 1
language: en
issued: March 2025
audience: scientists
publisher: California Cooperative Oceanic Fisheries Investigations
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_size: 2-60
samp_vol_we_dna_ext: 1-30
samp_vol_we_dna_ext_unit: L
nucl_acid_ext_lysis: chemical
nucl_acid_ext_sep: ethanol
nucl_acid_ext: https://www.protocols.io/view/phenol-chloroform-dna-isolation-for-environmental-4r3l26bxv1y9/v1
nucl_acid_ext_modify: Addition of Proteinase K during lysis incubation; overnight lysis incubation; use isopropanol + NaAcetate instead of ethanol + NaCl during preciptation; final incubation at 4°C
dna_cleanup_0_1: 0
concentration: not applicable
concentration_method: not applicable
ratioOfAbsorbance260_280: not applicable
pool_dna_num: not applicable
nucl_acid_ext_method_additional: not applicable
---

# CalCOFI Protocol for Extracting eDNA from Water Filters using Phenol:Chloroform

## Abstract
This protocol describes the extraction of DNA from 47 mm filters stored without buffer using phenol:chloroform and an isopropanol precipitation.

## Minimum Information about an Omics Protocol (MIOP)

See https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml for list and definitions.

## Authors

| **PREPARED BY**    | **AFFILIATION**             |   **ORCID**    |  **DATE**  |
|----------------------------------|--------------------------------------|---------|-----------|
| **Nastassia Patin** | Scripps Institution of Oceanography, UCSD | 0000-0001-8522-7682 | 09.27.2024 |
| **Julie Dinasquet**                      | Scripps Institution of Oceanography, UCSD  | 0000-0002-3401-764X | 09.27.2024

## PROTOCOL REVISION RECORD

Version numbers start at "1.0.0" when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0). Please store all versions in the gDrive folder designated to your institute.

| VERSION  | RELEASE DATE | DESCRIPTION OF REVISIONS | 
| ------------- | ------------- | ------------- |
| 1.0.0  | 2025-01-29  | Initial release  |
| 1.1.0	| 2025-03-06 | Added FAIRe terms and acronyms |

## ACRONYMS AND ABBREVIATIONS

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| NOAA | National Oceanic and Atmospheric Administration |
| eDNA | environmental DNA |
| PPE | Personal protective equipment |
| EtOH | Ethanol |
| SDS | Sodium dodecyl sulfate |
| TE | Tris-EDTA |


## GLOSSARY

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Extraction blank | A type of negative control to confirm there is no contamination during DNA extractions. Normally an empty filter extracted and PCR amplified alongside other samples. |

# Background
This document describes the required protocol to extract environmental DNA from flat 47 mm filters stored without buffer.

## Summary

This protocol was developed to process eDNA samples from marine environments. A typical filtration method entails filtering water onto 47 mm-diameter flat membranes enclosed in Swinnex housings. These filters are then stored in cryovials or tubes without storage buffer and frozen at -80° C. The use of phenol is considered a rigorous approach to DNA extraction with resulting DNA relatively free from impurities; therefore, this protocol is often used when experimental goals include detection of rare targets such as marine mammals.

## Method description and rationale
This protocol contains an overnight cell lysis stage using a commercially available buffer and proteinase K, a DNA extraction and purification stage using phenol:chloroform:isoamyl alcohol (25:24:1), and an isopropanol precipitation stage to maximize DNA yield. The filters are cut up to maximize the surface area exposed to the lysis buffer. Phenol extraction helps separate nucleic acids from other cellular components. After centrifugation, the DNA remains in the aqueous phase, allowing for further isolation and purification. An unused filter should be extracted alongside field samples for an extraction blank to identify any lab contamination.

## Personnel Required
One person with molecular biology experience.

## Safety
**Chloroform** is classified as toxic, a health hazard, and an irritant. Chloroform can be absorbed through the skin, and it can cause severe eye and skin irritation or be harmful if ingested. It is also classified as a possible human carcinogen.
**Phenol** is classified as toxic, corrosive, a health hazard, and environmentally damaging. Phenol can cause serious eye burns and skin damage, as well as pose a general risk to aquatic life and environments. It causes very painful burns that can bleach the skin and take a long time to heal. Phenol is a solid that readily deliquesces, which can lead those not familiar with the material to assume droplets are simply water, leading to accidental burns or improper clean up.
All steps involving phenol and chloroform should be performed in a fume hood. Users should wear appropriate PPE including nitrile gloves, a lab coat, closed toed shoes, and eye protection. Coat sleeves should extend to the gloves to ensure no skin is exposed. If exposure to the lab coat occurs with solutions containing phenol, remove the coat immediately. In case of skin contact with phenol, wash teh area with polyethylene glycol (PEG) or water. For chloroform exposure, rinse thoroughly with water.  Properly seal tubes and bottles before transport to minimize fume dispersal and splashing. Treat all used solutions as hazardous waste and dispose of them according to laboratory guidelines. 

## Training requirements

Molecular biology training (including, at a minimum, sterile technique, pipetting small volumes, and running a centrifuge) is required to conduct this protocol.

## Time needed to execute the procedure

This protocol requires approximately 6 hours of labor, including 1 hour and 45 minutes for DNA lysis and around 4 hours for extraction and purification. It also includes an overnight incubation step. Users should plan to complete the extraction in 18 hours over two days.

# EQUIPMENT


| **Description**              | **Product Name and Model**                  | **Manufacturer**    | **Quantity** | **Remark**                              |
|------------------------------|---------------------------------------------|---------------------|--------------|-----------------------------------------|
| **Durable Equipment**         |                                             |                     |              |                                         |
| BioSafety II cabinet	  | Biological safety cabinet (INT-1100A2) | Kewaunee | 1 | Positive pressure and UV lamp required for opening the Sterivex in a sterile environment
| Fume hood          |       |             | 1            | Required for handling phenol and chloroform. |
| Heatshaker                    | Fisherbrand incubating mini-shaker          | Fisher Scientific   | 1            | Needed for incubation during lysis or digestion steps. |
| Centrifuge                    | Eppendorf 5425 R                            | Fisher Scientific   | 1            | For separating phases and pelleting DNA; must fit 1.5 mL tubes. |
| Vortex                        | Analog vortex mixer                         | Fisher Scientific   | 1            | Required for mixing during extraction. |
| -80°C freezer                 | TSX high-performance -80°C freezer | Fisher Scientific | 1            | Required for sample and reagent storage. |
| Pipettor: 20 - 200 uL         | Pipetman P200L                              | Gilson              | 1            | For accurate pipetting of smaller volumes. |
| Pipettor: 100-1000 uL         | Pipetman P1000                              | Gilson              | 1            | For accurate pipetting of larger volumes. |
| Microtube racks               | 96-Well flipper microtube racks             | Fisher Scientific   | 2            | Organizing tubes for extraction process. |
| 50 mL tube racks              | SPL snap 50 mL tube rack (25 place)         | SPL Life Sciences   | 2            | To hold 50 mL tubes for Sterivex processing. |
| **Consumable Equipment**      |                                             |                     |              |                                         |
| 200 μL pipette tips           | TipOne RPT filter tips 200 μL graduated     | USA Scientific      | 96           | Must be sterile and filtered. |
| 1000 μL pipette tips          | TipOne RPT filter tips 1000 μL              | USA Scientific      | 220          | Must be sterile and filtered. |
| 1.5 mL tubes                  | Snap cap DNA LoBind 1.5 mL tubes, PCR-clean | Eppendorf           | 24           | Used for DNA extraction and storage; must be sterile. |
| Kimwipes                      | Delicate task wipes                         | Kimtech             | 5            | Must be lint-free for cleaning and wiping surfaces. |
| Nitrile gloves                | Powder free nitrile gloves                  | Fisher Scientific   | 8            | Must be sterilized before use (10% bleach followed by 70% EtOH). |
| Trash bags for BSC            | Teivio 1.2 Gallon 360 Counts Strong Trash Bags | Teivio           | 3            | For biohazard waste disposal. |
| **Chemicals**                        |                                          |                      |              |                             |
| DNAZap	|	DNAZap™ Solutions | 	Thermo Fisher	| 1 bottle | Degrades nucleic acids and decontaminates surfaces and labware. Can be substituted with DNA AWAY or 10% bleach solution. |
| Ethanol (70%) |	Molecular biology grade ethanol dilution |	Fisher Scientific	| 1 bottle |  Kills bacteria to decontaminate surfaces. |
| ATL buffer                           | ATL buffer (for DNA extraction)          | QIAGEN               | 20 mL        | Standard DNA extraction buffer.         |
| 1X TE buffer                         | Tris-EDTA buffer                         | Fisher Scientific    | 10 mL        | Can be substituted with generic.        |
| Proteinase K (20 mg mL⁻¹)            | Qiagen Proteinase K                      | Qiagen               | 1.92 mL      | Molecular biology grade.                |
| 10% SDS                              | Sodium dodecyl sulfate solution          | Sigma-Aldrich        | 10 mL        | Must be prepared fresh.                 |
| Sodium acetate (3.0 M, pH 5.2)           | Sodium acetate solution                  | Sigma-Aldrich        | 5 mL         | Molecular biology grade.                |
| Ice-cold isopropanol                 | Molecular biology grade isopropanol      | Fisher Scientific    | 30 mL        | Must be ice-cold for use.               |
| Ice-cold ethanol (70%)               | Molecular biology grade ethanol (70%)    | Fisher Scientific    | 20 mL        | Must be ice-cold for use.               |
| Ethanol (100%)                       | Molecular biology grade ethanol (100%)   | Fisher Scientific    | 30 mL        | Can be substituted with generic, 200 proof. |
| Phenol:Chloroform:Isoamyl alcohol (25:24:1) | Molecular biology grade P:C:I solution  | Fisher Scientific    | 10 mL        | Handle with caution in fume hood.       |
| Chloroform:Isoamyl alcohol (24:1)    | Molecular biology grade solution         | Fisher Scientific    | 10 mL        | Handle with caution.                    |


# STANDARD OPERATING PROCEDURE

## Day 1: DNA Lysis (1h45 for 12 samples)

1. **Set up the workspace**: 
   - Preheat the incubation oven to 56°C.
   - Disinfect the BioSafety cabinet with DNAzap and ethanol. Leave materials (pipettors, 1.5 mL tubes, tube racks, NOT filters) under UV for at least 15 minutes.
   
2. **Prepare the samples**: 
   - Label 1.5 mL tubes.
   - Remove samples from the -80°C freezer and keep them on ice.
   - Cut half of the filters into small pieces and place the remaining filter back in the -80°C freezer.

3. **Prepare the lysis mixture**: 
   - Add 525 µL of ATL buffer, 10 µL of proteinase K, and 60 µL of SDS to each sample.
   - Mix by pipetting and vortex briefly.

4. **Incubation**: 
   - Seal the tubes with parafilm and incubate them overnight at 56°C with gentle shaking.

## Day 2: DNA Extraction, Separation, and Purification (~4 hours)

1. **Prepare for extraction**:
   - Rinse filters with 500 µL of 1X TE buffer.
   - Vortex and divide the extracts equally between two 1.5 mL tubes (~500 µL per tube).

2. **Phenol:Chloroform Extraction**:
   - Under the fume hood, add equal volumes of phenol:chloroform:isoamyl alcohol (P:C:I) (~500 µL) to each tube.
   - Vortex the samples and centrifuge at maximum speed for 5 minutes at 20°C.

3. **Transfer the upper phase**: 
   - Carefully transfer the upper phase (~300 µL) to new tubes without disturbing the interface. This can be done manually or with a vacuum manifold.
   - Add equal volumes of chloroform:isoamyl alcohol (C:I) (~500 µL) to the upper phase.
   - Vortex, centrifuge for 5 minutes at maximum speed, and transfer the upper phase to new tubes.

4. **DNA Precipitation**:
   - Add 1/10 volume of sodium acetate and 0.6 volume of ice-cold isopropanol to precipitate the DNA.
   - Vortex and incubate at -20°C for at least 1 hour.

5. **Centrifugation and Washing**:
   - Centrifuge at 15,000 rpm for 20 minutes at 4°C. Carefully remove the supernatant (this can be done manually or with a vacuum manifold).
   - Wash the pellet with 0.5 mL of 70% ice-cold ethanol. Vortex and centrifuge for 20 minutes at 15,000 rpm and 4°C.
   - Remove the supernatant (manually or with a vacuum manifold) and air dry the pellet under the fume hood for 20 minutes.

6. **Dissolve the DNA**: 
   - Dissolve the dried DNA pellet in 40 µL of 1X TE buffer. Vortex gently.
   - Incubate at 4°C for 2 hours and store the samples at -20°C.

7. **DNA Quantification**:
   - Quantify the DNA using the Qubit Broad Range kit.

## Cleanup
1. Dispose of phenol/chloroform waste appropriately into a designated waste bottle.
2. Ensure that gloves and all disposable materials are placed in designated lab waste bins.

# Quality Control
- Verify the presence of DNA using PCR and gel electrophoresis.
- Ensure no contamination is present by running appropriate controls (negative controls without template DNA).

