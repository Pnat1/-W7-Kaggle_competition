# W7-Kaggle_competition

![](/image/diamante.jpeg)

## Description 
In this project my task is to find the best machine learning model and params for a given dataset. The dataset is composed of a series of diamonds classified within their given characteristics such as color, carat, cut, price,... amongst others. The aim is to generate two dataframes and follow a train, test, split process and the neccessary regression models to achieve the best machine learning model and params for the dataset. There are a maximun of 5 submissions in the kaggle program per day. I must both be cautious and take advantage of this.


## Project Goals

- Jupyter notebooks where to show the process followed to get my submissions.

- A slide in .ppt or ipynb form with a summary of the metrics obtained and the rationale behind it.

- Must answer why do these params work better than others?


## Process

### train.csv

- Processing/cleaning the dataset: this should be later modularized in functions.

- Train a model (fit & predict) with the data in train.csv. This file does contain a y. 

    I must train, test or split the train.csv if necessary.
    
    Choose the best model regarding the metrics. In this case, the lowest RMSE (error).

- 2.1. Export the model: we don't want to invest time/RAM resources on training the model again in the future.

### test.csv

- Apply the same cleaning to test.csv. This files does NOT contain a y.

- We'll apply the already trained model from step 2 to the text.csv file. With this we'lñl generate a new column with the predicted values.

### my_submission.csv

Generate a submission.csv file with only two columns: the ID of the diamond & the predicted price (y).


## Technology

A list of technologies used within the project:

- Jupyter Notebook : Version 6.1.4
- Python: Version 3.8

## To Do's

- Improve the model
- Explore new libraries with different models

