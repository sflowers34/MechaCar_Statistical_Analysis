# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

An analysis of the relationship between the miles per gallon vs vehicle length, vehicle weight, spoiler angle, ground clearance, and AWD was completed. 

The lm() function was used to perform a linear regression against all six variables. 

![](Images//lm.jpg)

The summary function was used to determine the p-value and r-squared value for the linear regression model.

p-value:5.35

r-squared:0.7149

![](Images//summary.jpg)


### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Based on the results of the liner regression the vehicle length and ground clearance variables provided a non-random amount of variance.

### Is the slope of the linear model considered to be zero? Why or why not?
The slope is not considered to be zero. The p-value is 5.35, which is lower than the significance level 0.05.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not? 
Based on the R-squared value of 0.71 we can confidently state that the model effectively predicts the mpg of MechaCar prototypes. 

## Summary Statistics on Suspension Coils

Does the current manufacturing data meet the design specificiation for the MechaCar suspension coils which dictate that the variance of the suspension coils must not exceed 100 PSI in the total?

The total summary table of the Suspension Coils is displayed below. Based are the results of Variance of 62.29356 in total summary table, we can conclude that the current manufacturuing data meets the design specifications for suspension coils. 


![](Images//total_summary.jpg)

Does the current manufacturing data meet the design specificiation for the MechaCar suspension coils which dictate that the variance of the suspension coils must not exceed 100 PSI in the lot summary?

The lot summary table of the Suspension Coils is displayed below. Based are the results of the Variance in the lot summary table, we can conclude that the current manufacturuing data does not meet the design specifications for suspension coils in Lot3 (Variance 170.2861), however the data does meet the design specifications for suspension coils in Lot1 (Variance 0.9759)  and Lot2 (Variance 7.4694). 

![](Images//lot_summary.jpg)

## T-Tests on Suspension Coils
