# Australian Weather Prediction Project 🌦️

This project involves predicting rainfall using 10 years of daily weather observations from various locations across Australia. The dataset contains a range of features related to temperature, rainfall, wind, humidity, and other weather conditions.

[Dataset Link](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)

The dataset used in this project consists of daily weather observations with the following key features:

* Date: Date of observation
* Location: Location of the weather station
* MinTemp: Minimum temperature in degrees Celsius
* MaxTemp: Maximum temperature in degrees Celsius
* Rainfall: Amount of rainfall recorded for the day in mm
* Evaporation: Class A pan evaporation in mm (24 hours to 9am)
* Sunshine: Hours of bright sunshine in the day
* WindGustDir: Direction of the strongest wind gust
* WindGustSpeed: Speed of the strongest wind gust in km/h
* WindDir9am / WindDir3pm: Direction of the wind at 9am and 3pm
* WindSpeed9am / WindSpeed3pm: Average wind speed in km/h prior to 9am and 3pm
* Humidity9am / Humidity3pm: Humidity percentage at 9am and 3pm
* Pressure9am / Pressure3pm: Atmospheric pressure reduced to mean sea level at 9am and 3pm
* Cloud9am / Cloud3pm: Fraction of sky obscured by cloud at 9am and 3pm
* Temp9am / Temp3pm: Temperature in degrees Celsius at 9am and 3pm
* RainToday: Boolean indicating if precipitation exceeded 1mm
* RainTomorrow: Boolean target variable indicating if it will rain the next day

## Project Structure

1. Exploratory Data Analysis (EDA): Initial analysis of data distributions, correlations, and insights.
2. Data Preprocessing: Handling missing values, encoding categorical variables, and normalizing numerical features.
3. Model Building: Implemented three machine learning models to predict rainfall:
  * Random Forest
  * Logistic Regression
  * XGBoost
