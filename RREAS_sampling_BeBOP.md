---
# MIOP terms
methodology_category: sample collection
project: Rockfish Recruitment and Ecosystem Assessment Survey Opportunistic eDNA Collection
purpose: biodiversity assessment objective [OBI:0001969]
analyses: filtration [OBI:0302885], environmental material collection process [OBI:0600012]
geographic_location: North East Pacific Ocean [GAZ:00013765]
broad_scale_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
environmental_medium: sea water [ENVO:00002149]
target: environmental DNA [NCIT:C169106]
creator: Nastassia Patin, Kelly Goodwin
materials_required: filtration [OBI:0302885]
skills_required: sterile technique, pipetting skills, standard molecular technique, research vessel experience
time_required: 120
personnel_required: 1
language: en
issued: 2025-03-06
audience: scientists
publisher: California Cooperative Oceanic Fisheries Investigations
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_category: sample
env_broad_scale: marine biome [ENVO:00000447]
env_local_scale: marine photic zone [ENVO:00000209]
env_medium: sea water [ENVO:00002149]
habitat_natural_artificial_0_1: 0
samp_collect_method: CTD rosette
samp_collect_device: Niskin bottle
samp_size: 3000
samp_size_unit: mL
---

# RREAS Water eDNA Sampling Protocol

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Nastassia Patin | UC San Diego, CalCOFI | <https://orcid.org/0000-0001-8522-7682> | 2025-03-06 |

## RELATED PROTOCOLS

| PROTOCOL NAME | LINK  | VERSION | RELEASE DATE|
| ------------- | ------------- | ------------- | ------------- |
| CalCOFI Protocol for Extracting eDNA from Water Filters using Phenol:Chloroform | <https://github.com/nvpatin/eDNA-protocols/blob/main/Membrane_Protocol-v4.md> | 1.1.0 | 2025-03-06 |


### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-03-06 | Initial release |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| CalCOFI | California Cooperative Oceanic Fisheries Investigations |
| SIO | Scripps Institution of Oceanography |
| NOAA | National Oceanic and Atmospheric Administration |
| RREAS | Rockfish Recruitment and Ecosystem Assessment Survey |
| AOML | Atlantic Oceanograhpic and Meteorological Laboratory |
| eDNA | environmental DNA |
| PPE | Personal Protective Equipement |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Field negative control | Negative control created during sampling. Usually distilled (DI) water run through a filter in place of a seawater eDNA sample. This will act as a control for contamination during field sampling. |
| Niskin bottle | Plastic cylindrical bottle used for collecting water samples at different depths. Comes in a variety of volumes. |

## BACKGROUND

### Summary

This protocol describes collection and filtration of marine [environmental DNA](target) samples using 47 mm membrane filters and can be adapted to collect water samples from individual [Niskin bottle](samp_collect_device), [CTD rosette](samp_collect_method), or flow through systems. This protocol was used to opportunistically collect eDNA aboard the NOAA RREAS survey from 2021-2023.

### Method description and rationale

This protocol is used to pump [sea water](environmental_medium) samples collected via [Niskin bottle](samp_collect_device)  through a 0.22 uM 47 mm membrane filter using a peristaltic pump. Filters are placed dry in cryovials and immediately stored at -20°C to better preserve [environmental DNA](target). The recommended filtration volume ~3 liters, which takes ~1 hour. Precautions are taken to minimize contamination of samples by thoroughly sterilizing all equipment prior to use. 

### Spatial coverage and environment(s) of relevance

This protocol can be used across any marine environment to effectively collect water samples for biodviersity monitoring. This protocol can tolerate a wide range of depths for sampling - RREAS samples range from the surface up to 500m.

## PERSONNEL REQUIRED

One person with pipetting experience. Research vessel experience is recommended but not required.

### Safety

There are no major safety concerns with this protocol. Standard precuations should be taken such as wearing PPE at all times to avoid skin and eye exposure especially when working with bleach.

### Training requirements

Standard moleculary biology training including sterile technique and pipetting technique is required to properly conduct this protocol. Research vessel experience is recommended. Personnel should be trained in filtering protocol prior to conducting on ship.

### Time needed to execute the procedure

The process of setting up sampling equipment and filtering seawater will take ~2 hours ([120](time_required) minutes) depending on number of samples.

## EQUIPMENT

