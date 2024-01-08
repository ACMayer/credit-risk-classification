# Module 20 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

# Answer:
The purpose of this particular anaylsis was to design a machine learning model that would be able to predict the odds of a loan being either healthy or high risk based on a multitude of factors relating to loans including but not limited to: Loan size, interest rate, borrows income and total debt. In this specific dataset that was being analysed the loan status, which was the target variable, was binary whereby healthy loans and highrisk loans where classed by either a 0/1 respectively. 
There are different stages involved in the machine learning process, it started off with data loading where the csv is loading into a Pandas DataFrame, then the data gets examined and the types of each column was checked. The data was then split  into the labels (y-variable) and the features (x-variables). The data was then split into test and training sets. A logisitc regression model was trained using the training data. The model made predictions on the testing set and then  a confusion matrix and classfication report was produced to evaluate the model. The main machine learning process used in this anaylsis was a logistic regression model. A logigstic regression model can usually assist with predictions on classifying binary data. 


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
