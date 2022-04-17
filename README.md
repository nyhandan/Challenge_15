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

The true mean of the whole sample is 1498.78, with a p-Value of 0.06. Considering a p-Value of 0.06 is larger than the confidence level of .05, we cannot  reject the claim that the population's true mean is 1500.


![individual t-tests](https://github.com/nyhandan/Challenge_15/blob/main/Challenge_15/3%20t-tests.png)


- Lot 1's true sample mean is 1500, again as we saw in the summary statistics above. With a p-Value of 1, clearly we cannot reject    (i.e. accept) the null hypothesis that there is no statistical difference between the observed sample mean and the presumed population mean (1500).
- Lot 2 has essentially the same outcome with a sample mean of 1500.02, a p-Value of 0.61; the null hypothesis cannot be rejected, and the sample mean and the population mean of 1500 are statistically similar.
- Lot 3 is a different scenario. Here the sample mean is 1496.14 and the p-Value is 0.04, which is lower than the common significance level of 0.05. All indicating to reject the null hypothesis that this sample mean and the presumed population mean are not statistically different.
