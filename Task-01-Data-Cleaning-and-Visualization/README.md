# Task 1: Data Cleaning & Preprocessing

**Internship:** Thiranex Data Science Internship  
**Dataset:** Online Retail / E-Commerce Dataset (Kaggle)

## Overview
This project implements an end-to-end data preprocessing pipeline focusing on data hygiene, missing value imputation, duplicate removal, outlier handling, categorical encoding, and feature scaling.

## Preprocessing Steps
1. **Missing Value Handling:** Identified null values in `Description` and `CustomerID`, visualized missing data distributions, and performed appropriate imputation.
2. **Duplicate Removal:** Checked for and eliminated duplicate rows to ensure dataset consistency.
3. **Outlier Detection & Treatment:** Detected extreme values in numerical features (`Quantity`, `UnitPrice`) using the IQR method and applied percentile capping (visualized with before/after boxplots).
4. **Categorical Encoding:** Converted categorical variables into numeric format using One-Hot Encoding (`pd.get_dummies`).
5. **Feature Scaling:** Standardized numerical columns using `StandardScaler` to ensure zero mean and unit variance (visualized before/after distributions).
6. **Data Export:** Saved the final preprocessed dataset to `data/cleaned_ecommerce_data.csv`.

## Project Structure
- `data/`: Contains raw and preprocessed CSV datasets.
- `task1_data_cleaning_and_visualization.ipynb`: Jupyter notebook containing the preprocessing steps, code, and visualizations.
- `requirements.txt`: Python package dependencies.

## Usage
```bash
pip install -r requirements.txt
jupyter notebook task1_data_cleaning_and_visualization.ipynb
```
