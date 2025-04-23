# Dew Impact on GPP Using Boosted Regression Trees (BRT)

This repository contains R scripts for modeling and visualizing the effects of dew duration and environmental variables on Gross Primary Productivity (GPP) across different ecosystems using Boosted Regression Tree (BRT) models.

---

## Project Structure

/BRTcode ├── jane_1390_sm_appendixs/ # BRT helper functions (e.g., brt.functions.R) ├── mydt/ # Input CSVs with dew-related variables ├── result/ # Output folder for model results ├── plt/ # Output folder for plots ├── run_brt_models.R # Main R script └── README.md # This file


---

## Requirements

You need R and the following packages:

```r
install.packages(c("dplyr", "ggplot2", "cowplot", "tibble", "tidyr", "gbm"))
