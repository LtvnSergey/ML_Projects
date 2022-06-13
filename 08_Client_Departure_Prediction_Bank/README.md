# Project - Customer Churn


## Objective

Clients started leaving Beta-Bank. Every month. A little, but noticeable. Bank marketers figured it was cheaper to retain current customers than to attract new ones.

It is necessary to predict whether the client will leave the bank in the near future or not. You have been provided with historical data on customer behavior and termination of agreements with the bank.

Build a model with an extremely high F1-measure. To deliver the project successfully, you need to bring the metric to 0.59.

Main metric: F1

Additional metric: AUC-ROC


## Data

Data source: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

Features:

     RowNumber - the index of the row in the data

     CustomerId - unique customer identifier

     Surname - surname

     CreditScore - credit rating

     Geography - country of residence

     Gender - gender

     Age - age

     Tenure - the number of properties the client has

     Balance - account balance

     NumOfProducts - the number of bank products used by the client

     HasCrCard - credit card availability

     IsActiveMember - client activity

     EstimatedSalary - estimated salary


Target:

     Exited - the fact of the client's departure


## Libraries used

- pandas
- matplotlib
- seaborn
- numpy
- warnings
- sklearn


## Main steps

1. Load and analysis of dataset
2. Select and preprocess features for prediction
3. Train RandomForestClassifier model disregarding the class imbalance 
4. Train RandomForestClassifier model with class weights
5. Train RandomForestClassifier model using upsampling approach
6. Train RandomForestClassifier model using downsampling approach
7. Compare results of different models on test data
