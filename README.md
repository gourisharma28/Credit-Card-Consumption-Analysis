# Credit Card Consumption Analysis

## Project Overview

This project analyzes customer demographic, behavioral, and credit card transaction data to understand spending patterns and build a predictive model for credit card consumption.

## Business Objective

Financial institutions need to understand customer spending behavior to improve marketing strategies, customer segmentation, and product offerings. The objective of this project is to identify key drivers of credit card spending and predict future consumption levels.

## Dataset

The analysis uses three datasets:

* Customer Demographics
* Customer Behavior
* Credit Card Consumption Data

These datasets were merged and prepared for analysis and modeling.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Data Cleaning and Preparation
2. Exploratory Data Analysis (EDA)
3. Linear Regression Modeling
4. Model Evaluation

## Key Insights

The Linear Regression model shows that historical spending behavior is the strongest predictor of credit card consumption.

## Key Positive Drivers:
* Past credit card consumption (cc_cons_apr, cc_cons_may, cc_cons_jun)
* Debit card consumption patterns (dc_cons_apr, dc_cons_may)
* Credit activity frequency (credit_count_jun)

This indicates that customers with consistent past spending behavior tend to continue higher consumption patterns.

## Key Negative Drivers:
* Several region-based variables (e.g., region_code_814, region_code_907, region_code_265)
* Debit amount in June (debit_amount_jun)

This suggests strong geographic variation in spending behavior and possible budget balancing effects between debit and credit usage.

## Repository Structure

```text
Data_Credit_Card/
├── CreditConsumptionData.xlsx
├── CustomerBehaviorData.xlsx
└── CustomerDemographics.xlsx

Notebook/
└── Credit Card CS(Linear Regression).ipynb
```

## Future Improvements

* Test advanced regression models.
* Implement feature selection techniques.
* Improve model performance through hyperparameter tuning.
