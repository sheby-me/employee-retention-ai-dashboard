# Employee Retention AI Dashboard
**Predicting attrition with Machine Learning to drive better HR decisions.**

## Project Overview
This project addresses the business challenge of employee turnover. Using a **Random Forest Classifier**, the model analyzes historical data to predict the likelihood of an employee leaving and identifies the most significant factors behind those decisions.

## Key Features
* **High-Accuracy Classification:** Predicts churn with 87.76% precision.
* **Feature Importance:** Ranks variables like 'Monthly Income' and 'Overtime' to show why employees leave.
* **Automated Pipeline:** Clean, modular Python code that handles data preprocessing and encoding automatically.

## Tech Stack
* **Language:** Python
* **ML Library:** Scikit-Learn
* **Data Handling:** Pandas, NumPy
* **Visualization:** Matplotlib / Seaborn

## Results (HR Insights)
The model identified the following top 3 drivers of attrition:
1. **Monthly Income** (Retention is highly sensitive to compensation).
2. **Overtime** (High workload correlates with higher churn).
3. **Age** (Early-career employees show higher mobility).
