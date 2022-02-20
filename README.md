# MechaCar Statistical Analysis

### Linear Regression
![linear](summarylm.png)
- Vehicle length and ground clearance would provide a non random amount of variance to the mpg values in the dataset.
- The p-value of the summary is 5.35e-11, which is lower than the assumed significance level, so we would reject the null hypothesis.
- The linear model seemingly effectively predicts mpg of MechaCar protoypes because the Multple R squared value equates to about 71%.

### Suspension Coil Summary
![summary](lot_summary.png)

![summary](total_summary.png)

- The current manufacturing data meets the design specifications on only Lots 1 and 2. Lot 3, however exceeds a PSI of 100. Lot 3 has a PSI variance of 170.
### T-Tests
![ttest](ttest_suspension.png)
- Lot 1 and 2 hypothesis cannot be rejected
- 
![ttest](ttestlot1.png)
![ttest](ttestlot2.png)
-Lot 3 p values rejects null hypothesis. 

![ttest](ttestlot3.png)

### Study Design: MechaCar vs Competition
For the average car consumer, normally you factor in specs like fuel efficiency and maintenance cost. We would need to factor in other car companies and how they rate on this spectrum to determine how MechaCar compares. Essentially, you would want to run a T-Test on these factors to determine if Mechacar compares to the competitor.