# Module 15 Challenge

# Deliverable 1: Linear Regression to Predict MPG
The Mechacar used different metrics such as the length of the vehicle, the weight, the angle of the spoiler, the drivetrain, and even the the clearance from the ground to help design the vehicle to perform superiorly. The goal of this deliverable was to design a linear model that predicts the mpg of MechaCar prototypes using several variables from the MechaCar_mpg.csv file.

## Linear Regression to Predict MPG
Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Is the slope of the linear model considered to be zero? Why or why not?
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Answer:
mpg = 6.27*vehicle_length + 0*vehicle_weight + 0.07*spoiler_angle + 3.55*ground_clearance - 3.41*AWD - 104. 
From this formula above we can already see that vehicle length and spoiler angle have almost no impact on the mpg of the vehicle so we can rewrite our model to be:
 mpg = 6.27*vehicle_length + 3.55*ground_clearance - 3.41*AWD - 104.
 ![Screen Shot 2022-11-09 at 12.22.15 PM.png](https://github.com/bkazi07/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-11-09%20at%2012.22.15%20PM.png?raw=true)

# Deliverable 2: Summary Statistics on Suspension Coils

The suspension coil dataset contains the results from multiple production lots. In this dataset, the weight capacities of multiple suspension coils were tested to see if the manufacturing process is consistent across the entire production lot.

According to the summary output, the r-squared value of the multiple linear regression model is 0.71, which means that roughly 71% of all mpg predictions will be correct while using this regression model. In addition, the p-value of our linear regression is 5.35e-11, which is much smaller than our assumed significance level of 0.05. Therefore, we can state that there is sufficient evidence to reject our null hypothesis.

![Screen Shot 2022-11-09 at 12.27.17 PM.png](https://github.com/bkazi07/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-11-09%20at%2012.27.17%20PM.png?raw=true)

![Screen Shot 2022-11-09 at 12.27.27 PM.png](https://github.com/bkazi07/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-11-09%20at%2012.27.27%20PM.png?raw=true)

# Deliverable 3: T-Tests on Suspension Coils

The purpose of this deliverable was to perform t-tests to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch.

![Screen Shot 2022-11-09 at 12.30.20 PM.png](https://github.com/bkazi07/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-11-09%20at%2012.30.20%20PM.png?raw=true)
![Screen Shot 2022-11-09 at 12.32.05 PM.png](https://github.com/bkazi07/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-11-09%20at%2012.32.05%20PM.png?raw=true)
![Screen Shot 2022-11-09 at 12.30.37 PM.png](https://github.com/bkazi07/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-11-09%20at%2012.30.37%20PM.png?raw=true)
![Screen Shot 2022-11-09 at 12.30.45 PM.png](https://github.com/bkazi07/MechaCar_Statistical_Analysis/blob/main/Screen%20Shot%202022-11-09%20at%2012.30.45%20PM.png?raw=true)
# Deliverable 4:  Study Design: MechaCar vs Competition
1.  The metric that is trying to be tested is fuel efficiency per class.
2.  Null Hypothesis: The fuel efficiency for cars in the same class are the same. 
Alternative Hypothesis: the fuel efficiency for cars in the same class are not the same.
4.  The two-sample T-test would be the used to compare the samples from different populations. I would also maybe used a box plot to have a better visualization on the results.
5.  The data needed is fuel efficiency per car class from each competitor.



