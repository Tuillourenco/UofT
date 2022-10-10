# MechaCar Statistical Analysis Project.

## Project Description.
The upper management addressed the project team on a particular project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles blocking the manufacturing team’s progress. Indeed, AutosRUs’ upper management has called the data analytics team to review the production data for insights that may help the manufacturing team.

## Project Scope:
- Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.
- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots.
- Run t-tests to determine if the manufacturing lots are statistically different from the mean population.
- Design a statistical study to compare the vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, reporting a summary interpretation of the findings.

## Project Deliverables
This new project consists of three technical analysis deliverables and a proposal for further statistical study. The team was assigned to accomplish the following outcomes:
- Deliverable 1: Linear Regression to Predict MPG.
- Deliverable 2: Summary Statistics on Suspension Coils.
- Deliverable 3: T-Test on Suspension Coils.
- Deliverable 4: Design a Study Comparing the MechaCar to the Competition.

### Linear Regression to Predict MPG
For this deliverable, it is necessary to fulfill some parameters to respond to the three questions below and help the understand the method of evaluation; as shown in the attached picture:

![](MechaCar_Statistical_Analysis/images/deliverable_01.png)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- In this question, the best approach to respond is in the results,  three variables that behave with a non-random amount of variance: the intercept, the vehicle length and ground clearance; they demonstrate that there has been a smaller p-value; being direct, it is statistically significant. Opposite, the rest of the variables are not statistically significant; if there were the possibility of getting more data, the model would change or skip these variables to help its efficiency.

Is the slope of the linear model considered to be zero? Why or why not?
- The results of the p-value of our linear regression analysis are 5.35e-11, which is smaller than the significance level of 0.05%. Albeit, it is possible to conclude that the evidence to reject the null hypothesis has been found in the procedure, which means that our linear model's slope is not zero.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- When executing a multiple linear regression model, the r-squared value results in 0.7149, meaning that 71% of the variability (miles per gallon - mpg) is directly related to using it. Although the analysis is suitable for predicting the given dataset, the lack of significant variables is evidence of overfitting. The model performs well with a current dataset but fails to generalize and predict future data correctly.

### Summary Statistics on Suspension Coils.
