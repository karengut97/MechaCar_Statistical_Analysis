# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
<img src="images/linear_output.png" width="500" height="500"/>  

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

    Vehicle Length (p-value: 2.60e-12) and Ground Clearance (p-value: 5.21e-08) provide non-random amounts of variance to the mpg values due to their p-values being below 0.05. This means they are statistically significant to the mpg measure on these vehicles. 

2. Is the slope of the linear model considered to be zero? Why or why not?


    The slope of this linear model is not zero. This is evidenced by the fact that our p-value (5.25e-11) is MUCH smaller than our assumed signficance level of 0.05%.

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

    Yes, this model is effective at predicting mpg in the prototypes. The R-squared value is 71.5% which indicates that roughly 71.5% of the variability of mpg is explained by using this linear model.

## Study Design: MechaCar vs. Competition
1. Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. 
In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating. 

3. In your description, address the following questions:


*  What metric or metrics are you going to test?
*  What is the null hypothesis or alternative hypothesis? 
*	 What statistical test would you use to test the hypothesis? And why? 
*	 What data is needed to run the statistical test?


