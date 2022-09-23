# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![MechaCarDev1 2](https://user-images.githubusercontent.com/107225715/191778346-3c2a453f-4b4e-4995-8a24-63eaa6de1ad9.png)

* Looking at the screenshot above, we can see that vehicle_length and ground_clearance likely provided a non-random amount of variance to the mpg values in the dataset.

* The p-Value, which is 5.35e-11, is much smaller than the significance level of 0.05 which means that the results are highly significant. This indicates that the slope of the linear model is not considered zero as ths statisticla results provides evidence that the null hypothesis should be rejected.

* The linear model has a R-squared value of 0.7149, which means that there is 71.15% chance that future mpg predictions will be determined by this model. Hence, the linear model does predict the mpg of MechaCar prototypes effectively.

## Summary Statistics on Suspension Coils

Total Summary Statistics

![MechaCar2 1](https://user-images.githubusercontent.com/107225715/191841488-dab33157-f1b0-468f-895a-853cb8f0397a.png)

Lot Summary Statistics

![mechacar2 2](https://user-images.githubusercontent.com/107225715/191841688-601ed6a8-ca1d-4636-8eb5-f46144a64027.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Looking at the Total Summary Statistics table, the variance is 62.29 PSI for the entire population of production lot, which is within the 100 pounds PSI. Lot 1 and Lot 2 has 0.98 and 7.47 PSI respectively, which also falls within the requires 100 pounds PSI. However, Lot 3 has 170.29 PSI which way over the 100 pounds PSI limit.

## T-Tests on Suspension Coils

t-Test for All Manufacturing Lots

![MechaCarDev3 1](https://user-images.githubusercontent.com/107225715/191973039-4172af55-c4e9-431a-9b06-65e56f47cacb.png)

The p-value for all manufacturing lots is 0.06 which is higher than the basic significance level of 0.05. This means that there is not enough evidence to reject the null hypothesis. The mean of all three manufacturing lots is statistically similar to the polulation mean of 1,500 pounds PSI.

t-Test for Individual Lots

![MechaCarDev3 2](https://user-images.githubusercontent.com/107225715/192026422-78c2d0c9-2651-4cee-9e03-98f113c45a04.png)

* With a p-value of 1, for Lot 1, there is not enough evidence to reject the null hypothesis that the mean PSI of Lot 1 is not statistically different from the population mean of 1500 pounds PSI.

* Lot 2 has a p-value of 0.61, which means that there is not enough evidence to reject the null hypothesis and the sample mean and the population mean of 1500 pounds PSI are statistically similar.

* Lot 3 has a p-value of 0.04, which means that there is enough evidence to reject the null hypothesis, therefore, the mean PSI of Lot 3 is statistically different from the population mean of 1500 pounds PSI.

## Study Design: MechaCar vs Competition

Safety Rating, which is considered one of the most important factores when looking for a car, would be a useful statistical study. We would perform the statistical study to compare safety ratings of MechaCar vehicles and safety ratings of vehicles from other manufacturers.

Null Hypothesis: Mechacar vehicles have do not have statistically significantly higher safety ratings compared to vehicles from other manufacturers.
Alternative Hypothesis: MechaCar vehicles do have statistically significantaly higher safety ratings compared to vehicles from other manufacturers.

I would use a one-tailed t-test as it would result in statistic information any differences between the groups being compares. 

The data needed would be safety ratings of MechaCar vehicles and safety ratings of other manufacturers' vehicles safety ratings. 
