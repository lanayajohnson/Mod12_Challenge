# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

We can measure a model’s performance based on the differences between its predicted and its actual values. Risky Credit Loans vs Healthy Credit loans.

* Explain what financial information the data was on, and what you needed to predict.

The financial information the data was on was credit risk imbalances and predicted a Logistic Regression Model with Resampled Training Data.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

To predict y labels, value_counts means under categorical variables, it counts the number of categories in that variable.

* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

We choose a model appropiate for data, let the model learn based on existing data by fitting the data, and have the model make predictions for the future data.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

*Balanced accuracy scores calculate the accuracy scores and evaluates imbalanced classes.
*Recall measures the number of actually risky loans that the model correctly classified as risky.
*Precision measures how confident we are that the model correctly made the positive predictions.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

Model 1 Accuracy score is 99% accurate.
Model 1 Precision is 100% for low risk loans and 86% for high risk loans.
Model 1 Recall is 100% for low risk loans and 90% for high risk loans.

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

Model 2 Accuracy score is 94% accurate.
Model 2 Precision score is 97% for low risk loans and 2% for high risk loans.
Model 2 Recall score is 97% for low risk loans and 2% for high risk loans.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) If you do not recommend any of the models, please justify your reasoning.

The Original Data vs the Testing Data in comparison to both precision and recall, has a 3% decrease. In both models, the precision and recall scores remained the same value. The higher risk credit loans values decreased significantly from Model 1 to Model 2. There is a small number of high-risk loan labels in both Models. Performance does depend on the problem we are trying to solve. Model 2 is a better model because as mentioned, there is a smaller number of high risk loans than Model 1.











