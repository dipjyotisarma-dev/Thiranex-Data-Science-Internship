# Task 4: Real-World Data Project (Finance: Credit Risk Classification)

**Internship:** Thiranex Data Science Internship  
**Domain:** Finance / Banking  
**Dataset:** Real-World Credit Scoring / Risk Dataset (4,446 records)

## Overview
This project implements an end-to-end classification pipeline for predicting credit default risk on retail loan applicants, following the workflow: **Data Cleaning -> Exploratory Data Analysis (EDA) -> Feature Engineering -> Prediction + Evaluation**.

## What Was Done
1. **Basic Data Cleaning:** Filtered primary financial/demographic attributes, mapped binary default risk (`bad` = 1, `good` = 0), and verified zero missing values.
2. **Exploratory Data Analysis (EDA):** Visualized target class distribution (28.1% default rate), analyzed delinquency record risk impact, and examined a numerical correlation heatmap.
3. **Feature Engineering:** Created financial domain metrics:
   - `Debt_to_Income`: Ratio of debt obligations to monthly income.
   - `Loan_to_Income`: Burden of requested credit relative to income.
   - `Net_Assets`: Total assets minus liabilities.
   - Applied One-Hot Encoding to categorical features (`Home`, `Marital`, `Records`, `Job`) and performed an 80/20 stratified split.
4. **Prediction & Evaluation:** Trained and evaluated **Logistic Regression** and **Random Forest Classifier**:
   - Visualized performance via side-by-side **Confusion Matrices**.
   - Plotted comparative **ROC Curves** with AUC scores.
   - Extracted **Top 10 Feature Importances** (delinquency records, seniority, and loan burden).

## Performance Summary

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|:---|:---:|:---:|:---:|:---:|:---:|
| **Logistic Regression** | 79.55% | 67.00% | **53.60%** | **0.5956** | 0.8278 |
| **Random Forest** | **81.46%** | **77.07%** | 48.40% | 0.5946 | **0.8362** |

## Project Structure
- `data/`: Contains `credit_scoring.csv`.
- `task4_real_world_data_project.ipynb`: Executed notebook with complete pipeline, outputs, and charts.

## Usage
Ensure dependencies from root `requirements.txt` are installed:
```bash
jupyter notebook task4_real_world_data_project.ipynb
```
