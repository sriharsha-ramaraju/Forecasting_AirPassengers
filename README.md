# Forecasting_AirPassengers
 Time Series
Dataset is from Kaggle: https://www.kaggle.com/rakannimer/air-passengers
This code provides insights into Time Series Analysis
Following operations are performed on Time Series Data
1) Basic insights such as numbers of obs in time series, start and end of the time series dates
2) converting the data frame to time series format
3) Visualising the time series
4) Visualisation technique, rolling mean and std to visualise how mean is changing over time
5) Agumented Dicker-Fullery test
Three ways to transform data to stationary series (6,7,8)
6) LOG TRANSFORM
7) SUBSTRACTION OF MOVING AVERAGE
8) DIFFERENCE OPERATOR
9) Let us use ARIMA to forecast the series..to use use ARIMA the time series has to be stationary
10) So let's check acf and pacf plots to make sure we are using correct order
11) Let us use HOLT WINTERS model
12) Splitting Data into Train and Test
13) Building ARIMA and Holt Winters model on Train data and testing it on Test data
14) Used RMSE,MAE as the metrics to choose the best model
