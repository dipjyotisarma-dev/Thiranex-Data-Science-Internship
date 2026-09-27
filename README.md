# Thiranex Data Science Internship

Repository containing projects and tasks completed as part of the **Thiranex Data Science Internship**.

---

## Tasks Overview

| Task | Title | Description | Status | Link |
|:---:|:---|:---|:---:|:---|
| **Task 1** | **Data Cleaning & Visualization** | Preprocessing pipeline: missing values, duplicates, IQR outlier treatment, One-Hot encoding, and feature scaling. | **Completed** | [Task 1 Directory](Task-01-Data-Cleaning-and-Visualization/) |
| **Task 2** | **Predictive Modeling Using Machine Learning** | Supervised classification with Logistic Regression, Decision Tree, and Random Forest; evaluated via confusion matrices & ROC curves. | **Completed** | [Task 2 Directory](Task-02-Predictive-Modeling-Using-Machine-Learning/) |
| **Task 3** | **Exploratory Data Analysis (EDA) Project** | Exploratory analysis on retail sales: statistical summaries, category/regional breakdowns, correlation matrix, and profit driver analysis. | **Completed** | [Task 3 Directory](Task-03-Exploratory-Data-Analysis/) |

---

## Repository Structure

```
.
├── .gitignore
├── README.md
├── requirements.txt                                # Unified dependencies for all tasks
├── Task-01-Data-Cleaning-and-Visualization/
│   ├── data/
│   │   ├── raw_ecommerce_data.csv                  # Original raw dataset
│   │   └── cleaned_ecommerce_data.csv              # Cleaned and preprocessed dataset
│   ├── task1_data_cleaning_and_visualization.ipynb # Preprocessing notebook with charts
│   └── README.md                                   # Task 1 documentation
├── Task-02-Predictive-Modeling-Using-Machine-Learning/
│   ├── data/
│   │   └── telco_customer_churn.csv                # Real-world Telco Churn dataset
│   ├── task2_predictive_modeling.ipynb             # ML modeling notebook with confusion matrices & ROC curves
│   └── README.md                                   # Task 2 documentation
└── Task-03-Exploratory-Data-Analysis/
    ├── data/
    │   └── sample_superstore.csv                   # Real-world Superstore sales dataset
    ├── task3_exploratory_data_analysis.ipynb       # EDA notebook with statistical summaries & charts
    └── README.md                                   # Task 3 documentation
```

---

## Getting Started

1. Clone the repository and install dependencies:
   ```bash
   git clone <repo-url>
   cd Thiranex-Data-Science-Internship
   pip install -r requirements.txt
   ```

2. Run any task notebook:
   ```bash
   # Task 1
   cd Task-01-Data-Cleaning-and-Visualization
   jupyter notebook task1_data_cleaning_and_visualization.ipynb

   # Task 2
   cd ../Task-02-Predictive-Modeling-Using-Machine-Learning
   jupyter notebook task2_predictive_modeling.ipynb

   # Task 3
   cd ../Task-03-Exploratory-Data-Analysis
   jupyter notebook task3_exploratory_data_analysis.ipynb
   ```
