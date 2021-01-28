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

![](Images//lot_summary.jpg)

![](Images//total_summary.jpg)
