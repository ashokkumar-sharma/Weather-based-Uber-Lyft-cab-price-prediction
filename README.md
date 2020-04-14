# Weather-based-Uber-Lyft-cab-price-prediction

## Problem Description: 
Uber and Lyft's ride prices are not constant like public transport. They are greatly affected by the demand and supply of rides at a given time So what exactly drives this demand?
Our objective is to fix the current price prediction system with a predictive model that can estimate the price of a ride including a more widespread range of measures. We aim to better understand the combined effect of day, time, type of ride and weather conditions on the price of the ride.

## Data Description:
The dataset is the part of a Kaggle competition, sourced https://lnkd.in/d9W_7_c. The raw data consisted of information about cab rides for every 5 minutes and weather data for every hour from a few locations in Boston for a few weeks from November December 2018.

## Data Preprocessing:
The data were merged based on location and time and the resulting dataset comprised 6 90 107 instances 21 features.
Day of the week and hour were extracted from the raw data Null values in rain were replaced by 0 inches.  The instances for cab type Taxi were discarded since the target variable “price” for such cab types was not available.

## Modeling:
In this project, we had the opportunity to leverage big data tools like Python, PySpark, Hadoop. To solve this regression problem we used several machine learning algorithms like Elastic-Net Regularised regression, Random Forest and Gradient Boosting. For better performance of these algorithms and to achieve desired outputs we deployed some feature engineering and hyperparameter optimization techniques.

## Inference & Conclusion: 
The impact of features like the day of the week, hour and weather on price are negligible because other features like distance, surge multiplier and cab type dominate the ride price, assuming these features are handled under surge multiplier.
This methodology can be used by any ridesharing or transportation company to determine their own prices considering various factors and pricing strategies.
