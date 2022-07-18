# MechaCar_Statistical_Analysis

Purpose
	The purpose of this project was to import data from a csv and write script in order to retrieve and create data from it. Once we created tables from the csv we can then look further into the data and use a linear equation to see the trend of the miles per gallon of a vehicle with respect to the vehicles dimensions such as vehicle length. Next, our goal was to import suspension coil data from a csv and use the summary function in order to get the mean, median, and variance of all the coils. From there we had to then find the the p-value for each Lot number and determine if the lots were different than the mean.

## Linear Regression to Predict MPG
1)In terms of providing non-random amount of variance to the mpg values in the data set, the vehicle dimensions would be the non-random variables. For each calculation, the slope was determined by the set variables given to use by the data.
2)No, the slope of the linear model is not considered zero, while the slope is a small incline, the amount is still considerable in terms of creating a difference.
3)The R-Squared value for the data set was around 71%. While a higher R-Squared value means that the data is more closely related to the trend line, a 71% means that there is in fact a strong relationship between the data and the trend line. However, because 71% is still considered low, the data can be a considered a little unreliable at times.

## Summary Statistics on Suspension Coils
1)From our results, we can conclude that the manifesting data does meet the design specifications for all of the lots except lot 3. This is due to the fact that for the first two lots, the variance was less than 10. This means that for majority of lot 1, the PSI falls closer to the mean, with majority of the PSIs were around 1500. While the variance for lot 2 was higher, it was still low enough to where we could conclude that a majority of the PSIs were close to the mean. Lot 3, had one of the highest variances, equal to 170. This variance value tells us that the data points for Lot 3 were far away from the mean by a large amount. 

## T-Tests on Suspension Coils
1) From out T-test results, we can conclude for the first two lots, that we do not have enough evidence to reject the hypothesis of the suspension coils being more than 100 psi. However for the 3rd Lot, we had a p-value that was more significant, which we can then reject the idea of our data for Lot 3 being close to the mean.

## Study Design: MechaCar vs Competition
From our data sets that we created, we can conclude that vehicle dimension and mpg are inversely related. From the first part of the project, we found that mpg was much higher for smaller vehicles then it was for larger ones. Further more, we found that lot 1 suspension coils were much safer to use on the vehicles compared to lot 2 and lot If someone was wanting to design a safe and efficient car, building a smaller car with lot 2 coils would be the safest and cheapest car to be made. However, if you created a much larger car, you would have to use lot 1 coils in order to have a higher chance of safety for the car.
1)The metrics we are going to test will be vehicle length, mpg, and vehicle weight. These three variables will play the biggest impact on the outcome of a car and what suspension coils to use.
2)The null hypothesis is that a car with higher mpg is able to use all coils. The alternative hypothesis is that higher mpg cars variables don’t play a role in which coils to use.
3)In order to test a hypothesis, we would use a p-value in order to find if we can accept or reject a hypothesis. A p-value that is less than .05 means that the data does not support the rejection of the hypothesis. 
4)The data that is need to run the test is the mean of the data and the variance of the data set.
