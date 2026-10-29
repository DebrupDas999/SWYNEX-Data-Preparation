# SWYNEX-Data-Preparation

## Overview
Completed Task 1: Data Preparation for the SWYNEX Data Science Internship. This project covers end-to-end data preprocessing, missing value handling, feature encoding, outlier capping, and standardization on the Titanic dataset.

## Pipeline Steps
1. **Loading & Inspection:** Loaded the public Titanic passenger dataset and inspected data types and missing values.
2. **Missing Value Imputation:** Dropped `Cabin` due to high missingness (>77%), imputed `Age` with the median, and `Embarked` with the mode.
3. **Encoding:** Converted categorical features (`Sex`, `Embarked`) into numerical formats using mapping and label encoding.
4. **Outlier Treatment:** Handled outliers in the `Fare` feature using the Interquartile Range (IQR) capping method.
5. **Feature Scaling:** Standardized `Age` and `Fare` using Scikit-Learn's `StandardScaler`.
6. **Export:** Saved the processed output as `cleaned_titanic_data.csv`.

## Files
* `data_preparation.py` (or your Jupyter Notebook file)
* `cleaned_titanic_data.csv`
