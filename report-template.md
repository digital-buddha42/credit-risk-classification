# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* For this analysis we are using credit risk data to see if we can predict future probablity of an individual defaulting on a loan.
* Financial data includes loan_size,	interest_rate,	borrower_income,	debt_to_income,	num_of_accounts,	derogatory_marks,	total_debt,	loan_status.
* The goal is to predict the "loan_status" for future people.
* First we split the data into test and trainig sets and used the LogisticRegression model from SKLearn.
* We also resampled with RandomOverSampler to better balance our training data set.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy: 0.9924164259182832
  * Precision: The model has a precision of 1.00 for class 0 and 0.87 for class 1. This means it is perfect in predicting class 0 and quite high for class 1.
  * Recall: The recall is 1.00 for class 0 and 0.89 for class 1, which again is excellent for class 0 and very good for class 1.



* Machine Learning Model 2:
  * Accuracy: 0.994180571103648
  * Precision: 0.99 for both classes.
  * Recall: The recall is also 0.99 for both classes, indicating that the model is able to identify 99% of all actual instances of each class.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best? model 2 is definitely best as its .99 for either class
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
* No, 1's and 0s are equally precise

If you do not recommend any of the models, please justify your reasoning. I would use the 2nd model! More precise and accurate.
