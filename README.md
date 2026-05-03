# IS 547 Course Project – Harmonizing Instrumental Climate Observations and Reported Severe Weather Events in Illinois (2010–2025)

**Student:** Jasmitha Duvvuru (jd56)  
**Semester:** Spring 2026

## Project Goal
This project harmonizes daily instrumental weather measurements from the NOAA Global Historical Climatology Network – Daily (GHCN-Daily) with county-level severe weather event records from the NOAA Storm Events Database for Illinois (2010–2025). The focus is on spatial and temporal harmonization between the two systems.

## Repository Structure

```
IS547_Course_Project/
├── Raw Data/
│   ├── Climate Dataset1.csv
│   └── StormEvents_details/
│       ├── StormEvents_2010.csv
│       ├── StormEvents_2011.csv
│       ├── StormEvents_2012.csv
│       ├── StormEvents_2013.csv
│       ├── StormEvents_2014.csv
│       ├── StormEvents_2015.csv
│       ├── StormEvents_2016.csv
│       ├── StormEvents_2017.csv
│       ├── StormEvents_2018.csv
│       ├── StormEvents_2019.csv
│       ├── StormEvents_2020.csv
│       ├── StormEvents_2021.csv
│       ├── StormEvents_2022.csv
│       ├── StormEvents_2023.csv
│       ├── StormEvents_2024.csv
│       └── StormEvents_2025.csv
├── Processed Data/                     ← Cleaned and final outputs folder
├── Statistics/                         ← Visualizations and summary
├── is547_course_project.ipynb          ← Main notebook (run this)
├── data_dictionary.md
├── README.md   
└── (other documentation files)
```

## How to Reproduce
1. Clone or download this GitHub repository.
2. Place the original raw files in the exact folder structure shown above (`Raw Data/` folder).
3. The Jupyter Notebook and Raw Data folder should be in the same directory.
3. Open `is547_course_project.ipynb` in Jupyter Notebook or JupyterLab.
4. Run all cells in order.

The notebook uses **only relative paths** and will automatically generate the final integrated dataset.

## Key Files
- `data_dictionary.md` – Full explanation of every column in the final dataset
- `final_integrated_illinois_climate_events.csv` – Main curated dataset
- `is547_course_project.ipynb` – Complete, reproducible curation pipeline

## Final Dataset
The curated dataset is also available on Zenodo Sandbox:  
**DOI:** 10.5072/zenodo.495348  
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)