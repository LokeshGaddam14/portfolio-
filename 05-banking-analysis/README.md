# Automated Bad Loan Detection System for Banking

## Project Overview
This project implements an automated system for identifying bad loans in banking datasets. It combines data quality audits with machine learning to detect problematic loans early and prevent financial losses.

## Objective
- Identify patterns in bad loans vs. good loans
- Build a predictive model for loan default risk
- Automate data quality checks on loan portfolios
- Create early warning system for risky loans
- Generate actionable insights for loan portfolio management

## Technologies Used
- Python 3.x
- Scikit-learn for machine learning
- XGBoost/CatBoost for gradient boosting
- Pandas & NumPy for data processing
- Matplotlib & Seaborn for visualization
- SQL for data queries
- Jupyter Notebook

## Dataset
- Bank loan dataset with historical performance
- Features: Loan amount, duration, interest rate, borrower info
- Target: Binary classification (Bad/Good loan)
- Data validation and quality checks included

## Key Components
- Data Quality Audit
  - Missing value analysis
  - Outlier detection
  - Data consistency checks
  - Feature validation

- Machine Learning Models
  - Logistic Regression (Baseline)
  - Random Forest
  - XGBoost
  - CatBoost

- Feature Engineering
  - Loan-to-value ratio
  - Payment-to-income ratio
  - Loan age and maturity
  - Default probability indicators

## Files in This Project
- automated_bad_loan_detection.ipynb - Main notebook
- data_quality_audit.ipynb - Data validation notebook
- data/ - Loan datasets
- models/ - Trained model files
- reports/ - Analysis and audit reports

## Performance Metrics
- Precision: [To be calculated]
- Recall: [To be calculated]
- F1-Score: [To be calculated]
- ROC-AUC: [To be calculated]

## Business Impact
- Early identification of risky loans
- Reduced credit losses
- Better portfolio management
- Automated compliance reporting
