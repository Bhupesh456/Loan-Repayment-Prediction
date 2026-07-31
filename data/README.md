# Dataset

This folder contains the datasets used in the **Loan Repayment Prediction using Logistic Regression** project.

## Files

### 1. Loan_Repayment_Training_Data.csv
- **Purpose:** Used to train and evaluate the Logistic Regression model.
- **Description:** Contains customer information along with the target variable indicating whether the loan was repaid.

### 2. Loan_Repayment_Test_Data_NoLabel.csv
- **Purpose:** Used to generate predictions on unseen data.
- **Description:** Contains customer information without the target variable. The trained model predicts the loan repayment status for these records.

## Notes
- The training dataset is used for model development and evaluation.
- The test dataset is used only for prediction and does not contain the actual repayment labels.
- No modifications were made to the original datasets except for preprocessing steps performed within the Jupyter Notebook.
