# Car prices prediction

This is a simple regression project. 

The task is to predict car prices by given dataset of different car features.


## Data
Dataset is taken from the Kaggle datasets: https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho

This is a csv file.

There are 301 rows and 9 features there.


## Methodology
Data visualization

Data pre-processing (fill missing values, encode categorical data)

Feature selection (by correlation)

Cross-validation 


**Model**
I’ve tried several models:

LinearRegression

XGBRegressor

The highest accuracy was achieved by XGBRegressor


## Technologies
Python

pandas

sklearn

matplotlib

seaborn

xgboost
