# Project - Time Series


## Objective

The Clean Taxi company has collected historical data on taxi orders at airports. To attract more drivers during peak periods, you need to predict the number of taxi orders for the next hour.
- Main metric: RMSE


## Data

The data is in the /datasets/taxi.csv file.

The number of orders is in the 'num_orders' column (from the English number of orders).

## Libraries used

- pandas
- matplotlib
- seaborn
- numpy
- warnings
- time
- scipy
- sklearn
- lightgbm


## Main steps

1. Load and resample data
2. Data analysis, decomposition to trend, seasonal and periodic components
3. Prepare features for time series predictions
4. Train Linear Regression model with different hyperparameters
5. Train Random Forest model with different hyperparameters
6. Train Gradient Boosting model with different hyperparameters
7. Analyse and compare results of each model on test data
