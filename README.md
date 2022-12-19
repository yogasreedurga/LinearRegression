# BIKE SHARING SYSTEM - DEMAND PREDICTION OF BIKES
The main objective of this programming assignment is to build a multiple linear regression model for the prediction of demand for shared bikes for a US bike-sharing provider BoomBikes.

## Table of Contents
* [General Info](#general-information)
* [Techniques Used](#Techniques-used)
* [Tools/libraries used](#Tools/libraries used)
* [Conclusions](#conclusions)


## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.This assignment is a programming assignment wherein we have to build a multiple linear regression model for the prediction of demand for shared bikes for a US bike-sharing provider BoomBikes.

Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

-  Which variables are significant in predicting the demand for shared bikes.
-  How well those variables describe the bike demands

## Techniques Used
-  Reading and understanding the data
-  Data cleaning - converting datatypes, dropping redundant columns,creating dummy variables,etc.,
-  Data Visualization - Visualizing numerical and categorical data
-  Preparing the data for modelling - Train-test split,Rescaling the variables
-  Training the model - Model building using manual and automated methods
-  Preparing the test data - Defining X and y, Rescaling the dataset
-  Residual Anaysis - Calculating error terms, assuming error terms are normally distributed
-  Predictions on the test set - Predicting test to understand the spread of data
-  Evaluations of the model - Calculating R-squared, adjusted R-squared values

## Tools/libraries used
-  numpy
-  sklearn
-  statsmodel
-  seaborn
-  pandas

## Conclusions
-  The variable ‘temp’ has a coefficient of ‘0.5854' representing unit increase in target variable,increases the shared bikes numbers by 0.5854 units
-  The variable ‘yr’ has a coefficient of ‘0.2329’ representing unit increase in target variable, increases the shared bikes numbers by 0.2329 units
-  The variable ‘weathersit_Snowy/Rainy’ has a coefficient of ‘0.2524’ representing unit increase in target variable, decreases the shared bikes numbers by 0.2524 units
-  The variable ‘holiday’ has a coefficient of ‘0.0875’ representing unit increase in target variable, decreases the shared bikes numbers by 0.0875 units

## Contact
Created by [@yogasreedurga] - feel free to contact me!
