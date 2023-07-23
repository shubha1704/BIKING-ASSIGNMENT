# BIKING-ASSIGNMENT
# Shared Bike Demand Analysis by Shubhashree P

To predict the demand of bikes based on which the organization can forecast the demands and accordingly take the necessary measures to to satisfy the customers.

# Table of Contents
-General Infoformation
-Technologies Used
-Observations and Conclusions
# 1. General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.A US bike sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

a) Which variables are significant in predicting the demand for shared bikes. b) How well those variables describe the bike demands

# 2. Technologies Used
Using Python programming in Jupyter notebook following steps has been adopted

library - pandas
library -numpy
library - sklearn
Using Python programming in Jupyter notebook following steps has been adopted

•Data preproceesing •Data cleaning •By building linear Regression model by considering all features ,we try to estimate mean square error-( one and above) •R2 values are reduced from each iteration ( by observing high VIF and low P value) •Linearity, mean of residual Analysis etc. •Validated by Scatter plot – Actual v/s Predicted

# 3. Observations and Conclusions
From the Vizualition of dataset the following observations has been made Season Fall is having more demand for shared bikes Spring season is having less demand for shared bikes There is more demand on for the shared shared bikes on holiday when compared to 2018, demand has increased in 2019 There is no demand for shared bikes during heavy rain and more demand when the weather is clear

From the pair plot analysis following observations has been made

temp and atemp are highly correlated. they have positive correlation with demand(cnt) registered is highly correlated with deman(cnt)

From the categorical data analysis using box plot following observations has been made

it is observed that most of the week days are having median value in the similar range there is more demand in 2019 when compared to 2018

Based the VIF and P value mutiple iterations has been carried out and finally acual vs prediction plot was computed for training and test data


# Contact

Shubhashree P
