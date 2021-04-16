# Project - Wells


## Objective

Let's say you work for the production company GlavRosGosNeft. You need to decide where to drill the new well.

You have been provided with oil samples in three regions: in each of 10,000 fields, where the quality of oil and the volume of its reserves were measured. Build a machine learning model to help determine the region where mining will generate the most profit. Analyze the potential rewards and risks using the Bootstrap technique.

Steps for choosing a location:

1. Deposits are searched for in the selected region, and the values of the attributes are determined for each;
2. Build a model and estimate the volume of reserves;
3. Deposits with the highest value estimates are selected. The number of fields depends on the company's budget and the cost of developing one well;
4. The profit is equal to the total profit of the selected fields.

Main metric: RMSE, R2


## Data

Exploration data for three regions are in files:

- geo_data_0.csv
- geo_data_1.csv
- geo_data_2.csv

id - unique identifier of the well;
f0, f1, f2 - three features of points (it doesn't matter what they mean, but the features themselves are significant);
product - the volume of reserves in the well (thousand barrels).


## Libraries used

- pandas
- matplotlib
- seaborn
- numpy
- warnings
- sklearn


## Main steps

1. Load and analysis of dataset
2. Train LinearRegression model for each region
3. Calculate predicted profit and risks from each region using bootstrap method
4. Analyse predicted profit, risks to choose the best region for well 
