# Project - Image Age


## Objective

The Khleb-Salt chain supermarket is introducing a computer vision system for processing customer photos. Photo fixation in the checkout area will help determine the age of customers in order to:

Analyze purchases and offer products that may be of interest to buyers of this age group;
Monitor the conscientiousness of cashiers when selling alcohol.

Build a model that will determine the approximate age of the person from the photograph. At your disposal is a set of photographs of people with age indication.

- Main metric: MAE


## Data

You have one folder with all images (/ final_files) and a csv file labels.csv with two columns: file_name and real_age.


## Libraries used

- pandas
- tensorflow
- seaborn
- matplotlib
- PIL


## Main steps

1. Data analysis to figure what images we have, their quality, are they representative
2. Create function for dataset loading
3. Create function for buidling neural network model
4. Create function for training model
5. Run the script with created functions on server with GPU
6. Analysis of model predictions
