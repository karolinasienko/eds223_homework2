# EDS 223: Homework 2 - Exploring Patterns of Environmental Justice in Los Angeles County, CA

## Purpose of this Repository
This repository is for Homework 2 for EDS 223: Geospatial Analysis & Remote Sensing. It uses data from EJScreen, EPA's environmental justice screening and mapping tool, that uses Census block groups as the basic geographic unit. It contains data across the entire United States, but was filtered to specifically look at Los Angeles County, CA. Another dataset used was ...

The goal was to ...


## Package Dependencies
* `tidyverse`
* `sf`
* `here`
* `tmap`
* `spData`


## File Structure
```
.
├── data
│   ├── ejscreen
│   │   ├── EJSCREEN_2023_BG_Columns.xlsx
│   │   ├── EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb/
│   │   └── ejscreen-tech-doc-version-2-2.pdf
│   ├── mapping-inequality
│   │   ├── mapping-inequality-los-angeles.json
│   │   └── mapping-inequality-new-haven.json
│   └── SWITRS_LA
│       └── Crashes.csv
├── homework_2.pdf
├── homework_2.qmd
└── README.md
```

## Data Information & Access
This analysis uses data from the EPA's previous [EJScreen: Environmental Justice Screening and Mapping Tool](https://www.epa.gov/ejscreen), accessed on October 1, 2026. The tool, when it existed, used national data to highlight places that had higher environmental burdens and vulnerable populations. 

An unofficial version of the EJScreen tool can be found [here](https://pedp-ejscreen.azurewebsites.net/).

OTHER DATA ...


## Authors
Author: [Karolina Sienko](https://github.com/karolinasienko)


## Citations
United States Environmental Protection Agency (EPA), 2023. *EJScreen Technical Documentation*.

United States Environmental Protection Agency (EPA). 2023 version. *EJSCREEN*. Accessed October 1, 2026.
