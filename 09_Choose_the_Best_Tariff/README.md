# Project - Tariffs


## Objective

The mobile operator "Megaline" found out: many customers use archived tariffs. They want to build a system that can analyze customer behavior and offer users a new tariff: "Smart" or "Ultra".

You have at your disposal data on the behavior of customers who have already switched to these tariffs. It is necessary to build a model for the classification problem, which will select the appropriate tariff

Main metric: Accuracy


## Data

Each object in the dataset is information about the behavior of one user per month.

It is known:

- сalls - number of calls,
- minutes - total duration of calls in minutes,
- messages - number of sms messages,
- mb_used - consumed internet traffic in MB,
- is_ultra - what tariff did you use during the month ("Ultra" - 1, "Smart" - 0).


## Libraries used

- pandas
- matplotlib
- seaborn
- numpy
- sklearn


## Main steps

1. Load preprocessed dataset
2. Train and investigate different models with various hyperparameters: DecisionTreeClassifier, RandomForestClassifier, LogisticRegression
3. Compare models on test dataset
