# Crop Yield, Pest Risk and Drone Operations Analytics

End-to-end data mining and predictive modeling project using Python.  
The project covers data cleaning, regression models, time series forecasting, PCA and clustering applied to agricultural and drone operation datasets.

## Project overview

This repository contains a complete data science workflow focused on three analytical problems:

1. Predicting crop yield from agricultural and environmental variables.
2. Modeling the probability of severe pest outbreaks.
3. Segmenting drone operations using dimensionality reduction and clustering.

The project also includes a time series forecasting section using the Spanish Industrial Production Index (IPI).

## Techniques used

- Exploratory Data Analysis
- Data validation and cleaning
- Missing value imputation
- Outlier treatment
- Linear regression
- Lasso variable selection
- Logistic regression
- Cross-validation
- Holt-Winters exponential smoothing
- SARIMAX forecasting
- PCA
- K-Means clustering

## Repository structure

```text
.
├── data/
│   └── raw/              # Original datasets
├── notebooks/
│   └── crop-yield-pest-risk-analytics.ipynb
├── src/
│   └── utils.py          # Reusable custom functions
├── outputs/
│   ├── figures/
│   └── models/
├── requirements.txt
├── .gitignore
└── README.md
