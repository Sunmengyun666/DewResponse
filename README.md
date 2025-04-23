# Dew Impact on GPP Using Boosted Regression Trees (BRT)

This repository contains R scripts for modeling and visualizing the effects of dew duration and environmental variables on Gross Primary Productivity (GPP) across different ecosystems using Boosted Regression Tree (BRT) models.

---

## Project Structure

/BRTcode
├── jane_1390_sm_appendixs/   # Contains BRT helper functions (e.g., brt.functions.R)
├── mydt/                     # Input folder for CSV files with dew-related variables
├── result/                   # Stores model output files such as contribution tables
├── plt/                      # Stores generated plots like violin plots and PDPs
├── run_brt_models.R          # Main R script to run BRT models and generate plots
└── README.md                 # Project documentation file (this file)

---

## Requirements

You need R and the following packages:

```r
install.packages(c("dplyr", "ggplot2", "cowplot", "tibble", "tidyr", "gbm"))
