# Credit Risk Classification
# Module 12 Report

## Overview of the Analysis

In an effort to predict if a loan is high-risk or healthy, machine learning was applied to a dataset. The machine learning model was trained by looking at the indicators of:
* loan size
* interest rate
* borrower income
* debt to income rate
* total debt
* number of loans
* derogatory marks
* loan status (only used to test the model)

These factors were used to train a logistic regression model by isolating a subset of the data to train the model and comparing the derived model with the dataset not used to train the model. 

The predicted results were then compared with the known result (loan status) of the dataset to calculate the model's accuracy.

## Results

Highly accurate results were achieved using this model. Consistently the model performed better at predicting a healthy loan rather than a high-risk loan. 

* Machine Learning Model 1: Logistic Regression
    * Accuracy (Precision):
        * Healthy Loan: 100%
        * High-Rish Loan: 84%
    * Recall (Sensitivity):
        * Healthy Loan: 99%
        * High-Risk Loan: 94%
    * F1-Score (Precision/Recall Ballance)
        * Healthy Loan: 100%
        * High-Risk Loan: 89%

## Summary

The logistic regression model produces a highly predictive result when looking at the factors described above. 

It is worth noting that a high-risk result is accurate in 84% of cases. A high-risk prediction may warrant a higher interest rate, rejection of the loan, or other mitigating actions.

### Recommendation: Logistic Regression can be used to predict healthy loans with a solid degree of accuracy. Use of the model is recommended.
