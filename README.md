# Credit Risk Analysis Report

## Overview
Utilizing data analysis techniques, we delved into a dataset containing historical lending information from a peer-to-peer lending platform. Our primary objective was to craft a model capable of assessing the creditworthiness of borrowers.

Our analysis encompassed various factors, including: 
* Loan size
* Interest rate
* Borrower's income
* Debt-to-income ratio
* Number of borrower's accounts
* Total debt
  
We constructed a logistic regression model using the LogisticRegression module from scikit-learn, trained on the training set. 
Below are the performance metrics for the model.

## Results
Logistic Regression Model:
* Precision: for healthy low-risk loans the precision is 100%, for high-risk loans the precision is 87%
* Recall: for healthy low-risk loans the precision is 100%, for high-risk loans the precision is 89%
* Accuracy: 99% 

## Summary
The logistic regression model boasts a precision and recall rate of 100% for healthy low-risk loans. It exhibits a slightly lower precision and recall rates for high risk-loans. With an accuracy score of 99%, this model is sufficient for generating loans in the low-risk category but may need to have another tier to review high-risk loans. 
