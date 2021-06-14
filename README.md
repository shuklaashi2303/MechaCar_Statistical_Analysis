# MechaCar_Statistical_Analysis


I #Background

AutoRUs is developing a new prototype vehicle, MechaCar. Jeremy, the data analytic's team leader was approached by upper management about a special project. MechaCar is suffering from production troubles that are blocking the manufacturing team’s progress. The company want Jermey to develop the analysis by using regression, t-test for insights that may help the manufacturing team.


## Linear Regression to Predict MPG

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

The result shows that following variables provided a non random amount of variance to mpg values:
1- vehicle weight
2- spoiler angle
3- AWD

Is the slope of the linear model considered to be zero? Why or why not?

All 3 variables are showing to be outside the 95% minimum significance level based on the data used for linear model. For example spoiler angle 0.3069-1 = 0.6931 or 69%. Additional values may still need to be collected or observed to increase the power of the analysis prediction. The slope of the linear model is not considered to be zero because the p-value is less than 0.05.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The total summary output shows the r-squared value is 0.71 which predicts 71% of all mpg  will be correct using linear model. In addition p-value of the linear model is 5.35e-11(F-statistics results) which is little smaller than desired significance level of 0.05.


## Summary Statistics on Suspension Coils


The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The total summary for all the 3 lots reveals mean is steady 1498.78 in all 150n. Rows. The variance is fixed to 62.29356 and standard deviation is 7.892627. the variance of the PSI sample distribution and SD are well in design specifications for all 3 lots and does not exceeds 100 pounds per square inch.


## T-Tests on Suspension Coils

The results shows that p-value for all lots is 0.60 which is outside the significance level resulting confidence interval of 93.97%. There is no reason to reject the null hypothesis as it clearly states that the suspension coils data set is statistically representative of population mean.

## Study Design: MechaCar vs Competition.

The main focus to do this challenge is to make the fuel efficient car which is going to be better competitor in the market. Data needs to be gathered for all MechaCar manufacturing designs, in addition to the current six variables from this analysis. Additional data could be external like geographic locations, age, gender and need  etc. Varying distances of short trips and long trips are also needed to determine fuel efficiency, as well as fuel efficiency over time. The dataset must include general marketplace competitor's data for comparison.

What metric or metrics are you going to test?
The data will meet the following metrics:

All data is to be numerical
Data samples will be as large as possible
Data samples need to be randomly selected
Variance of data needs to be similar

What is the null hypothesis or alternative hypothesis?

HO: There is no difference between competitor's mpg data set and MechCar's mpg dataset.

Ha: The true mean of MechaCar's mpg is greater than the mean of the competitor's mpg.

What statistical test would you use to test the hypothesis? And why?


I recommend using the t-test to compare our dataset with the competitors. The t-test has already been used for this current analysis and provided the predictions needed to take the next steps for improvement.

What data is needed to run the statistical test?


The p-value would be set at 0.05. Data that results in a prediction of a p-value smaller than 0.05 would provide predictive evidence that the null hypothesis could be rejected and state that the Ha is true. Providing evidence that the Ha is true would also predict that the MechaCar provides consistently better fuel efficiency than the competitors mpg. There is always room for error and better fuel efficiency may not happen all of the time, but at least 95% of the time.