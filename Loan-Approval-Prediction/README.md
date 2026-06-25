# Loan Approval Prediction

## Project Overview

This project predicts whether a loan application will be approved based on applicant information such as income, education, loan amount, credit history, and employment status.

## Dataset

The project uses the Loan Prediction Dataset containing applicant demographic and financial information.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Data Preprocessing

* Handled missing values using mode and median imputation.
* Removed unnecessary columns.
* Encoded categorical variables using Label Encoding.
* Applied feature scaling using StandardScaler.

## Machine Learning Models

### Logistic Regression

* Training Accuracy: 79.84%
* Testing Accuracy: 86.18%
* ROC-AUC Score: 0.8019

### Random Forest

* Training Accuracy: 100%
* Testing Accuracy: 82.93%
* ROC-AUC Score: 0.7950

## Results

Logistic Regression achieved the highest testing accuracy and showed better generalization performance compared to Random Forest, which exhibited overfitting.

## Important Features

* Credit_History
* ApplicantIncome
* LoanAmount
* CoapplicantIncome

## Conclusion

Logistic Regression is recommended for deployment due to its superior testing performance and lower risk of overfitting.

## Files

* Loan_Approval_Prediction.ipynb
* Loan_Approval_Prediction_Report.pdf
* README.md

## Author

Saniya Shiya
Data science intern
