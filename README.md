# MechaCar_Statistical_Analysis

# Overview

Jeremy just started his new role he is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress.  AutosRU’s upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

In this challenge, we will help Jeremy and the data analytics team do the following:

-	Perform multiple linear regression analysis to identify wich variables in the dataset predict the mpg of MechaCar prototypes.
	
-	Collect summary statistics on the pounds per square inch (psi) of the suspension coils from the manufacturing lots.
	
-	Run t-test to determine if the manufacturing lots are statistically different from the mean population

-	Design a statical study to compare vehicle performance of the MechaCar vehicles against vehicle from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

# Linear Regression to Predict MPG

- In this study, the spoiler weight, vehicle angle, and AWD all contributed to non-random variances. In terms of random variance, two variables are most significant: ground clearance and vehicle length.

- By looking at the p-value, which is less than 0.05, we can tell that our slope is not zero.

- As measured by the R-square of 0.71, 71% of mpg variations can be attributed to variations in the vehicle length, vehicle weight, the spoiler angle, the drivetrain,   and the ground clearance. This linear model can predict the mpg of MechaCar prototypes well.

# Summary Statistics on Suspension Coils

- MechaCar's suspension coils are designed to have a variance of no more than 100 pounds per square inch. The design specs are respected across all manufacturing lots with a global variance of 62.3 psi.Lot 1 and Lot 2 are in specs with respectively a variance of 0.98 and 7.5 psi. With a variance of 170.3 psi, Lot 3 is out of specs.

# T-Test on Suspension Coils
 ## All Lot Summary
 
- Using the common significance level of 0.05 percent, our p-value of 0.45 is above the significance level. Due to the lack of sufficient evidence to reject the null hypothesis, we can conclude that the PSI across all manufacturing lots is statistically like the population mean
 
 
# Study Design: MechaCar vs Competition
-	MechaCar is designed to match or surpass the performance of general marketplace vehicles. This goal can be achieved by improving factors like fuel efficiency, pricing, safety features of the MechaCar. In addition to the six variables from this analysis, data must be collected for all MechaCar manufacturing designs.

- MechaCar's performance metrics are statistically like all vehicles from other manufacturers, so here, it would be the null hypothesis that each metric is the same.
-	A continuous numerical variable is compared across several groups using this test. We would thus compare the means of each metric across manufacturers in this analysis.

- To conduct the test, we would require MechaCar and its competitors' data in one dataframe, with each metric grouped into one column.
