# timeseries-forecasting

This project developped in R analyzes a [bike-sharing dataset](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset), covering hourly and daily bike rentals, containing weather and seasonal information, including data on temperature, humidity, windspeed, weather conditions, and bike usage by casual and registered users.

The project focuses on predicting future bike rentals using time series specific methods such as ARIMA.

This project was completed as part of the course Machine Learning for Data Science at University Paris Cité, France. Therefore the comments and analysis are written in French.

The main steps of the project are outlined below:

- **Data Exploration** : Temperature analysis accross different seasons, correlation analysis between temperature-related variables (temp and atemp) and the total count of bike rentals (cnt), calculation of monthly statistics and investigation of how temperature is associated with bike rentals for registered vs. casual users
- **Data Preprocessing** : Plot of total bike rentals per date to examine trends, patterns, and irregularities, oulier handling and cleaning
- **Time Series Analysis** : Time series smoothing, analysis of the smoothed time series by seasonality and stationarity
- **ARIMA Model Comparaison** : Evaluation of different ARIMA models on AIC and BIC fitting criteria, without seasonal effects, using the auto.arima() function, evaluating the residuals and analyzing the ACF/PACF plots
- **ARIMA Model Forecasting**  : Forecast compariason of the next 25 observations using the chosen ARIMA model and the Auto-ARIMA model

# Repository Overview
This repository contains the following files: a [R Markdown file](TimeseriesProject.Rmd) and a [compiled version of the notebook](TimeseriesProject.html).
