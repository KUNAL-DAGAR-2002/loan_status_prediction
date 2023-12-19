# Loan Status Prediction

## Overview

This project aims to predict the loan status of applicants based on various features using a machine learning model. The dataset consists of information such as gender, marital status, dependents, education, income details, loan amount, loan term, credit history, property area, and the ultimate loan status (approved or denied).

## Dataset Columns

1. **Loan_ID**: Unique identifier for each loan application.
2. **Gender**: Applicant's gender (Male/Female).
3. **Married**: Applicant's marital status (Married/Single).
4. **Dependents**: Number of dependents.
5. **Education**: Applicant's education level (Graduate/Not Graduate).
6. **Self_Employed**: Self-employment status (Yes/No).
7. **ApplicantIncome**: Income of the applicant.
8. **CoapplicantIncome**: Income of the coapplicant.
9. **LoanAmount**: The amount of the loan applied for.
10. **Loan_Amount_Term**: Term of the loan in months.
11. **Credit_History**: Credit history of the applicant (1: Good, 0: Poor).
12. **Property_Area**: Area of the property (Urban/Rural/Semiurban).
13. **Loan_Status**: The target variable indicating loan approval status (Y: Approved, N: Denied).

## Random Forest Model

The loan status prediction was performed using the Random Forest machine learning algorithm. Random Forest is an ensemble learning method that builds multiple decision trees and merges their predictions. It is known for its high accuracy and robustness.

## Accuracy

The Random Forest model achieved an accuracy of 78% on the given dataset. This means that the model correctly predicted the loan status for 78% of the applicants in the dataset.

## Files

1. **loan_status.ipynb**: Jupyter Notebook containing the code for data exploration, preprocessing, model training, and evaluation.
2. **loan-train.csv**: CSV file containing the training dataset.
3. **loan-test.csv**: CSV file containing the test data.
4. **submission.csv**: Results for test data.

## Conclusion

The Random Forest model provides a decent accuracy of 78% in predicting loan status based on the given features. Further improvements could be explored by tuning hyperparameters, trying different algorithms, or incorporating additional relevant features.

## Dependencies

Make sure to have the following Python libraries installed:

```bash
pip install pandas scikit-learn matplotlib seaborn


