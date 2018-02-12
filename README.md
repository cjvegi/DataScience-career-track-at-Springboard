# Porto Seguro’s Safe Driver Prediction:

## Objective: 
Predict if a driver will file an insurance claim next year

## Bussiness Aspect: 
Help provide accurate tailored insurance plans and hopefully make auto insurance coverage more accessible to more drivers.

## Project Description: 
Porto Seguro, one of Brazil’s largest auto and homeowner insurance companies, completely agrees. Inaccuracies in car insurance company’s claim predictions raise the cost of insurance for good drivers and reduce the price for bad ones.
In this competition, you’re challenged to build a model that predicts the probability that a driver will initiate an auto insurance claim in the next year. While Porto Seguro has used machine learning for the past 20 years, they’re looking to Kaggle’s machine learning community to explore new, more powerful methods.

## Data
Source: [Kaggle: Porto Seguro Driver's Prediction Challenge](https://www.google.com)
In data, features that belong to similar groupings are tagged as such in the feature names (e.g., ind, reg, car, calc). In addition, feature names include the postfix bin to indicate binary features and cat to indicate categorical features. Features without these designations are either continuous or ordinal. Values of -1 indicate that the feature was missing from the observation.

## Pipeline

1. Exploratory Data Analysis:

_Label/Target Distribution:

   ![alt text](https://github.com/cjvegi/DataScience-career-track-at-Springboard/blob/master/Capstone%20project%201/images/labels_distribution.png)
This shows that the data is imbalanced.

_Correlation plot

![alt text](https://github.com/cjvegi/DataScience-career-track-at-Springboard/blob/master/Capstone%20project%201/images/correlation_plot.png)
This shows that the columns with 'cal' suffix are not correlated to any columns in the data sets. We can use this information to keep useful columns when predicting our labels.

_Imputing Missing values: filling with Median, Mean and using outlier detection methods

2. Machine Learning:

Trained different machine learning models and ensembeled them


Project Reference:https://www.kaggle.com/c/porto-seguro-safe-driver-prediction
