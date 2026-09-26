# Thiranex Data Science Internship

Repository containing projects and tasks completed as part of the **Thiranex Data Science Internship**.

---

## Tasks Overview

| Task | Title | Description | Status | Link |
|:---:|:---|:---|:---:|:---|
| **Task 1** | **Data Cleaning & Visualization** | Preprocessing pipeline: missing values, duplicates, IQR outlier treatment, One-Hot encoding, and feature scaling. | **Completed** | [Task 1 Directory](Task-01-Data-Cleaning-and-Visualization/) |
| **Task 2** | **Predictive Modeling Using Machine Learning** | Supervised classification with Logistic Regression, Decision Tree, and Random Forest; evaluated via confusion matrices & ROC curves. | **Completed** | [Task 2 Directory](Task-02-Predictive-Modeling-Using-Machine-Learning/) |
| **Task 3** | Upcoming Task | Scheduled next milestone | Planned | - |

---

## Repository Structure

```
.
├── README.md
├── Task-01-Data-Cleaning-and-Visualization/
│   ├── data/
│   │   ├── raw_ecommerce_data.csv                  # Original raw dataset
│   │   └── cleaned_ecommerce_data.csv              # Cleaned and preprocessed dataset
│   ├── task1_data_cleaning_and_visualization.ipynb # Preprocessing notebook with charts
│   ├── requirements.txt                            # Dependencies
│   └── README.md                                   # Task 1 documentation
└── Task-02-Predictive-Modeling-Using-Machine-Learning/
    ├── data/
    │   └── telco_customer_churn.csv                # Real-world Telco Churn dataset
    ├── task2_predictive_modeling.ipynb             # ML modeling notebook with confusion matrices & ROC curves
    ├── requirements.txt                            # Dependencies
    └── README.md                                   # Task 2 documentation
```

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd Thiranex-Data-Science-Internship
   ```

2. Run Task 1:
   ```bash
   cd Task-01-Data-Cleaning-and-Visualization
   pip install -r requirements.txt
   jupyter notebook task1_data_cleaning_and_visualization.ipynb
   ```

3. Run Task 2:
   ```bash
   cd ../Task-02-Predictive-Modeling-Using-Machine-Learning
   pip install -r requirements.txt
   jupyter notebook task2_predictive_modeling.ipynb
   ```
