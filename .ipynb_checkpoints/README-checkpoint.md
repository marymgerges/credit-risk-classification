# Credit Risk Classification Report

## Overview of the Analysis

### In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

#### * Explain the purpose of the analysis.
##### The purpose of the analysis is to evaluate for accuracy a data model that predicts if a loan borrower would have a healthy or high-risk loan.

#### * Explain what financial information the data was on, and what you needed to predict.
##### The data set had the following financial information:
##### Loan size
##### Interest rate
##### Borrower income
##### Debt-to-income ratio
##### Nmber of accounts
##### Derogatory marks
##### Total debt
##### Loan Status
##### Using this information, I was able to predict if the borrower would have a high-risk loan or a healthy loan.

#### * Describe the stages of the machine learning process you went through as part of this analysis.
##### The machine learning process began by cleaning up the data, then doing some analysis to explore the data being used. Next, it selected X and y parameters in order to test them, then split test, then train the datasets. Lastly, it did a model fit to test the accuracy of the test sample.

#### * Briefly touch on any methods you used (e.g., `LogisticRegression`).
##### I used LogisticRegression in order to predict the loan status, meaning if the borrower would have a healthy or high-risk loan.


## Results

### Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

#### * Machine Learning Model:
#### * Description of Model Accuracy, Precision, and Recall scores.
##### Accuracy: 99%
##### Precision: 92%
##### Recall: 95%


## Summary

### Summarize the results of the machine learning model, and include a recommendation on whether to use the model to use. For example
#### * Does the model seem to perform well? How do you know it performs well?
##### Yes, the model seems to perform well since it has a 99% accuracy to predict if a loan will be healthy or high-risk.


#### * Does performance depend on the problem we are trying to solve?
##### In this case, it seems more important to predict the `1`'s, meaning the high-risk loans.