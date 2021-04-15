# Project - Autos


## Objective

Service for the sale of used cars "Not bit, not beautiful" is developing an application to attract new customers. In it, you can quickly find out the market value of your car.

Historical data is at your disposal: technical characteristics, equipment and prices of cars. You need to build a model to determine the cost.

Important for the customer:

- the quality of the prediction;
- prediction speed;
- studying time.

Main metric: RMSE


## Data

The data is in the file /datasets/autos.csv

Features:

    DateCrawled - date of downloading the questionnaire from the database

    VehicleType - the type of vehicle body

    RegistrationYear - year of vehicle registration

    Gearbox - transmission type

    Power - power (l. From.)

    Model - car model

    Kilometer - mileage (km)

    RegistrationMonth - month of vehicle registration

    FuelType - type of fuel

    Brand - car brand

    NotRepaired - was the car being repaired or not

    DateCreated - the date the profile was created

    NumberOfPictures - number of car photos

    PostalCode - postal code of the profile owner (user)

    LastSeen - date of last user activity

Target: 
  
    Price - price (euro)


## Libraries used

- pandas
- matplotlib
- seaborn
- numpy
- warnings
- time
- math
- sklearn
- lightgbm


## Main steps

1. Load data
2. Preprocess and analyse data
3. Prepare features for time series predictions
4. Train Gradient Boosting model with different hyperparameters
5. Train Decision Tree Regressor model with different hyperparameters
6. Train Random Forest Regressor model with different hyperparameters
7. Analyse and compare results of each model on test data
