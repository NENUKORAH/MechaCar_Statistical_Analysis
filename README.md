# MechaCar_Statistical_Analysis

The purpose of this project is to perform an analysis to help the Upper management of AutosRUs in understanding the 
production troubles that are blocking the manufacturing team's progress in their newest prototype "The MechaCar". 

I will be performing the following analysis to help the team;

* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.

* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots.

* Run t-tests to determine if the manufacturing lots are statistically different from the mean population.

* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. 

## Resources

**Data Sources:** MechaCar_mpg.csv, Suspension_coil.csv

**Code Files:** MechaCarChallenge.RScript

**Software:** R Studio 1.4.1106, R 3.6.

## Linear Regression to Predict MPG

In this section, i will use multiple linear regression to predict the Miles Per Galoon (MPG) by using the vehicle length, vehicle weight, spoiler angle, ground clearance, and all wheel drive (AWD) independent variables.

![Linear Regression to Predict MPG](https://user-images.githubusercontent.com/81701640/127416002-249f97cf-7750-4a5e-8b0b-e63c5976fef9.png)

From the above analysis, we can deduce the following;

* The ground clearance and vehicle length coefficients can be described to have a non-random amount of variance to the mpg values. This is due to extremely small p-value meaning that they had a high level of significance.

* The slope of the linear model is not considered to be zero. This is because the multiple linear regression shows that some of the independent variables had a significant effect on the dependent variable

* The linear model predicts the mpg of MechaCar prototypes effectively. This is because the R-squared value is set at 0.7149, implying a 71% effectiveness. 

## Summary Statistics on Suspension Coils

In this section, I will be reviewing the suspension coils data of the company and presenting summary statistics on suspension coils;

![Summary Statistics on Suspension Coils - One](https://user-images.githubusercontent.com/81701640/127416031-4c590e08-8602-41e6-916a-94a4a1a8de17.png)

From the above, we can deduce that the the current manufacturing data meet the design specification for all manufacturing lots in total. 

This is because the current variance is approximately 76.23 per square inch which does not exceed 100 pounds per square inch limit.

![Summary Statistics on Suspension Coils - Two](https://user-images.githubusercontent.com/81701640/127416048-383dca18-f0e4-443b-9d25-c087dc26308f.png)

From the above summary statistics, we can deduce the following;

* Lot One meets the design specification at a variance of 1.15.

* Lot Two meets the design specification at a variance of 10.13.

* Lot Three does not meet the design specification at a variance of 220.01.

## T-Tests on Suspension Coils

![T-Tests on Suspension Coils -Main](https://user-images.githubusercontent.com/81701640/127416120-67830c65-9ec9-4a9b-aa19-9dd49e4e1870.png)

From the above analysis, Taking into consideration the p-value, we will fail to reject the null hypothesis. There is no statistical difference  from the population mean of 1,500 pounds per square inch. 

![T-Tests on Suspension Coils -Lot1](https://user-images.githubusercontent.com/81701640/127416135-cb18bcc6-5af9-4b85-a5dd-3ceaf187ff2c.png)

From the above analysis, Taking into consideration the p-value, we will fail to reject the null hypothesis. There is no statistical difference  from the population mean of 1,500 pounds per square inch.

![T-Tests on Suspension Coils -Lot2](https://user-images.githubusercontent.com/81701640/127416149-b3bd3dd6-486e-4323-9c58-9e15bf0dae73.png)

From the above analysis, Taking into consideration the p-value, we will fail to reject the null hypothesis. There is no statistical difference  from the population mean of 1,500 pounds per square inch.

![T-Tests on Suspension Coils -Lot3](https://user-images.githubusercontent.com/81701640/127416177-61e26718-c2e6-49bd-bf4d-122b6d683756.png)

From the above analysis, Taking into consideration the p-value, we will fail to reject the null hypothesis. There is no statistical difference  from the population mean of 1,500 pounds per square inch.

## Study Design: MechaCar vs Competition

A new study can be developed to compare performance of the MechaCar vehicles against performance of vehicles from other manufacturers.

Firstly, we can use a wide range of metrics to perform this analysis namely Current price, Resale value, MPG, Annual cost and fuel efficiency etc.

For the purpose of this study, i will use the city and highway fuel efficiency metrics.

The Null hypothesis for this study will be: Cars in the same class have same fuel efficiency.

The Alternative hypothesis for this study will be: Cars in the same class does not have same fuel efficiency.

I will use a multiple linear regression for the purpose of this study.

The data for this analysis will be information on all identified metrics over the past five years accross all the manufacturers.

**Nnaemeka Enukorah**

**29th July, 2021**

