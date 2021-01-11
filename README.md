# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
The vehicle length and ground clearance are statistically not a random amount to the mpg values in the dataset. There is a significant linear relationship because the R-squared value is greater than 0.5.  In addition the p-value of our linear regression analysis is 5.35 x 10-11, which is much smaller than our assumed significance level of 0.05%. Therefore the slope of our linear model is not zero, which means there is significant linear relationship. The mutliple R-squared value is 0.7149, which means that roughly 71% of the MPG predictions of MechaCar prototypes will be effective when using the model.
![Linearregresssion](/Linearregression.PNG)


 ## Summary Statistics on Suspension Coils
 The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The variance of all of the Suspesion coils does not meet the design specification because it does not exceed 100 pounds. Only Lot3 meets the design specification because the variance is 170.2, while the other two lots have variances much less than 100 pounds. 
 
 ![summarizesuspension](/summarizesuspension.PNG)
 ![lotsummary](/lotsummary.PNG)

## T-Tests on Suspension Coils
Assuming our significance level was the common 0.05 percent, our p-value is above our significance level. The PSI across all manufacturing lots is statistically similar to the population mean of 1,500 pounds per square inch.
![Ttest](/Ttest.PNG)

## Study Design: MechaCar vs Competition
A statistical study is that the more expensive a car is the better the MechaCar performs against the competition. The null hypothesis is that there is no significant difference between the performance of the car based on price. The statistical test I would use is the multiple linear regression. This model would help predict the price of the car based on the speed and MPG. The data needed for this model would be the car model, the speed of the car, the MPG of the car and the price. 
