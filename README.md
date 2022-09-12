# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![Linear Regression to Predict MPG]()

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Vehicle length and ground clearance provided a non-random amount of variance to the mpg values in the dataset. (highlighted in above image)
- Is the slope of the linear model considered to be zero? Why or why not?
No, the slope of the linear model is not considered to be zero because the p-value is 5.35e-11.
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The linear model does not predict mpg of MechaCar prototypes effectively because the Multiple R-Squared number is 0.7149 meaning that it is 71% accurate. 

## Summary Statistics on Suspension Coils

![total_summary]()

![lot_summary]()

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
The current manufacturing data meets the design specification for manufacturing lots in total but does not meet the individual standard in Lot3 as the variance is over 100 (170.286). 

## T-Tests on Suspension Coils
![sample_test]()

All manufacturing lots show that there is not a statical difference from the population mean as the p-value is 0.06028. This hypothesis cannot be rejected. 

![Lot1_test]()

Lot1 shows that there is not a statical difference from the population mean as the p-value is 1. This hypothesis cannot be rejected. 

![Lot2_test]()

Lot2 shows that there is not a statical difference from the population mean as the p-value is 1. This hypothesis cannot be rejected. 

![Lot3_test]()

Lot3 shows that there is  a statical difference from the population mean as the p-value is 0.04168. This hypothesis can be rejected. 

## Study Design: MechaCar vs Competition

- What metric or metrics are you going to test?

Manufacturer's Suggested Retail Price(MSRP), Fuel Efficiency, Safety rating. 

- What is the null hypothesis or alternative hypothesis?

The MSRP is not statistically different compare to the competition. 

- What statistical test would you use to test the hypothesis? And why?

Two-Sample t-Test because there more than likely is a statistical difference between the distribution means from two samples. 

- What data is needed to run the statistical test? 

MSRP, Fuel Efficiency data, safety rating data is all needed to run the statistical test. 
