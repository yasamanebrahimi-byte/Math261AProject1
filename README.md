# Median Household Income and Primary Drinking Water Violations in California

Yasaman Ebrahimi  

## Project Overview

This project uses simple linear regression to examine whether service-area median household income (MHI) differs between California community water systems with and without a current primary maximum contaminant level (MCL) violation.

## Repository Structure

- `README.md` — project description and reproducibility information
- `paper1draft1.qmd` — Quarto source file containing the analysis and report
- `paper1draft1.pdf` — rendered PDF report
- `paper1.Rproj` — RStudio project file

## Data

The data comes from the California State Water Resources Control Board's **Drinking Water - SAFER Dashboard Failing and At-Risk Drinking Water Systems** dataset on California Open Data.

Dataset page: https://lab.data.ca.gov/dataset/safer-failing-and-at-risk-drinking-water-systems


## Reproducing the Report

1. Open the R project.
2. Download `SAFER_RA.csv` from the dataset page and place it in `data/` or the project folder.
3. Open `paper1draft1.qmd`.
4. Render the Quarto file to PDF.

The analysis uses R and the `tidyverse`, `ggpubr`, `gridExtra`, `scales`, and `knitr` packages.