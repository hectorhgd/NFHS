# NFHS-4 & NFHS-5 Statistical Analysis Repository
This repository contains the R Markdown files used for the statistical analyses presented in the scientific article titled "Patterns of antibiotic use for acute respiratory infections in under-three-years-old children in India: a cross-sectional study".

## Overview

We organized the code into distinct R Markdown scripts to facilitate the understanding and reproducibility of the analyses. Each script corresponds to a specific stage of the project, and a brief description of the objectives for each script is provided at the beginning.

### 1. Data Cleaning

In this phase, we performed input of the original .DTA file and reduced observations. The following scripts were developed:

- `NFHS4_clean.Rmd`
- `NFHS4_HH_cleaning.Rmd`
- `NFHS5_clean.Rmd`
- `NFHS5_HH_cleaning.Rmd`

### 2. Recoding of the Data

To enhance clarity and categorization, we recoded variables of interest in this stage. The relevant scripts include:

- `NFHS4_recoding.Rmd`
- `NFHS5_recoding.Rmd`

### 3. Analysis of the Data

The core analysis is divided into multiple scripts to cover different aspects:

- `nfhs_ari_unweighted_table1.Rmd`
- `nfhs_ari_weighted_table1.Rmd`
- `nfhs_ari_weighted_table2.Rmd`
- `nfhs_ari_regional_analysis.Rmd`
- `nfhs_ari_regression.Rmd`

## Data Sources

The NFHS-4 and NFHS-5 datasets (.DTA files) used in this analysis are publicly available and can be downloaded from the Demographic and Health Survey (DHS) program at [https://dhsprogram.com/data/available-datasets.cfm](https://dhsprogram.com/data/available-datasets.cfm).

## Contributors

This codebase was developed by Hector Gonzalez Dorta under the supervision of Dr. Arijit Nandi at McGill University.

Feel free to explore, contribute, or use this repository as a reference for similar analyses. If you have any questions or suggestions, please don't hesitate to reach out.
