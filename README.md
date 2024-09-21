# Project Name
> Bike Sharing Case Study Assignment.

## General Information
- Objective of the project is to develop a linear regression model to predict the demand of shared bikes based on the various variables provided. 


## Conclusions
Below are the variables, which have the highest or lowest coefficients: 
• atemp (coefficient 0.6376) – temperature of the day in Celsius (on colder days below 8 Celsius the bike counts are low and with rising temp, the bike counts rises) 
• yr (coefficient 0.2413) – year, which is 1 for 2019 and 0 for 2018 (since bike counts in year 1 is higher) 
• weathersit_3Light_Rain (coefficient -0.2163) – Derived dummy variable, which reflected the day with “Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds” or a value of 3 for “weathersit”. This is negative, as on such days, the bike counts is low.

Overall, the model is having: R2 of 80% on Test data and R2 of 84% on Train data (it is able to capture > 80% of variance).
