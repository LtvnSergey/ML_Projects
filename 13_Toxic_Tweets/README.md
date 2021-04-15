# Project - Toxic Tweets


## Objective

The Wikishop online store is launching a new service. Users can now edit and add product descriptions just like in community wikis. That is, customers propose their edits and comment on others' changes. The store needs a tool that will search for toxic comments and submit them for moderation.

Train the model to classify comments as positive and negative. You have at your disposal a dataset with markup on the toxicity of revisions.

- Main metric: F1


## Data

You have one folder with all images (/ final_files) and a csv file labels.csv with two columns: file_name and real_age.


## Libraries used

- pandas
- matplotlib
- seaborn
- numpy
- warnings
- time
- re
- textblob
- pymystem3
- nltk
- sklearn


## Main steps

1. Load data
2. Preprocess text fields: lemmatize, remove regular expressions, lowercase, remove stopwords
3. Calculate TD-IDF term-frequency times inverse document-frequency
4. Train Logistic Regression model with different hyperparameters and 'balanced' class weights
5. Train Logistic Regression model with cross-validation and different hyperparameters
6. Train Linear Support Vector Classification model with different hyperparameters
7. Compare and analyse results of trained models on test data
