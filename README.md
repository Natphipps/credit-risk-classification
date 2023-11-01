# credit-risk-classification
module 20 challenge

# Challenge Overview

The purpose of this challenge was to practice machine learning techniques such as logistic regression to evaluate loan risk. The dataset included information such as:

- loan size

- interest rate

- borrower income

- debt-to-income

- number of accounts

- derogatory marks

- total debt

- loan status

The data was first broken down into training and testing sets. The training dataset was used to create a logistic regression model which was then applied to the testing data. The model's performance was evaluated by generating a confusion matrix, and a classification report. The model was evaluated based on how well it predicted 0(healthy loan) and 1(high-risk loan) labels. 

The second part of this challenge was to resample the data using RandomOverSampler from the imbalanced-learn library. RandomOverSampler takes the minority class, and picks random samples with replacement. Oversampling addresses the problem of class imbalance in training datasets. A new logistic regression model was generated using the resampled data, and the model's performance was evaluated by using the same techniques used in the first model.

# Results

The model's performance was broken down into the following classification metrics:

- Accuracy: Measures the percentage of correct predictions the model made.

- Precision: Measures the proportion of correctly predicted positive instances.

- Recall: Measures the number of true positives that were correctly identified. 

Model 1:

- Accuracy: The accuracy score for model 1 was approximately 95%

- Precision: Model 1 had a precision score of 100% for healthy loans, and an 85% precision score for high-risk loans.

- Recall: Model 1 had a recall score of 99% for healthy loans, and a 91% recall score for high-risk loans.

Model 2:

- Accuracy: Model 2 had an accuracy score of approximately 99%

- Precision: Model 2 had a precision score of 100% for healthy loans, and 84% for high-risk loans.

- Recall: The recall score for both healthy loans, and high-risk loans was 99%.

# Summary

Overall, the two model's were fairly similar. Model 2 did have a lower accuracy percentage for high-risk loans, however it was only a 1% difference. Model 2 also has better recall, and similar precision for healthy loans. I would recommend the company use the second model instead of the first.

# Technologies 

- python

- Jupyter Notebook

- Pandas

- sklearn

- imblearn



