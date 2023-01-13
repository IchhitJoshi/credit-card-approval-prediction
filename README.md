# R Studio Project for Credit Card Approval Prediction using Logistic Regression Model

I built a machine learning-based classifier that predicts if a credit card application will get approved or not, based on the information provided in the application.


## Introduction to the Dataset

This project is about answering the central question whether or not it is possible to predict whether or not a credit card applicant gets approved to get a credit card. Does the approval have anything to do with the applicant's gender, age, income, or if they have a driver's license? I will be answering this question and figure out what variables help in increasing the odds of success for approval.

I got this dataset from Kaggle. 

**Data source:** 

<a href="https://www.kaggle.com/datasets/samuelcortinhas/credit-card-approval-clean-data?resource=download&select=clean_dataset.csv">Credit Card Approvals (Clean Data)</a>

## Logistic Model

- Model explains 82.6% of the variance in train data set
- Model successfully predicted 86.38% of the observations in the test data set

## Conclusion

The model was really successful in predicting who gets approved for a credit card and I am very happy with results. We have now discovered that according to our model, an applicant needs to have the following in order to have higher odds of approval for credit card : 

1. Many years of employment 
2. A prior default, which means the applicant has accounts go delinquent before submitting this credit card application
3. High credit score 
4. High source of income
