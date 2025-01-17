# Supervised Learning Challenge 20: Loan Risk Prediction  

This project focuses on using supervised learning techniques to train and evaluate a machine learning model that predicts loan risk. By analyzing historical lending data from a peer-to-peer lending service, we aim to classify borrowers as high-risk or healthy based on their creditworthiness.  

## Project Overview  

In this challenge, the primary objectives include:  
- Training and evaluating machine learning models to classify loan risk.  
- Applying supervised learning techniques such as logistic regression.  
- Assessing model performance using metrics like accuracy, precision, recall, and f1-score.  

---

## File Structure  

- **`Credit_Risk/Credit_Risk_Analysis_Report.md`**  
  - A detailed report summarizing the methodology, analysis, results, and conclusions.  

- **`Credit_Risk/credit_risk_classification.ipynb`**  
  - A Jupyter Notebook containing the Python code used for data preprocessing, training, and evaluating machine learning models.  

- **`Credit_Risk/Resources/lending_data.csv`**  
  - The dataset used in the analysis, containing historical lending activity and borrower information.  

---

## Dataset Information  

The `lending_data.csv` file includes key financial details about borrowers:  
- **Features:**  
  - `loan_size`: Loan amount.  
  - `interest_rate`: Annual interest rate of the loan.  
  - `borrower_income`: Annual income of the borrower.  
  - `debt_to_income`: Debt-to-income ratio.  
  - `num_of_accounts`: Number of financial accounts.  
  - `derogatory_marks`: Negative marks on credit history.  
  - `total_debt`: Total outstanding debt.  

- **Target Variable:**  
  - `loan_status`: A binary variable where:  
    - `1` indicates a high-risk loan.  
    - `0` indicates a healthy loan.  

---

## Key Steps in the Analysis  

1. **Data Preparation**  
   - Loaded the dataset using `pandas`.  
   - Separated features (`X`) and labels (`y`).  
   - Split the data into training and testing sets using `train_test_split`.  

2. **Model Training**  
   - Trained a logistic regression model with the training data using `scikit-learn`.  

3. **Model Evaluation**  
   - Generated a confusion matrix to evaluate the model’s performance.  
   - Computed precision, recall, f1-score, and overall accuracy.  

4. **Results Analysis**  
   - Compared model metrics to determine its effectiveness in predicting loan risk.  
   - Discussed whether the model meets the needs of the problem being addressed.  

---

## Results  

The analysis aimed to identify an optimal model for predicting borrower creditworthiness. The results and recommendations are presented in the report: **`Credit_Risk_Analysis_Report.md`**.  

---

## How to Use  

1. Clone or download this repository.  
2. Open the Jupyter Notebook: `credit_risk_classification.ipynb`.  
3. Follow the steps in the notebook to process the data, train the model, and evaluate its performance.  
4. Review the findings in the report: **`Credit_Risk_Analysis_Report.md`**.  

---

## Tools and Libraries  

- **Python**  
- **scikit-learn**  
- **pandas**  
- **numpy**  

---

## Author  

This project is part of Module 20: Supervised Learning Challenge and demonstrates machine learning applications in financial risk analysis.  
