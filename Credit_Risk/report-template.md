# Credit Risk Analysis Report
## Module 12

## Overview of the Analysis

* The purpose of the analysis is to assess the ability for a model to predict borrowers loan risk based on their creditworthiness.
* The dataset used to train and evaluate the model represents historical lending activity from a peer-to-peer lending service company.
* A logisitic regression model was created using the 'lbfgs' solver, then a subset of the data were used to train the model.
* Loan status predictions were made based on: loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and total debt.
* The predicted loan status results were ultimately assigned to either a "healthy" or "high-risk" loan category and these predicted outcomes were evaluated against true outcomes to assess model performance.

## Results

* Machine Learning Model:
    * Accuracy: 99%
    * Precision:
        * healthy loan: 100%
        * high-risk loan: 84%
    * Recall:
        * healthy loan: 99%
        * high-risk loan: 94%
    

## Summary

* The model is perfect at predicting good candidates for healthy loans, however is only correct at prediciting high-risk loans 84% of the time.
* Almost all (99%) healthy loans are predicted by this model, with a 94% ability to correctly predict high-risk loans.
* At 99% accuracy, high precision, and recall, this model seems to perform well at identifying the correct loan category.
* The training data includes a much higher ratio of healthy to high-risk loans, which may hinder the ability to predict high-risk loans. Including more healthy loan data to train the model may improve the precision and recall scores for high-risk loans and ultimately increase the accuracy of the model.
* This model seems appropriate to use for predicting borrowers loan risk, performing particularly well in prediciting healthy loans. However, it could be improved by retraining the model including more high-risk loan data.