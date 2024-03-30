# Weather Forecast Prediction

## Overview
The Weather Forecast Prediction project focuses on using machine learning algorithms to predict weather patterns based on historical data. By employing various predictive models, including linear regression and ridge regression, the project aims to forecast weather conditions accurately. The primary goal is to develop a robust predictive model capable of predicting daily and weekly temperature.

## Objective
The primary objective of this project is to build a predictive model capable of forecasting weather conditions with high accuracy. By utilizing historical weather data and machine learning algorithms, the project aims to predict temperature for future time periods. 

## Dataset
The dataset used for this project contains historical weather data collected over several years from various weather stations. It includes features such as temperature, precipitation, wind speed, humidity, and atmospheric pressure. The target variable may vary depending on the specific weather variable being predicted, such as maximum temperature, minimum temperature, or precipitation amount.

[(https://www.ncei.noaa.gov/cdo-web/search)]

## Methodology
* Data Preprocessing: Cleaning the dataset, handling missing values, and removing outliers.
* Model Selection: Training various machine learning models, including linear regression, ridge regression,lasso regression and KNN on the historical weather data.
* Model Evaluation: Assessing model performance using evaluation metrics such as mean absolute error (MAE), mean squared error (MSE), and coefficient of determination (R-squared).
  
## Tools and Libraries
* Python
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
  
## Results
The predictive models developed in this project demonstrate promising performance in forecasting weather conditions. Evaluation metrics such as MAE, MSE, and R-squared indicate the accuracy and reliability of the predictions. Further optimizations and refinements can be explored to enhance the models' performance and robustness.

Both Linear Regression Model and Ridge Regression Model have given the best performance with a very marginal difference in accuracy between the two. After adding more predictor variables, the accuracy improved by a factor of 0.97%. The model has also been modified to make weekly predictions, which resulted with an accuracy score of 0.85%
