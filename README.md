# credit-risk-classification

## Overview of the Analysis
This repo contains python code that aims to analyse the effectiveness of machine learning analysis on predicting the creditworthiness of borrowers. The hypothesis is using financial data such as a borrowers' loan size, interest rate, borrower income and more, loans can be correctly identified as healthy loans or high-risk loans.

To achieve this outcome, the following steps were undertaken:
1. Financial data of borrowers were loaded into a dataframe
2. The outcome was seperated from the independant financial variables and saved into new dataframes
3. training and test datasets were created using the train_test_split function
4. A logistic regression model was created and trained using the training dataset
5. Predictions were now made using the trained regrssion model, and the test dataset
6. A confusion matrix and classification report was generated to evaluate the accuracy and results of the model

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Logical Regression Model
* Accuracy: 99% Accurate indicating the model is correctly predicting 99% of loans
* Precision: 100% for healthy loans and 85% for high-risk, showing when it predicts a healthy loan, it is 100% correct whilst 85% correct when predicting high-risk
* Recall: 99% and 91% for healthy loans and high-risk loans respectively. This indicates for all healthy loans, 99% was identified correctly and 91% for high-risk loans. 

## Summary

The logistics regression model results show that it has very high accuracy, precision and recall and is capable of reaching the correct loan classification the majority of the time. The strengths of using this logistics regression model is it is able to correctly predict which borrowers will result in healthy loans 100% of the time. Its weakness is its prediction capability for high-risk loans which was the lowest at 85%, indicating 85% of predicted high-risk loans were correct and 15% were in fact healthy loans. However, this model is still appropriate to use for evaluating credit-worthiness. 
