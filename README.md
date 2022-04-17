# Statistical Analysis

## Linear Regression to Predict MPG
  - The vehicle_length and ground_clearance have p-vaules under .05, indicating that they most likely provide a non-random amount of variance to the mpg values in the dataset.
  - The p-Value for this model is much smaller than thesignificance level of 0.05%. This means there is sufficient evidence to reject our null hypothesis, so the linear model will not be zero.
  - The r-squared value is around 0.7149, so there is moderate-to-strong correlation between the input and output variables. So, this linear model most likely predicts mpg of MechaCar prototypes effectively.

## Summary Statistics on Suspension Coils
This design specification of variance within 100 pounds per square inch is not met in all the manufacturing lots. Lot 1 has a variance of 0.9795918, Lot 2 has a variance of 7.4693878, and Lot 3 has a variance of 170.2861224. So, Lots 1 & 2 meet the requirement, but Lot 3 does not. For all the lots, the requirement is not met, but it is for the first 2. 

## T-Tests on Suspension Coils
Here's the results of the t-tests:
![entire t-test](https://github.com/nyhandan/Challenge_15/blob/main/Challenge_15/Total%20T-test.png)

The mean of the whole sample is 1498.78, with a p-Value of 0.06. Considering a p-Value of 0.06 is larger than the confidence level of .05, we cannot  reject the claim that the population's true mean is 1500. In fact, 95% of the sample means tested for this population will be between 1497.507 and 1500.053, so there's a chance that the true mean is exactly 1500.


![individual t-tests](https://github.com/nyhandan/Challenge_15/blob/main/Challenge_15/3%20t-tests.png)


- Lot 1's sample mean is 1500. The p-value of 1 indicates that this sample gives an abosolute certainty that the mean will be 1500, given each test contains the same data. 

- Lot 2 has a sample mean of 1500.2. It has a p-Value of 0.6072, so the null hypothesis cannot be rejected. There's a significant chance the true population mean will be within the confidence interval: 1499.423 and 1500.977.

- Lot 3 has a sample mean of 1496.14, and the p-Value is 0.04168, which is smaller than our confidence level of 0.05. Lot 3 data rejects the null hypothesis. This sample indicates the population mean will be between 1492.431 and 1499.849. 



