Loan Default Prediction — Logistic Regression
📌 Project Overview

This project aims to predict whether a bank customer will default on a loan using Logistic Regression.
The dataset (loan_default.csv) contains customer financial and demographic information. The target variable is defaulted (binary: 1 = default, 0 = no default).



⚙️ Methodology

Preprocessing

Split data into train/test sets (80/20).

Standardize numeric features using StandardScaler.

Modeling

Fit a Logistic Regression model to predict defaulted.

Evaluation Metrics

Accuracy

Precision

Recall

F1-score

ROC-AUC

Feature Importance

Logistic regression coefficients are analyzed to determine which feature increases the probability of default.



📊 Results (Sample Run)

Accuracy: ~0.45

Precision: ~0.36

Recall: ~0.21

F1-score: ~0.27

ROC-AUC: ~0.37

👉 The model struggles to capture defaults (low recall & ROC-AUC < 0.5).



📈 Possible Improvements

Collect more data (200 rows is too small for robust modeling).

Handle class imbalance (SMOTE, class weights).

Try alternative models (Random Forest, XGBoost).

Perform feature engineering (income-to-loan ratio, debt-to-income).
