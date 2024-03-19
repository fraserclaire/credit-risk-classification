# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

* The purpose of the analysis is to assess the ability for a model to predict boroowers loan risk based on their creditworthiness.
* The dataset used to train and evaluate the model represents historical lending activity from a peer-to-peer lending service company.
* Loan status predictions were made based on: loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and total debt.
* The predicted loan status results were ultimately assigned to either a "healthy" or "high-risk" loan category.


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

* The model is perfect at predicting good candidates for healthy loans, however is only correct at prediciting high-risk loans 84% of the time.
* Almost all (99%) healthy loans are predicted by this model, with a 94% ability to correctly predict high-risk loans.
* At 99% accuracy, high precision, and recall, this model seems to perform well at identifying the correct loan category.
* 