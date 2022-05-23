# Power Consumption in Teotuan City

This repository contains source code and materials used to model power consumption 
time series data from Teotuan City, Morocco. This project was completed as required
in the MSCA 31006: "Time Series Analysis & Forecasting" course at the University of Chicago


### Data

The selected time series dataset was obtained from the University of California, Irvine's Machine Learning data repository
and can be found by clicking the following link:

https://archive.ics.uci.edu/ml/datasets/Power+consumption+of+Tetouan+city

Power consumption as measured in three zones in Teotuan City, Morocco, was collected along with 
select weather features, including temperature, humidity, and wind speed in Teotuan City. Further, 
diffuse flow information was also included in the dataset. Observations were collected every 10 
minutes throught the year 2017 (from January 1st through December 30th). In total, the dataset 
contained 52,316 observations. 

This dataset was studied in 
"Comparison of Machine Learning Algorithms for the Power Consumption Prediction:-Case Study of Tetouan city",
Salam, A., & El Hibaoui, A. (2018, December), in 2018 6th International Renewable and Sustainable 
Energy Conference (IRSEC), IEEE (Institute of Electrical and Electronics Engineers).


### Goals and Objectives

Our goal for this project is to analyze and model the time series data with a minimum
of four forecasting models. Based on our selection crtieria, forecasting metrics, and accuracy, we will make note of the best performing model. We will evaluate our models, data,
and discuss how our model forecasting can be improved as needed.

Our data drives at an important problem statement in today's methods for forecasting load
in modern electric grids. Accurate forecasts of load can be used to proactively perform network switching, which results in alleviating current overloads. Alleviating current overloads can lead to:

* Longer shelf life of expensive and difficult to procure electric equipment in our grids, including transformers, breakers, switches, fuses, capacitors, and electric lines; and
*  Reduced count and duration of of power outages


### Models Implemented

As we performed exploratory data analysis to gain an understanding of our data, we developed a list of time series models that fit the criteria of being usable in forecasting a dataset as ours (e.g., seasonality). As such, we implemented the following time series models:

* Auto ARIMA
* Holt Winters with Exponential Smoothing
* Long Short Term Memory (LSTM)
* Prophet


### About Us

Our team is comprised of Martin Copello, Kartik Garg, Maya Zhao, and David Wen. We are students of the University of Chicago MScA program, and this project was completed in fulfillment of the requirements of the program's Time Series Analysis and Forecasting course.
