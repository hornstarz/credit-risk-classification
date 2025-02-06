# credit-risk-classification
Module 20 assignment

## Overview of the Analysis

* Purpose of the Analysis
    The purpose of this analysis was to use a logistic regression model to predict the risk of loans using the data that we were given. 
    This will help make informed decisions regarding the approval of loans and the risks involved

* Financial and Prediction Information
    The objective is to predict the loan_status, where the values of 0 indicate healthy loans and values of 1 indicate high-risk loans.
    The data used contains various financial information about loans, such as:
    The loan amount
    Interest Rate
    Borrower income
    Debt-to-income ratio

* Variables used
    The variables used included Labels(y) and Features(x)

* Machine Learning Process
    * Data Splitting - Using this dependency from -sklearn.model_selection import train_test_split- I was able to spilt the data into training and testing sets, 75% of the data for training and 25% for testing
    
    *Model Training - Using this module -from sklearn.linear_model import LogisticRegression- I instantiated a logistic regression model and trained using the training data from before.
    
    *Predictions - Made predictions using the testing data

    *Evaluation - I then used -from sklearn.metrics import confusion_matrix, classification_report- to evaluate the models performance with a confusion matrix and classification report

* Methods Used
    Logistic Regression was the algorithim used to build and evaluate the model

## Results

* Machine Learning Model:
    * Accuracy: 0.99
    * Precision:
        - Healthy loans (0): 1.00
        - High-Risk loans (1): 0.84
    * Recall:
        - Healthy loans (0): 0.99
        - High-Risk loans (1): 0.94

## Summary

The logistic regression model does show an excellent performance in predictiong both the healthy and the high-risk loans. The overall accuracy score of 0.99 suggests that the model is very reliable in classifying the loan status. For healthy loans, the 1.00 precision and 0.99 recall show an almost perfect identification. With the high-risk loans, even though the precision is much lower at a 0.84 the recall being at a 0.94 show a strong performance in the model.
Based on the evaluation mertics, the logistic regression model would be something I would recommend for use for the company.