| DESCRIPTION | PRODUCT NAME AND MODEL | VENDOR | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** | 
| 20 L carboy | 20 L Nalgene carboy | Generic brand | 1 | |
| 8 L carboy | 8 L Nalgene carboy | Generic brand | 1 | Used to hold bleach solution |
| Peristaltic pump | Masterflex peristaltic pump | Cole Parmer | 1 | |
| Pump heads | Masterflex L/S Easy-Load II Pump Heads for Precision Tubing | Avantor | 3 | The greater the # of pump heads, the faster the sampling process |
| Pump tubing | Masterflex Precision Pump Tubing, Peroxide-Cured Silicone  (EW-96400-24) | Cole Parmer | 4-6' per simultaneously filtered sample | Depends on # of pump heads |
| Swinnex housing | Millipore Swinnex Filter Holder, 47 mm | Millipore Sigma | 3 | Quantity depends on number of samples being filtered simultaneously. Housings are re-used. |
| Barbed adapter | 1/4" FNPT x 1/4" Hose ID Polypropylene Female Adapter | United States Plastic Corp. | 3 | Quantity depends on number of samples being filtered simultaneously. Can be substituted with stainless steel barbed adapters (e.g. Beduan brand: https://www.amazon.com/dp/B09BKNLQ26?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1) |
| 2 L graduated cylinders | Graduated cylinder - 2 L | Generic brand | 3 | Depends on # of samples being pumped at once, can be substituted with carboys which tubing will be directly attached to (no serological pipets) using adapters |
| Forceps | Sterilizable forceps | Generic brand | 2 | |
| Cooler | Standard cooler | Generic brand| 1 | |
| -20 °C freezer | -20 °C commercial chest freezer | Generic brand | 1 | |
| **Consumable equipment** |
| 47 mm PVDF filters | MilliporeSigma™ Durapore™ Membrane Filters, 0.22 μm (GVWP04700) | Fisher Scientific | 1 per sample | If a large pore size is desired, can substitute with other 47 mm filters |
| Sterile collection bags, 3.7 L | Nasco Whirl-Pak® Write-On Bag, 3.7 L capacity (#WPB01446WA) | Millipore Sigma | 1 box | 1 bag per water sample |
| 50-mL tubes | Falcon 50 mL high clarity conical centrifuge tube | Corning Falcon | 4 | Can be substituted with generic. Must be sterile. |
| Serological pipette | Greiner Bio-One 10mL Sterile Serological Pipets | Fisher Scientific | 3 | Depends on # of pump tubes|
| Cryovials | Nalgene™ General Long-Term Storage Cryogenic Tubes, 2 mL | Thermo Fisher | 1 per sample | |
| Cryolabels | Cryo-Babies® Labels (Z366218) | Millipore Sigma | 1 roll | Can be substituted with generic but must be resistant to freezing. |
| Gloves | Powder-free nitrile gloves | Generic brand | 1 box | Can be any generic brand of gloves |
| Field notebook | Hard cover notebook | Generic brand | 1 | Encouraged to keep a digital sample log in addition to written notes |
| **Chemicals** |
| 5-9% Sodium hypochlorite | Household bleach | Generic brand | 1 | (bottle) Dilute 1:20 for lab use |
| DNAZap | DNAZap™ Solutions | Thermo Fisher | 1 bottle | Degrades nucleic acids and decontaminates surfaces and labware. |
| Ethanol (70%) |	Molecular biology grade ethanol dilution |	Fisher Scientific	| 1 bottle |  Kills bacteria to decontaminate surfaces. |
| Milli-Q water | Molecular grade water | Generic brand | 10-20 L | |

## STANDARD OPERATING PROCEDURE

#### Preparation

1. Prepare a 1:20 dilution bleach solution by mixing 1 part household bleach (5-9% sodium hypochlorite) with DI water and storing in an 8 L carboy.
2. Decontaminate work stations for a) filtration and b) filter transfer to cryovial by spraying with bleach solution, letting sit for 10-15 minutes, and wiping down. Follow up by spraying 70% ethanol and wiping down. 
3. Prepare filter transfer space with 4 50-mL conical tubes containing the following: DNAZap (1 tube), milliQ water (2 tubes), and 70% ethanol (1 tube). Sterilize two pairs forceps and place in front of tubes (they will be sterilized again before filter transfer).
4. Set out cryovials and prepare cryolabels to the extent possible. 
5. Fill a cooler with wet ice to keep sample bags cold.

