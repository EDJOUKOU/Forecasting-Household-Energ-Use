# Forecasting Household Energy Use

## Project Overview  
This project focuses on forecasting electricity consumption over 2-month and 3-month periods. To accomplish this, 106 weeks of historical data were analyzed. The primary goal was to develop accurate forecasting models for household energy usage, which could help inform better energy management and planning strategies.

## Data Source  
The dataset utilized for this project was sourced from Kaggle and is available at the following link: [Household Energy Dataset](https://www.kaggle.com/datasets/jaganadhg/house-hold-energy-data "Access the dataset").

## Tools and Technologies  
The project was executed using the Jupyter Notebook Integrated Development Environment (IDE) for data analysis and visualization. Various Python libraries for data manipulation, analysis, and modeling were also employed.

## Data Cleaning and Preparation  
In the initial phase of the project, the following steps were taken to clean and prepare the data for analysis:  
1. Imported all necessary Python libraries.  
2. Converted the "Date" column to the appropriate `Datetime` data type for easier manipulation.  
3. Grouped the data by weeks to reduce the dataset's size from 70,368 rows (minute-level data) to 106 rows (weekly-level data).  

## Exploratory Data Analysis (EDA)  
Exploratory analysis was conducted to better understand the dataset and prepare it for forecasting:  
1. Assessed the stationarity of the time series data and applied necessary mathematical transformations to make it stationary.  
2. Split the dataset into training and testing sets.  
3. Identified the best-fitting ARIMA model using the Akaike Information Criterion (AIC) to minimize model complexity while maintaining accuracy.  
4. Evaluated the residuals to ensure they were normally distributed, uncorrelated, and resembled white noise, which indicates a good model fit.  

## Data Analysis and Forecasting  
The forecasting models were tested on the last 8 weeks of the dataset (test set). Predictions were compared with actual electricity consumption values to evaluate performance.

## Results and Findings  
The ARIMA model demonstrated superior performance compared to baseline methods such as the mean and last-value predictions. This highlights the effectiveness of ARIMA in capturing the underlying patterns and trends in household energy usage.  
 
