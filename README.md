# MechaCar_Statistical_Analysis

### Overview
- Linear Regression to Predict MPG
- Summary Statistics on Suspension Coils
- T-Test on Suspension Coils
- Design a Study Comparing the MechaCar to the Competition

## Linear Regression to Predict MPG 

Design a linear model that predicts the mpg of MechaCar prototypes using several variables 

- The vehicle length and the ground_clearance provided a non-random amount of variance. 

- The slope of the linear model is not considered to be zero because some of the independent variables had a significant effect on the dependent variable. 

- The effectiveness rate is approximately 71%, this is considered effective.

### Miles Per Gallon (mpg) linear regression:

![MPG Linear Regression](https://github.com/Williamj83/MechaCar_Statistical_Analysis/blob/main/linear_regression_mpg.png)

## Suspension Coils
- The suspension coil’s PSI continuous variable across all manufacturing lots
- The following PSI metrics for each lot: mean, median, variance, and standard deviation.
- The suspension coil variance is limited to 100 pounds per square inch.
  
  ![Total Summary](https://github.com/Williamj83/MechaCar_Statistical_Analysis/blob/main/total_summary.png)
 
  
  ![Lot Summary](https://github.com/Williamj83/MechaCar_Statistical_Analysis/blob/main/lot_summary.png)
  
  
### Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
The current variance is approximately 76.23 PSI, this meets the design specs. 
Lots 1 and 2 meet the design specification. Lot 1 at a varaince of approximately 1.14 PSI and Lot 2 at a variance of approximately 10.13 PSI.
Lot 3 does not because the variance is approximately 220.01 PSI and that greatly exceeds the design specification. 
 

## T-Test on Suspension Coils

- Perform t-tests to determine if all manufacturing lots and each lot individually are statistically different 
  from the population mean of 1,500 pounds per square inch. 

### Statistical difference in mean from the population of 1,500 PSI?

![T-tests Suspension Coils](https://github.com/Williamj83/MechaCar_Statistical_Analysis/blob/main/T_tests.png)


