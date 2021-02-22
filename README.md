# Bike Sharing Demand

From [kaggle](https://www.kaggle.com/c/bike-sharing-demand/overview)

## Overview. 

Forecast use of a city bikeshare system.  

The data has been split into two groups:  
- training set (train.csv)  
- test set (test.csv)    

The purpose is to train the training set data using machine learning algorithms to predict the number of hourly bikeshare rentals.  
data is not included in this repository but is available for download from [kaggle](https://www.kaggle.com/c/bike-sharing-demand/overview).  

## Data Dictionary
(from [kaggle](https://www.kaggle.com/c/bike-sharing-demand/data).)
- datetime : hourly date + timestamp.   
- season :  1 = spring, 2 = summer, 3 = fall, 4 = winter.   
- holiday : whether the day is considered a holiday. 
- workingday : whether the day is neither a weekend nor holiday. 
- weather :   
   1: Clear, Few clouds, Partly cloudy, Partly cloudy   
   2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist   
   3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds   
   4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog   
- temp : temperature in Celsius. 
- atemp : "feels like" temperature in Celsius.  
- humidity : relative humidity. 
- windspeed : wind speed.   
- casual : number of non-registered user rentals initiated.  
- registered : number of registered user rentals initiated.  
- count : number of total rentals.  

## Result and code

Please see code [here](https://github.com/ct627/Kaggle_BikeShare/blob/master/bikeshare.ipynb) for details.

