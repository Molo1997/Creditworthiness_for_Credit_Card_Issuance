# Credit Worthiness Prediction for Credit Card Approval

## Project Overview
This project implements a predictive model to assess the credit worthiness of banking customers for credit card approvals. The model analyzes anonymized customer data to determine if applicants are likely to make regular payments.

## Dataset
The dataset contains customer information including:
- Demographics (gender, age, marital status)
- Financial details (income, employment type)
- Asset ownership (car, property)
- Family information
- Contact details
- Target variable: credit reliability (1=reliable, 0=otherwise)

## Approach
1. **Data Preprocessing**
  - Handling missing values
  - Feature encoding
  - Creating derived features

2. **Exploratory Analysis**
  - Distribution analysis
  - Target variable imbalance assessment
  - Correlation analysis

3. **Model Development**
  - Logistic Regression
  - Random Forest Classification
  - Class imbalance handling (SMOTE, undersampling)
  - Hyperparameter optimization

4. **Evaluation**
  - Classification metrics
  - Confusion matrix analysis
  - ROC AUC score
  - Feature importance analysis

## Key Findings
- Random Forest outperformed Logistic Regression
- Optimal threshold adjustment improved model performance
- Identified key factors influencing credit worthiness
- Achieved strong performance with minimal false negatives

## Implementation
- Python, scikit-learn, pandas
- matplotlib, seaborn
- imbalanced-learn
