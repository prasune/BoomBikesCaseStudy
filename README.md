# BoomBikes - Linear Regression Model to predict demand
> BoomBikes is a bike rental company. They want to predict the demand for bike rentals post covid-19 based on the historical data.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


### Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### Final result comparison of R square of training and test data
Training Data R-squared: 0.834 <br>
Testing Data R-squared: 0.814

#### This is a good model for predicting bike rental demands of Boomikes
Percentage deviation of R2 from training data to test data is 2.4% ((0.834-0.814)/0.834) which is less than 5% <br>
Percentage deviation of adjusted R2 from training data to test data is 3.3% ((0.830-0.803)/0.830) which is less than 5% <br>
Equation: cnt = 0.2360 * yr - 0.0893 * holiday + 0.3593 * temp - 0.1520 * windspeed - 0.1070 * spring + 0.0670 * winter - 0.2975 * Light_Snow - 0.0789 * Mist_Cloudy - 0.0560 * Dec - 0.0623 * Jan - 0.0531 * Nov + 0.0640 * Sep

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- seaborn
- matplotlib
- statsmodels
- sci-kit learn


## Contact
Created by [@prasune] - feel free to contact me!


