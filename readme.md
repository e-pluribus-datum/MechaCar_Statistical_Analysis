# MechaCar Statistical Analysis

RStudio was used to load csv files and perform statistical analyses, such as linear regression and Student t-tests.

## MPG Statistics

The following is the results of a linear regression:

![mpg_lin_reg](mpg_lin_reg.png)

The vehicle length, ground clearance, and slope appear to be statistically significant values. This is evidenced by the Pr(>|t|) values being less than 0.05.

This linear regression, having an r-squared value above 0.7, effectively predicts the correlation between mpg and the other variables.

## Suspension Coil Statistics

### Overall Statistics
![susp_summary](suspension_summary.png)

### Statistics by Lot
![lot_summary](lot_summary.png)

Althought the parts in aggregate pass the manufacturer's specification of variance less than 100 psi, Lot 3 was grossly out of spec with a variance of 170 psi.