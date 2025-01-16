# Forecasting Household Energy Use
## Project overview
This project aims at forecasting electricty consumption for a 2 month-period. 106 weeks of data were used to achieve that. 

## Data source
The data used for this project was retrieved from kaggle at the following link : [Dataset](https://www.kaggle.com/datasets/jaganadhg/house-hold-energy-data "access the dataset")

## Tools
Jupyter notebook IDE for data analysis

## Data cleaning and preparation
In the initial phase, the following tasks were performed:
1. import the necessary libraries
2. Change the data type of the Date column to Datetime
3. Perform a grouping to reduce the data size to weeks instead of minutes (shrinked the data from 70368 to 106 rows)


## Exploratory Data analysis
1. Check for stationarity and apply mathematical transformations according
2. Divide the data into train and test sets
3. Find the best ARIMA model with the Akaike Information Criteria (AIC)
4. Check whether the residuals are normally distributed and uncorrelated (look like white noise)

## Data analysis
Forecasts have been attempted within 8 weeks in the test set and compare with the actual results

## Results

 
