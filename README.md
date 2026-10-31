# Primary MCL Violations and Service-Area Income in California Community Water Systems

Yasaman Ebrahimi  
Date of submission: October 30, 2026

## Project Overview

This project uses a baseline linear regression and an expanded multiple regression to examine whether service-area median household income (MHI) differs between California community water systems with and without a current primary maximum contaminant level (MCL) violation. The expanded model also considers system size, owner type, and regional board, with log-income and robust-error sensitivity checks.

Project repository: https://github.com/yasamanebrahimi-byte/Math261AProject1

## Repository Structure

- `README.md` — project description and reproducibility information
- `paper1draft2.qmd` — Quarto source file containing the analysis and report
- `paper1draft2.pdf` — rendered PDF report
- `references.bib` — BibTeX reference file

## Data

The data comes from the California State Water Resources Control Board's **Drinking Water - SAFER Dashboard Failing and At-Risk Drinking Water Systems** dataset on California Open Data. This project uses the September 22, 2026 SAFER data snapshot (`CREATED_DATE = 2026-09-22`), stored as `SAFER_RA.csv`.

Dataset page: https://lab.data.ca.gov/dataset/safer-failing-and-at-risk-drinking-water-systems

## Dataset License

The SAFER dataset is listed on the California Open Data page with the license **Other (Public Domain)**.

## Reproducing the Report

1. Open `paper1draft2.qmd` in RStudio or another Quarto-compatible R environment.
2. Use the September 22, 2026 snapshot (`CREATED_DATE = 2026-09-22`) in `SAFER_RA.csv` and place it in `data/` or the project folder.
3. Open `paper1draft2.qmd`.
4. Render the Quarto file to PDF.

The analysis uses R and the `tidyverse`, `ggpubr`, `gridExtra`, `sandwich`, `scales`, and `knitr` packages.

## External Resources

I used ChatGPT to help with making sure the citations were in the right format, and also used codex to install the dependencies for this project.
