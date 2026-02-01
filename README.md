# Employee-Attrition-Analysis-Report
Employee Attrition Analysis identifying key drivers of turnover. This repository features data cleaning, exploratory data analysis (EDA), and predictive modeling to uncover patterns in employee behavior. Includes actionable insights and retention strategies to help organizations reduce attrition and improve workplace satisfaction.

# Employee Attrition Analysis

## Project Overview

This project focuses on identifying the key factors that influence employee turnover within an organization. By analyzing an HR dataset using both statistical tools and machine learning, the project aims to provide actionable insights to improve employee retention and organizational stability.

The analysis revealed that while **83.8%** of the workforce was retained, **16.2%** left the company, with factors like Overtime, Monthly Income, and Job Satisfaction playing the most significant roles in these decisions.

## Technologies Used

* **MS Excel:** Used for initial data inspection, pivot table summaries, and statistical charts.
* **Python (Jupyter Notebook):** Used for advanced data cleaning, visualization, and predictive modeling.
* `pandas`: Data manipulation and cleaning.
* `seaborn` & `matplotlib`: Exploratory Data Analysis (EDA) and visualizations.
* `scikit-learn`: Implementation of a Decision Tree Classifier for feature importance.



## Dataset Description

The analysis was performed on an HR Attrition dataset containing various employee attributes, including:

* **Demographics:** Age, Gender, Education.
* **Employment Details:** Monthly Income, Job Role, Years at Company (Tenure), Overtime status.
* **Subjective Metrics:** Job Satisfaction, Work-Life Balance, Environment Satisfaction.
* **Target Variable:** Attrition (Yes/No).

## Key Features & Analysis

1. **Data Cleaning:** Handled missing values, removed duplicates, and encoded categorical variables for machine learning readiness.
2. **Exploratory Data Analysis (EDA):**
* Visualized distributions of age and salary for attrited vs. retained groups.
* Identified patterns in job satisfaction levels.


3. **Correlation Analysis:** Tested relationships between tenure, income, and attrition.
4. **Predictive Modeling:** Used a Decision Tree model to rank the importance of different features.
* **Top Predictor 1:** Overtime (Employees working extra hours showed significantly higher attrition).
* **Top Predictor 2:** Monthly Income (Lower income brackets were more likely to leave).
* **Top Predictor 3:** Job Satisfaction (Low satisfaction scores correlated with high turnover).



## Key Insights

* **Work-Life Balance:** Excessive overtime is the strongest indicator of potential attrition.
* **Compensation:** There is a clear negative correlation between monthly income and the likelihood of leaving.
* **Tenure:** New employees (lower tenure) are at a higher risk of leaving compared to long-term staff.

## Recommendations

* **Overtime Management:** Review workload distribution to reduce burnout in high-risk departments.
* **Competitive Compensation:** Adjust salary structures for entry-level or low-income roles to align with market standards.
* **Retention Programs:** Focus engagement initiatives on employees within their first few years at the company.

## How to Run the Analysis

1. Open the `HR-Employee-Attrition.csv` file in MS Excel to view pivot summaries.
2. Launch the Jupyter Notebook to run the Python scripts for visualizations and the Decision Tree model.
3. Refer to the `Employee Attrition Analysis Report.docx` for the full summary of findings.
