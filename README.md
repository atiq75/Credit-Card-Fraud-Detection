# Credit-Card-Fraud-Detection
## Introduction

This notebook is an exploratory data analysis (EDA) and prediction model for credit card fraud detection. The dataset contains credit card transactions made by European cardholders in September 2013, with a total of 284,807 transactions over a two-day period.

The primary focus of this notebook is to analyze the data, understand its characteristics, and build predictive models to identify fraudulent transactions. It begins with data exploration, including the examination of transaction time, transaction amount, and their distributions.

The notebook provides model evaluations, such as accuracy scores and confusion matrices, for different classifiers, including RandomForest, KNeighbors, AdaBoost, and XGBoost, alongside the Isolation Forest model. The results of the models are compared to identify the best-performing model for this particular dataset.

In summary, this notebook combines data exploration and predictive modeling to address the important problem of credit card fraud detection, considering the challenges posed by imbalanced datasets and the need for privacy in financial transactions.

## Dataset Description

The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset present transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.
Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset.
The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning.
Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

The data set couldn't be imported in github. Here is a link to donload it: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
