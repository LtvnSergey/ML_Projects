# Project - Gold Recovery


## Objective

Prepare a prototype machine learning model for Digits. The company develops solutions for the efficient operation of industrial enterprises.

The model should predict the recovery rate of gold from a gold-bearing ore. You have data with parameters of extraction and cleaning at your disposal.

The model will help to optimize production in order not to launch a plant with unprofitable characteristics.

Main metric: sMAPE


## Data

The data is in three files:

- gold_recovery_train.csv - training set;
- gold_recovery_test.csv - test sample;
- gold_recovery_full.csv - initial data.

The data is indexed by the date and time the information was received (the date attribute). 

Parameters adjacent in time are often similar. Some parameters are not available because they are measured and / or calculated much later. Because of this, the test sample is missing some features that may be in the training. Also, there are no target features in the test set. The original dataset contains training and test samples with all the features.

You have the raw data at your disposal: it was simply unloaded from the storage. Before you start building the model, check them for correctness according to our instructions.

## Libraries used

- pandas
- matplotlib
- seaborn
- numpy
- warnings
- sklearn


## Main steps

1. Load data
2. Analysis of train and test datasets on different stages of gold recovery process
3. Prepare train dataset
4. Train SGDRegressor model with different hyperparameters for the first stage of the process
5. Train SGDRegressor model with different hyperparameters for the final stage of the process based on the previous predictions
6. Compare SGDRegressor model results with constant model on test dataset
