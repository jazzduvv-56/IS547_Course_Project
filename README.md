# IS 547 Course Project – Illinois Climate & Severe Weather Integration

**Student:** Jasmitha Duvvuru (jd56) 
**Semester:** Spring 2026  

## Project Goal
Harmonize daily instrumental weather measurements (GHCN-Daily) with officially reported severe weather events (Storm Events Database) for Illinois 2010–2025. The focus is on spatial and temporal mismatches between the two systems.

## Datasets
- **GHCN-Daily** – 10 selected Illinois stations  
- **Storm Events** – Illinois records only, filtered to Winter Storm, Blizzard, Flood, Excessive Heat

## Repository Contents
- `ghcn_illinois_clean_with_county.csv` – cleaned GHCN data with county and season  
- `storm_events_illinois_clean.csv` – cleaned and daily-expanded Storm Events  
- `final_integrated_illinois_climate_events.csv` – final merged dataset (main deliverable)  
- `is547_course_project.py` – complete curation pipeline (GHCN + Storm Events + merge)  
- `Progress_Report_jd56.pdf` – this report  

## How to Reproduce
1. Place all raw `StormEvents_20XX.csv` files in a folder  
2. Run `is547_course_project.py`  
3. The final integrated file will be generated automatically  

All code includes detailed comments explaining every curation decision.

## Next Steps (April)
- Full data dictionary and comprehensive README  
- Mismatch analysis and visualization  
- Final report submission