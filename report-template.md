# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

## I used the Logistic Regression Model for the first model.
## After predicting the model, I used the balenced_accuracy_score and I came up with 0.9520479254722232 after running it.
## After running the classification_report_imbalenced, for the precision score for 0 I got 1.00 and for 1 I got 0.85.
## For the recall scores for 0 I got 0.99 and for 1 I got 0.91.


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  
  ## I ran the Logistic Regression Model again this time with the resampled data.
  ## Next I ran the balenced_accuracy_score I came up with 0.9936781215845847 after running it.
  ## For the precision score of model 2, for 0 I got 1.00 and for 1 I got 0.84.
  ## For the recall score of model 2, for 0 I got 0.99 and for 1 I got 0.99.
  

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.


## After running the 2 Logistic Regression Models, one with the normal data and one with the resampled data, I believe the second model predicts the recall much better but the precision is lower by 0.01 for 1.


