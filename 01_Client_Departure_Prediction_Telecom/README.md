# Project - Telecom


## Objective

Telecommunication operator Nedinogorazryva.com wants to learn how to predict customer churn. If it turns out that the user is planning to leave, he will be offered promotional codes and special conditions. The operator's team collected personal data about some customers, information about their tariffs and contracts.

- Main metric: AUC-ROC
- Additional metric: Accuracy


## Data

- contract.csv - information about the contract;
- personal.csv - personal data of the client;
- internet.csv - information about internet services;
- phone.csv - information about telephony services


## Libraries used

- pandas
- numpy
- seaborn
- matplotlib
- datetime
- scipy
- warnings
- time
- sklearn


## Main steps

1. Data analysis to identify features that allow you to separate regular customers from those who left
2. Preparing features for machine learning
3. Hyperparameters testing for Random Forest Classifier model
4. Hyperparameters testing for Gradient Boosting Classifier model
5. Comparing model results on test data using AUC-ROC and Accuracy metrics

