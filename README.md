# Module 12 Report: credit-risk-classification

## Overview of the Analysis

The purpose of creating the model was to identify the creditworthiness of borrowers based on various factors. 

The factors that were considered were:
* The size of the loan
* The interest rate
* The borrower's income
* The debt-to-income ratio
* The number of accounts the borrower holds
* The number of derogatory marks against the borrower
* The total amount of debt
* The loan status

The dataset used had a total of 77,536 data points, which was then split into traning and testing datasets. The training dataset was used to create an initial logistic regressional model by using the LogisticRegression module from scikit-learn. After creating the initial model, it was then applied to the testing dataset in order to determine whether a loan to the borrower would be low-risk or high-risk.


## Results

* Machine Learning Model: Logistic Regression Model
    * Precision:
      * For low-risk (0's), the precision was 100%
      * For high-risk (1's), the precision was 84%
      * Macro average: 92%
      * Weighted average: 99%
   * Recall:
      * For low-risk (0's), the precision was 99%
      * For high-risk (1's), the precision was 94%
      * Macro average: 97%
      * Weighted average: 99%
   * Accuracy: 99%

## Summary

The logistic regression model predicts a healthy loan with 100% precision. On the other hand, the model predicts a high-risk loan with 84% precision. The overall accuracy of the model is at 99%. Since this model yields a high percentage for overall accuarcy, this model is great to use in order to predict both the `0` (healthy loan) and `1` (high-risk loan) labels.
