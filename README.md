Credit Risk Analysis Dashboard

This project analyzes Lending Club loan data (2007–2018) to uncover patterns in borrower characteristics, loan purpose, and default behavior. The main goal is to support credit risk assessment with exploratory data analysis (EDA) and structured outputs for business intelligence tools.

Objectives
Clean and preprocess loan data to enable consistent analysis

Identify key variables that contribute to default likelihood

Summarize loan performance by grade, purpose, and borrower attributes

Export a Tableau-compatible dataset for building dashboards

Dataset
Source: Lending Club Loan Data (Kaggle)

Target Variable
loan_condition: Binary classification of loans into:

Good Loan – current, fully paid

Bad Loan – charged off, default, late

Sample Insights
Default rates are highest for subgrade F and G loans

Certain purposes such as 'small_business' have higher default probabilities

Correlation analysis shows relationships among interest rate, DTI, and grade

File
credit_risk_data_cleaned.csv: Cleaned dataset with loan condition and selected features

Tools
Python (Pandas, Matplotlib, Seaborn)

Jupyter/Colab

Tableau (optional for dashboard)
