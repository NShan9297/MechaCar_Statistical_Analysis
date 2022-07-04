# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
•	Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset
As per this table, the coefficients that provide a non-random amount of variance are intercept, vehicle length, and ground clearance the Pr(>|t|) value for each of these are less than 0.05, our assumed significance level.
•	Is the slope of the linear model considered to be zero? Why or why not?
The multiple r-squared value being 0.7149 suggests that more than 71% of the variability is not random and can be explained by using a linear model. The p-value is also lower than our assumed significance level of 0.05. these point to us being able to assume that we could reject the hypothesis thus the slope of linear model is not zero
•	Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
As per the table, only half of the variables are significant which seems to point to overfittingthis overfitting means that this model will not be effective in predicting future data even though it works well for this dataset. 

## Summary Statistics on Suspension Coils
•	The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
No, as per the lot_summary table, Lot3 has a variance of 170.29 pounds per square inch. Based on the design specifications, these cars will not meet the requirements. Lots 1 and 2, however, are much more similar to the design requirements
**pic of lot summary table**

## T-Tests on Suspension Coils
briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.
The t-test results show that Lot3 is an outlier that is really impacting the overall numbers, the p-value is greater than 0.05 and the average is less than the desired 1500 PSI

**Image of whole t-test**

When you take out Lot3, the numbers begin to look more like the design specifications
Lots 1 and 2 are more similar and have more similar p-values, that don’t point to us rejecting the null hypothesis:
**image of 1**
**image of 2**
