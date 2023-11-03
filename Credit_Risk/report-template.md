# Module 20 Report Template

## Overview of the Analysis

In this analysis, the goal was to build machine learning models for predicting loan status, specifically differentiating between "healthy loans" (0) and "high-risk loans" (1). I utilized financial data, including variables like credit scores, loan amounts, and employment length, to make these predictions.

The Machine Learning Process Was:
1. Handling missing data and splitting the dataset into training and testing sets
2. Chose Logistic Regression model for the classification task
3. Trained the model on the training data
4. Assessed model performance using accuracy, precision, and recall.

## Results

* Logistic Regression Model:
  * Balanced Accuracy: 0.95
  * Precision for Class 0 (Healthy Loans): 1.00
  * Precision for Class 1 (High-Risk Loans): 0.85
  * Recall for Class 0 (Healthy Loans): 0.99
  * Recall for Class 1 (High-Risk Loans): 0.91



## Summary

For "healthy loans" (class 0):

It has a precision of 1.00, meaning it rarely makes mistakes.
It captures nearly all of the actual healthy loans with a recall of 0.99.
The F1-Score is a perfect 1.00, indicating a great balance between precision and recall.


For "high-risk loans" (class 1):

It's pretty good at spotting them with a precision of 0.85, but it does make some incorrect calls.
It does a good job at catching most of the real high-risk loans with a recall of 0.91.
The F1-Score is 0.88, showing that it strikes a decent balance between precision and recall.

Overall, the model is incredibly accurate with an accuracy rate of 99%. It's also quite proficient at distinguishing between healthy and high-risk loans.
