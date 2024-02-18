# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis was to develop a machine learning model that predicts the likelihood of a loan defaulting or a loan getting repayed. This model would be used for analyzing customers to make better decisions on who to lend and who not to lend money to. Some of the factors of the data were loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt, and if the loan is healthy or high risk. The measure that we would try to predict is whether or not the loan is safe or high risk. Therefore, the target variable is whether the loan is high risk or not. According to this data set over 75000 loans were considered safe while 2500 were considered high risk. The basic machine learning process is to separate the target from the features. Then, you want to split the data into training and testing sets. After than you can choose a machine learning model, in this case we used a logistic regression modeel to make a prediction on the data. Futhermore, another model was built to see if the accuracy of the first model could be improved. It essentially resampled the data to reduced the imbalance between the high risk and safe loans to provide sort different data to work with.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * The logistic regression model predicted the healthy loans extraordinarily well with a precision of 100%. Furthermore, the recall and f1-scores were 100% as well which indicated it caught all of the positive cases and all the positive predictions were correct. However, the precision for the high-risk loans was only 87% correct in identifying that the model correctly predicted the instances labeled as 1. Furthermore, the recall was 89% correct in finding all positive instances. Therefore, the model could be slightly improved. The overall accuracy of the model was 99% which is very high so I would trust this model.



* Machine Learning Model 2:
  * The resampled logistic regression model predicted the healthy loans extraordinarily well with a precision of 100%. Furthermore, the recall and f1-scores were 100% as well which indicated it caught all of the positive cases and all the positive predictions were correct. However, the precision for the high-risk loans was only 87% correct in identifying that the model correctly predicted the instances labeled as 1. However, the difference in the model comes into play here. The recall was 100% accurate which means it found all positive instances. The overall accuracy was 100% so I would definetly use this model to predict where loans are safe or not.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* I feel like both models performed extremely well so I would use either for my predictions. However, the recall score for 1 (high risk loan) was slightly better in the second model. I would argue that this is a more important parameter to have more accurate because it determine the loans that are not safe. This parameter could put the lender in jeopardy because they have a risk of losing money.
