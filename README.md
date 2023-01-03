# MechaCar_Statistical_Analysis

# Overview

## Linear Regression to Predict MPG
Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
-the variables that provided a non-random amount is the AWD column with an estimate of -3.411
Is the slope of the linear model considered to be zero? Why or why not?
- The slope is considered to be zero due to rounding.
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- It does predict the prototypes effectively.
- ![2023-01-02](https://user-images.githubusercontent.com/111711885/210304691-dc48001f-cc7e-49fd-8670-af3c771a27f7.png)
## Summary Statistics of Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
- The current manufacturing data does meet this criterira for all lots total. The variance total was 62.29. Separately though, lot 3 did not meet the criteria due to the variance number being 170.28
![2023-01-02 (2)](https://user-images.githubusercontent.com/111711885/210305113-b9238b49-efa2-4ff8-80aa-65ada3c5a3aa.png)
![2023-01-02 (1)](https://user-images.githubusercontent.com/111711885/210305115-94b5ab97-caf9-40d5-a8db-49e3ff95d582.png)
## T-Tests on Suspension Coils
- The alternative is hypothesis is true due to the mean being less than 1500; it was calculated to be 1497.507.
![2023-01-02 (3)](https://user-images.githubusercontent.com/111711885/210305587-0897df98-8f5c-4b89-8791-4412b8de92c8.png)
## Study Design: MechaCar vs. Competition
This study design is to see how the MechaCar would perform against their competition. The metrics I would test for this would be cost, maintenance cost, and safety rating.My null hypothesis would be that consumers would buy a car based on looks rather than performance. My alternative hypothesis is that consumers would do thorough research considering those metrics when buying a car. I would do an Lm() function and a t-test to determine my statistics. The data that is needed for this would be based on the amount of consumers who base their purchases off of research, and the costs of vehicles, maintenance and safety ratings.
