# loan-approval-prediction
# Loan Approval Prediction
Predict if a loan applicant will be approved based on demographic and financial features (Kaggle-inspired dataset).

### Key Steps
- EDA: Visualized distributions, correlations, and imbalances.
- Preprocessing: Imputed missing values, encoded categoricals, scaled numerics.
- Models: Logistic Regression (Baseline), Random Forest, XGBoost.
- Best Model: XGBoost with ROC-AUC 0.85 and F1 0.72.

### Insights
- Credit_History is the top predictor.
- Higher income and married applicants have better approval rates.

### Tech Stack
Python, Pandas, Scikit-learn, Seaborn, XGBoost.

[View Notebook](loan-approval-prediction.ipynb)
