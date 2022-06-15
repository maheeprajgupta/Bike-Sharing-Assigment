Bike Sharing Assigment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. So, the company has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Business Objective:

The objective is to build a multiple linear regression model for the prediction of demand for shared bikes with the available independent variables. The company's management wants to know:

1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands

Goals of Model-Building:

1. To understand demand dynamics of a new market, with respect to various features.
2. To manipulate the business strategy to meet the demand levels and meet the customer's expectations.



## Conclusions
We can see that the equation of our best fitted line is:

###### bike_rental_count = 0.1264 + 0.2328 x year - 0.0992 x holiday + 0.5480 x temperature - 0.1533 x windspeed + 0.0868 x Summer_season + 0.1306 x Winter_season - 0.0797 x Mist_&_Cloudy_weather - 0.2838 x Light_Snow_&_Rainy_weather + 0.1011 x September



- All the features with positive coefficients i.e. 'year', 'temperature', 'Summer_season', 'Winter_season' and 'September', indicate that an increase in their values will lead to an increase in the demand of bike-rentals.

- All the features with negative coefficients i.e. 'holiday', 'windspeed', 'Mist_&_Cloudy_weather' and 'Light_Snow_&_Rainy_weather', indicate that an increase in their values will lead to an decrease in the demand of bike-rentals.

- The most significant factor with the largest coefficient is 'temperature' followed by 'Light_Snow_&_Rainy_weather'.

- The bike-rentals increase in the month of 'September' and reduce during 'holidays'.

- On the whole, this indicates that the demannd for bike rentals is majorly affected by temperature, season, month and weather.



## Technologies Used
- Numpy
- Pandas
- Calendar
- Matplotlib
- Stats Models
- Scikit Learn




## Contact
Created by [@maheeprajgupta] - feel free to contact me!
