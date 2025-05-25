# Data Science, Prediction and Forecasting
*Aarhus University, MSc Cognitive Science, spring 2025.*

This repository contains the code for the exam project **"Individual Determinants of Retirement Age: Insights from a Cross-National SHARE Sample"**.

This project, including both the report and the code, was completed in equal collaboration between the two authors.

The structure of the repository:

```
├── data/                        --- A placeholder for the data, acquired from SHARE.
├── output/                      --- Folder for the objects from the analysis.
│   ├── best_model.pkl           --- First model, not used in the analysis.
│   ├── best_model_2.pkl         --- Second mode, used in the analysis.
│   ├── shap_values.joblib       --- SHAP values, based on the model that is not used.
│   └── shap_values_2.joblib     --- SHAP values, based on the model used in the analysis.
├── plots/                       --- All plots, from both notebooks.
├── cleaning_data_all.ipynb      --- Notebook for cleaning the data.
├── data_analysis.ipynb          --- Notebook for data analysis.
└── retirement_data_all.csv.zip  --- Zipped data for data analysis.
```
