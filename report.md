# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis is to use a model to help predict credit risk by training the model with data we hav e from previous loans. The data has loan size, interest rate, borrower income, the debt-to-income ratio, the total debt, number of accounts, and the number of marks against the credit of the individual. Using these factors, the model will predict whether a loan is healthy or if it has a high risk of defaulting. The dataset includes 75,000 healthy loans, and 2500 risky loans. The first part of the process is to ensure the data is split into training groups and testing groups. 75% of the data is used to train the model, and then we can use the remaining 25% of the data to make predictions, then test whether those predictions were accurate. With this dataset, we will use Logistic Regression, then we will try it again with resampled training data. 


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * 99% precision and 100% recall when predicting healthy loans
  * 91% precision and 85% recall when predicting high risk loans
  * There was an overall accuracy score of 99%


* Machine Learning Model 2:
  * overall accuracy score if 99%
  * 100% precision and 99% recall when predicting healthy loans
  * 84% precision and 99% recall when predicting high risk loans

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* The first model performs best with a higher precision at predicting high risk loans. THe first model is recommended if the overall goal is to predict which loans may be high risk loans. 