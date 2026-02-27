This repository contains R scripts for 
- processing dew data and Gross Primary Productivity (GPP) data obtained from NEON sites
- modeling the effects of dew duration and environmental variables on GPP across different ecosystems
- visualizing four figures in the main text
---

## Workflow Overview
1. Run scripts in `/Dew and GPP/` to:
   - Identify dew events
   - Estimate GPP
   - Generate processed datasets (`Processed_data.csv`)

2. Run scripts in `/BRT/` to:
   - Fit BRT models
   - Extract variable importance
   - Generate partial dependence plots

3. Scripts in `/Figure1–Figure4/` reproduce the manuscript figures.

## Data Sources
This project uses eddy covariance and meteorological data from the National Ecological Observatory Network (NEON). 
Data were accessed through the NEON data portal (https://data.neonscience.org) for the period 2015–2022.

Due to NEON data use policies, raw data are not redistributed in this repository. 
Users must download the required NEON data products following the product IDs listed in `NEON products.xlsx`.

## Project Structure
- `/Dew and GPP/` – Process dew and GPP data, identify dew events, and create analysis-ready datasets (Processed_data.csv)
- `/BRT/` - Run BRT models
-      `/jane_1390_sm_appendixs/` – Contains BRT helper functions (e.g., `brt.functions.R`)
- `/Figure1–Figure4/` – Scripts and intermediate outputs used to generate manuscript figures
- `/NEON products.xlsx` – Reference table for NEON data products and variables
- `/site_info.csv`– Reference table for NEON sites and infomation, also used when processing dew and GPP data
- `/README.md` – Project documentation file

## Software Environment
All analyses were conducted in R (version 4.3.2).
