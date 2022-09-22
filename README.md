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

