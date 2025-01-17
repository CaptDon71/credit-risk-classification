# Module 12 Report Template

## Overview of the Analysis

The purpose of the analysis was to evaluate and predict the loan risk of borrowers, specifically determining whether a loan would be classified as a "high-risk loan" or a "healthy loan." This analysis aids in making informed financial decisions by leveraging machine learning models to identify risk categories and reduce potential financial losses. The dataset contained financial information about borrowers, which included key indicators of their financial health and creditworthiness. Loan Size 'loan_size', Interest Rate 'interest_rate', Borrower Income 'borrower_income', Debt-to-Income Ratio 'debt_to_income ', Number of Accounts 'num_of_accounts', Derogatory Marks 'derogatory_marks', and Total Debt 'total_debt ' were used to predict whether a loan would be classified as 'high-risk' or 'healthy'.

The machine learning analysis began with loading and reviewing the lending_data.csv dataset, followed by separating it into features (X) and the target variable (y). The data was split into training and testing sets using train_test_split while maintaining class distribution. A Logistic Regression model was chosen for its effectiveness in binary classification, trained on the training data, and used to predict loan statuses on the testing data. The model's performance was evaluated using a confusion matrix and a classification report, which showed high accuracy for predicting high-risk loans but slightly lower precision and recall for healthy loans. This process demonstrated how machine learning can be applied to predict loan risks based on financial indicators.

## Results

The regression model used in the analysis provided the following results:
*  Accuracy: The overall accuracy of the Logistic Regression model was 99%, indicating that the model correctly predicted the loan status for the vast majority of cases in the dataset.
* Precision: High-risk loans: 1.00 (perfect precision, meaning no false positives for high-risk loans).
* Healthy loans: 0.87 (some false positives, indicating room for improvement).
* Recall: 
        * High-risk loans: 1.00 (perfect recall, meaning all high-risk loans were correctly identified).
        * Healthy loans: 0.95 (very strong recall, capturing nearly all healthy loans but missing a small fraction).

## Summary

The Logistic Regression model performed exceptionally well with an overall accuracy of 99%. It showed perfect precision and recall for predicting high-risk loans (1s), ensuring no false positives or missed high-risk cases. For healthy loans (0s), the model achieved strong but slightly lower precision (0.87) and recall (0.95), indicating that it occasionally misclassified healthy loans as high-risk. Logistic Regression consistently demonstrated high performing metrics, which is well-suited for identifying high-risk loans.
The perfect recall for high-risk loans ensures that no risky borrowers are missed, which is crucial in financial decision-making. If the primary goal is to avoid missed high-risk loans, this model is ideal due to its perfect recall for 1s. However, if minimizing false positives for healthy loans (0s) is more critical, further model tuning or exploration of alternative algorithms might be necessary.

