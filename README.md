# Customer Churn Prediction

Predicting customer churn for a telecom provider using Logistic Regression and Random Forest, built on the IBM Telco Customer Churn dataset.

## Dataset
[IBM Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) — 7,043 customers, 21 features, 26.5% churn rate.

## Results

| Metric | Logistic Regression | Random Forest |
|--------|---------------------|----------------|
| Accuracy | 0.8055 | 0.8041 |
| Precision | 0.6572 | 0.6667 |
| Recall | 0.5588 | 0.5241 |
| F1-score | 0.6040 | 0.5868 |

**Top churn drivers:** tenure, total charges, monthly charges, fiber-optic internet, contract length.

## Team
- Sachin Gupta (12521978)
- Divyanshu (12526275)

## Tech
Python, pandas, scikit-learn, seaborn/matplotlib
