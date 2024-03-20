# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to develop machine learning models capable of predicting loan statuses based on financial information. The dataset contained various features related to loans, such as loan size, interest rate, borrower income, etc., and the target variable was the loan status, which indicates whether a loan is healthy or high-risk.

Financial Information and Prediction Target
The dataset contained information on loans, including attributes such as loan size, interest rate, borrower income, etc. The task was to predict the loan status, which could be either 0 for a healthy loan or 1 for a high-risk loan.

Variable Information
To gain insights into the distribution of loan statuses, a basic analysis was performed using the value_counts() function, revealing the number of healthy and high-risk loans in the dataset.

Machine Learning Process
The machine learning process involved several stages, including data preprocessing, model selection, training, evaluation, and interpretation of results.

Methods Used
Various machine learning algorithms were explored, including logistic regression, to build predictive models for loan status classification.

## Results

Machine Learning Model 1: Logistic Regression
Accuracy: 99% (both)
Precision: 100% (healthy), 85% (high-risk)
Recall: 99% (healthy), 91% (high-risk)

## Summary

The logistic regression model performs well, showing high accuracy, precision, and recall scores. It effectively distinguishes between healthy and high-risk loans. Its balanced performance makes it a reliable choice for predicting loan status, especially for identifying high-risk loans accurately. Therefore, the logistic regression model is recommended for practical use
The model's performance can vary based on the problem at hand. For instance, accurately predicting high-risk loans (label 1) may be more critical in minimizing financial losses. However, achieving a balance in predicting both 0 and 1 labels is generally desirable for overall accuracy. Therefore, the importance of predicting 1's versus 0's can impact the model evaluation and selection process.
