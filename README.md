# Dew Impact on GPP

This repository contains R scripts for 
- processing dew data and Gross Primary Productivity (GPP) data obtained from NEON sites
- modeling and visualizing the effects of dew duration and environmental variables on GPP across different ecosystems.
---

## Project Structure

- `/jane_1390_sm_appendixs/` – Contains BRT helper functions (e.g., `brt.functions.R`)
- `/mydt/` – Input folder for CSV files with dew-related variables
- `/result/` – Stores model output files such as contribution tables
- `/plt/` – Stores generated plots like violin plots and PDPs
- `/CodeforBRT.R` – Main R script to run BRT models and generate plots
- `/README.md` – Project documentation file (this file)


---

## Requirements

You need R and the following packages:
"dplyr", "ggplot2", "cowplot", "tibble", "tidyr", "gbm"
