# Module 20 Report

## Overview of the Analysis
* For this analysis we are using credit risk data to see if we can predict future probablity of an individual defaulting on a loan.
* Financial data includes loan_size,	interest_rate,	borrower_income,	debt_to_income,	num_of_accounts,	derogatory_marks,	total_debt,	loan_status.
* The goal is to predict the "loan_status" for future people.
* First we split the data into test and trainig sets and used the LogisticRegression model from SKLearn.
* We also resampled with RandomOverSampler to better balance our training data set.

## Results
* Machine Learning Model 1:
  * Accuracy: 0.9924164259182832
  * Precision: The model has a precision of 1.00 for class 0 and 0.87 for class 1. This means it is perfect in predicting class 0 and quite high for class 1.
  * Recall: The recall is 1.00 for class 0 and 0.89 for class 1, which again is excellent for class 0 and very good for class 1.

* Machine Learning Model 2:
  * Accuracy: 0.994180571103648
  * Precision: 0.99 for both classes.
  * Recall: The recall is also 0.99 for both classes, indicating that the model is able to identify 99% of all actual instances of each class.

## Summary
* Model 2 is definitely best as its .99 for either class
* If you want to predict 0s, Model 1 is better seemingly.

If you do not recommend any of the models, please justify your reasoning. I would use the 2nd model! More precise and accurate unless you want to predict only the 0s.
