# Structural Changes in Crash Severity Risk After COVID-19  
Evidence from 20 Years of Pennsylvania Crash Data

This repository contains the code and analysis pipeline used in the research study titled:

**"Structural Changes in Crash Severity Risk After COVID-19: Evidence from 20 Years of Pennsylvania Crash Data."**

The project applies machine learning and explainable AI techniques to investigate whether the determinants of severe traffic crashes have structurally changed following the COVID-19 pandemic.

The analysis compares crash severity risk factors across two periods:

- **Pre-COVID period:** 2005–2019  
- **Post-COVID period:** 2022–2024  

Machine learning models and SHAP explainability methods are used to identify changes in the relative importance of crash risk factors.

---

# Data Source

The primary data source for this project is the **Pennsylvania Department of Transportation (PennDOT) Statewide Crash Database**, an administrative safety dataset containing **police-reported traffic crashes across the Commonwealth of Pennsylvania**.

The dataset includes crash records from **2005 through 2024**, covering more than **3.6 million crashes**. The database contains detailed information on:

- crash severity
- driver characteristics
- roadway conditions
- crash types
- environmental factors
- temporal variables such as time of day and day of week
- roadway departure and collision attributes

Due to licensing and data-use restrictions, the full PennDOT crash dataset **cannot be redistributed in this repository**.

Researchers who wish to reproduce the analysis should obtain the dataset directly from the Pennsylvania Department of Transportation.

Pennsylvania Department of Transportation (PennDOT)  
https://www.penndot.pa.gov

---

# Analysis Notebook

The repository includes a **Jupyter Notebook (`.ipynb`)** that contains the full analysis workflow.

The notebook performs the following steps:

- data preprocessing and cleaning
- feature engineering
- model training using Random Forest and XGBoost
- model evaluation
- SHAP feature importance analysis
- visualization of changes in crash severity determinants before and after COVID-19

Users can reproduce the analysis by executing the notebook sequentially after configuring the dataset path.

---

# How to Run the Analysis

To reproduce the analysis:

1. Obtain the Pennsylvania crash dataset from PennDOT.

2. Download or clone this repository.

3. Store the raw dataset on your local machine.

4. Open the provided **Jupyter Notebook (`.ipynb`)**.

5. Update the file path in the notebook so that it points to the location of the crash dataset on your local computer.

Example:

```python
data_path = "path_to_your_local_dataset/pa_crash_data.csv"
df = pd.read_csv(data_path)
