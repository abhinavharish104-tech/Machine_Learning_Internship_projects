# Loan Default Prediction System

## Problem Statement
Financial institutions face significant losses due to loan defaults. 
The goal of this project is to build a machine learning model that predicts whether a loan applicant is likely to default or repay the loan based on historical applicant data.

This allows banks to:
- Reduce financial risk
- Improve approval decisions
- Automate credit assessment

---

## Dataset
Loan prediction dataset containing demographic and financial attributes:

Features:
Gender, Married, Dependents, Education, Self_Employed,
ApplicantIncome, CoapplicantIncome, LoanAmount,
Loan_Amount_Term, Credit_History, Property_Area

Target:
Loan_Status (Default / Non-Default)

---

## Project Workflow

1. Data Preprocessing
- Removed Loan_ID
- Handled missing values
- Encoded categorical features (Label Encoding / OneHotEncoding)
- Feature scaling where required

2. Exploratory Data Analysis
- Distribution plots of income and loan amount
- Loan approval vs credit history comparison
- Correlation heatmap

3. Model Training
Train-test split: 80-20

Models tested:
- Logistic Regression
- Decision Tree
- Random Forest (Tuned)

4. Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

## Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|------|------|------|------|------|
| Logistic Regression | 0.86 | 0.84 | 0.99 | 0.91 |
| Decision Tree | 0.75 | 0.86 | 0.76 | 0.80 |
| Random Forest | 0.89 | 0.90 | 0.95 | 0.93 |

Final Selected Model: Random Forest

Hyperparameters:
n_estimators = 200
max_depth = 5
min_samples_split = 5

ROC-AUC Score: 0.878

---

## Key Insights
- Credit history is the strongest predictor of loan repayment
- Higher income improves approval probability
- Property area influences risk category
- Deep trees overfit financial data — controlled depth improves generalization

---

## Feature Importance
Top influencing factors:
1. Credit History
2. Loan Amount
3. Applicant Income
4. Property Area

---

## Files
notebooks/ → Jupyter notebooks
models/ → Saved trained model
images/ → Visualizations
README.md → Project documentation

---

## Conclusion
Random Forest provided the best balance between identifying defaulters and avoiding false approvals.

The model successfully predicts loan default risk and can be used as a decision-support tool for loan approval systems.

---

## Future Improvements
- Use XGBoost for higher performance
- Add external financial indicators (CIBIL score)
- Deploy as web application using Streamlit
