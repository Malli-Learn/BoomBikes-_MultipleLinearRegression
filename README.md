# BoomBikes_MultipleLinearRegression
Multiple LinearRegression on Boom Bikes, Creating a Linear regression model and apply for test set and find Residual analysis 

### Problem Statement

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider <b>BoomBikes</b> aspires to understand the demand for shared bikes among the people
The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Table of Contents
* Reading and Understanding the Data
* Visualising the Data
* Data Preparation
* Splitting the Data into Training and Testing Sets
* Building a linear model
* Residual Analysis of the train data
* Conclusion




## Conclusions
- Seems that Fall seasion has best bookings, then summer and winter follows and spring is the least
- Compared to 2018 all season bookings are higher in 2019
- Most sales are happenign in June, July, Aug and Sep months
- 2019 has more increase in every month
- Seems, `temp` seems to the correlated to `Cnt` the most
- # Fitting Equation is
$  Cnt = 0.2327 + (0.2327 * year) + (0.0558 * workingday) + (0.3903 * temp)- (0.1474 * windspeed) - (0.0500* jan) + (0.0665*sep)+(0.0665 * sat) - (0.2941 * Light Rain)- (0.0792*Misty)-(0.1053*spring)+(0.0440 * winter) $
- Train dataset R^2          : 0.835
- Test dataset R^2           : 0.831
- Train dataset Adjusted R^2 : 0.829    
- Test dataset Adjusted R^2  : 0.772




## Technologies Used
* Python 3,o
* Pandas
* numpy
* matplotlib
* seaborn
*  statsmodels
- library - version 2.


## Contact
Created by @Malli-Learn - feel free to contact me!
