# Task 2: Predictive Modeling Using Machine Learning

**Internship:** Thiranex Data Science Internship  
**Dataset:** Telco Customer Churn (IBM / Kaggle)

## Overview
This project implements supervised machine learning classification models to predict customer churn. It compares a linear model (Logistic Regression), a tree model (Decision Tree), and an ensemble model (Random Forest), evaluating their performance using confusion matrices and ROC curves.

## What Was Done
1. **Data Preparation:** Handled missing values in `TotalCharges`, dropped the non-predictive `customerID`, encoded the target, one-hot encoded categorical variables, and performed a stratified 80/20 train-test split.
2. **Model Training:** Trained three classifiers:
   - **Logistic Regression** (Linear baseline)
   - **Decision Tree Classifier** (Tree-based model)
   - **Random Forest Classifier** (Ensemble model)
3. **Model Evaluation:** Evaluated models using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
4. **Visualizations:**
   - **Confusion Matrices:** Plotted side-by-side heatmaps for all models.
   - **ROC Curves:** Plotted ROC curves with AUC comparisons on a single graph.
   - **Feature Importance:** Visualized the top 10 churn drivers identified by Random Forest.

## Performance Summary

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|:---|:---:|:---:|:---:|:---:|:---:|
| **Logistic Regression** | 80.70% | 65.84% | 56.68% | 0.6092 | 0.8416 |
| **Decision Tree** | 79.42% | 62.96% | 54.55% | 0.5845 | 0.8284 |
| **Random Forest** | 79.63% | 67.90% | 44.12% | 0.5348 | 0.8429 |

## Project Structure
- `data/`: Contains `telco_customer_churn.csv`.
- `task2_predictive_modeling.ipynb`: Executed Jupyter notebook with code, outputs, and performance charts.

## Usage
Ensure dependencies from root `requirements.txt` are installed:
```bash
jupyter notebook task2_predictive_modeling.ipynb
```