#### Decontamination

1. Attach hose-barb adapter to one end of peristaltic pump tubing. Screw an empty Swinnex housing onto the adapter.
2. Fill one Whirl-Pak bag with 500 mLL bleach solution and one with 1L milliQ water.
3. Stick the tubing inflow directly into the baths. Use the peristaltic pump to first run the bleach solution, then the milliQ water through the tubing. Repeat this for each set of tubing if you plan to filter multiple samles simultaneously.  
4. Decontaminate forceps by dipping them in the four 50-mL tubes sequentially (DNAZap, water, water, ethanol). Shake off excess ethanol.

#### Assembling the filter and housing

1. Over a decontaminated surface, carefully unscrew the two parts of the Swinnex housing. Using decontaminated forceps (see above) carefully remove one 47 mm membrane filter from the pack and place it in the top part of the Swinnex housing (or bottom, as long as it is flat and stable). Filters are separated by blue paper; be sure to place the white filter, not the blue paper! 
2. Make sure the O-ring is correctly situated and there is no gap between the filter and O-ring where water can flow through before screwing the two parts back together. 
3. Screw the Swinnex onto the adapter attached to the tubing.

#### Field blank sample

1. Assemble a new filter following the protocol above and attach to the tubing adapter.
2. Run ~500 mL milliQ water through the filter.
3. Turn off the pump. Remove the Swinnex filter housing, carefully unscrew the housing parts, and place the filter in a new cryovial using forceps.
4. Label the cryovial and store at -20°C immediately.

#### Sampling

1. Prepare 1 Whirl Pak bag to collect rinse water, and 3 bags for each sample. For example, if you are collecting water from three CTD depths, you will need 3 x 3 + 1 or 10 total bags.
2. Wearing gloves, collect 3 L water from each desired depth. Collect equal volumes of water from replicate Niskin bottles. For example, if three bottles were tripped at each depth, sample 1 L from each of the three bottles for a 3 L total sample.
3. Store bags in the cooler with ice until you are ready to filter them.

#### Filtration

1. Set up the designated rinse water bag. There should NO filter on the outflow end of the tubing.
2. Place serological pipettes into rinse water bag.
3. Turn on the pump and run all 2 L seawater to rinse the tubing.
4. Turn off the pump and open pump head valves to release pressure. Attach assembled filters + housings to tubing adapter and place serological pipet in designated sample water bags.
5. Turn on the pump and run it pump at 100-150 rpm. Collect water in containers and measure the total volume filtered with the graduated cynlinder.
6. Filter 2 L or 1 hour, whichever comes first. When the filtration is finished, run some air through the tubing with the filter still attached to dry the filter. If there is any water left in the Whirl Pak, lift the pipet out so it pulls in air instead of water. Run 5-10 seconds of air before turning off the pump.

#### Sample preservation

1. Remove the Swinnex filter housing, carefully unscrew the housing parts. Remove the filter using decontaminated forceps. If possible, roll the filter into a little tube. Otherwise, fold it into quarters (use both sets of forceps). Place it in a new cryovial.
2. Label the cryovial and store at -20°C immediately.
3. On the sample sheet, record the date, time, latitute, longitude, volume filtered and any notes about the sample. This information should be entered into an Excel spreadsheet every few days to maintain a digital copy in addition to the paper copy.

### Quality control

Field blanks should be generated as described above once per sampling day.

Decontamination of tubing and Swinnex housings should be performed, at a minimum, before the sampling effort begins. If possible, it should be repeated throughout the sampling effort (ie once per sampling day); however, if milliQ and/or bleach is limited, thorough rinsing with sample water will suffice.

### Basic troubleshooting guide

Leaks
- If there is a leak present in the pump setup, you will notice trouble pulling water through the pump system. Check all seals and re-attach tubing.

Clogged Filter
- If a filter is clogged, turn valves and connections off and attempt to clear obstructions (i.e. large chunks of sediment or algae). Make note of any abnormal conditions and try to pump the full volume of seawater through the filter. 

## REFERENCES
Not applicable.

## APPENDIX A: DATASHEETS
Not applicable.

## APPENDIX B: VIDEO & IMAGE FILES

[Swinnex filter assembly with images](https://github.com/nvpatin/eDNA-protocols/blob/main/Images/SOP%20Swinnex%20assembly.docx)