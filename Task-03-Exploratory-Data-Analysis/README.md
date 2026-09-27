# Task 3: Exploratory Data Analysis (EDA) Project

**Internship:** Thiranex Data Science Internship  
**Dataset:** Sample Superstore Sales (Tableau / Kaggle)

## Overview
This project performs an Exploratory Data Analysis (EDA) on the Superstore retail dataset to uncover sales patterns, analyze category and regional trends, identify correlations, and isolate key drivers of profitability.

## What Was Done
1. **Statistical Overview:** Computed descriptive statistics (mean, median, standard deviation, percentiles) for numerical metrics and confirmed zero missing values.
2. **Distribution Analysis:** Visualized skewed distributions of `Sales` (log-scale) and `Profit` (clipped distribution).
3. **Categorical & Regional Breakdown:** Analyzed total sales and profit contributions across product categories (Technology, Furniture, Office Supplies) and geographic regions (West, East, Central, South).
4. **Correlation Analysis:** Generated a correlation heatmap to quantify relationships between Sales, Quantity, Discount, and Profit.
5. **Profitability Driver Analysis:** Evaluated sub-category profit performance and plotted average profit margin across increasing discount rates.

## Key Insights
- **Top Category:** Technology delivers the highest overall profit ($145.5K), led by Copiers ($55.6K) and Phones ($44.5K).
- **Loss-Making Sub-Categories:** Tables (-$17.7K) and Bookcases (-$3.5K) operate at significant losses due to heavy promotional discounting.
- **Discount Threshold:** Discount has a negative correlation with profit (-0.22). Discounts exceeding **20%** consistently push average transaction margins into negative territory.
- **Regional Difference:** The West region generates the highest profit ($108.4K), while Central generates the lowest ($39.7K).

## Project Structure
- `data/`: Contains `sample_superstore.csv`.
- `task3_exploratory_data_analysis.ipynb`: Executed Jupyter notebook with code, outputs, and visualizations.

## Usage
Ensure dependencies from root `requirements.txt` are installed:
```bash
jupyter notebook task3_exploratory_data_analysis.ipynb
```
