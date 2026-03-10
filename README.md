# Structural Changes in Crash Severity Risk After COVID-19
Evidence from 20 Years of Pennsylvania Crash Data

This repository contains the code and analysis pipeline used in the manuscript:

**"Structural Changes in Crash Severity Risk After COVID-19: Evidence from 20 Years of Pennsylvania Crash Data."**

The repository provides the full workflow for data preprocessing, machine learning modeling, SHAP-based feature importance analysis, and visualization.

---

# Project Overview

This study investigates whether the determinants of severe traffic crashes changed following the COVID-19 pandemic. Using machine learning models and SHAP explainability methods, the analysis compares risk factor importance between pre-pandemic and post-pandemic crash environments.

Key components of the analysis include:

- Data preprocessing and feature engineering
- Random Forest and XGBoost modeling
- SHAP-based feature importance comparison
- Visualization of structural changes in crash severity determinants

---

# Data Source

The primary data source for this project is the **Pennsylvania Department of Transportation (PennDOT) Statewide Crash Database**, an administrative safety dataset containing **police-reported traffic crashes across the Commonwealth of Pennsylvania**.

The dataset covers crashes from **2005 through 2024** and includes information on:

- crash severity
- driver characteristics
- roadway conditions
- crash types
- environmental factors
- time and location attributes

Due to data use and licensing restrictions, the full PennDOT crash dataset **cannot be redistributed in this repository**.

Researchers wishing to replicate the analysis should obtain the dataset directly from:

**Pennsylvania Department of Transportation (PennDOT)**  
https://www.penndot.pa.gov

---

# Data Setup Instructions

After obtaining the crash dataset from PennDOT, follow these steps:

1. Download or clone this repository.

2. Create a local data folder:
