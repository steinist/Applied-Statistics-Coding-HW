# Applied-Statistics-Coding-HW
## HKUST Fall2020 - MATH2411: Applied Statistics

### Homework 1
Use the dataset Demographics_State.csv, and conduct the following data analysis in R.
1. Compute the average, median, range, standard deviation and quartiles of total_population.
2. Plot the histogram and the boxplot of total_population.
3. Draw the scatter plot of total_population versus median_age. Compute the covariance of the twovariables without and then with the built-in function; check if the results are the same.

### Homework 2
In this assignment, you will compare the two estimators. In the following questions, we assume that λ = 10.

1. Generate n = 10 independent Poisson(λ) random variables, calculate the sample mean (you can use rpois(n = , lambda = ) function in R, where n is the total number of random varables generated and lambda is the parameter λ). Do the above 1000 times, then you have 1000 observations of the sample mean(each of them is calculated from n = 10 independent Poisson(λ) random variables.) Generate the boxplot and histogram of the 1000 observation of sample means.

2. For n= 10,repeat Part 1 with the sample variance.

3. Compare the boxplot and histogram you obtained from Part 1 and 2. Comment on the difference between them.(Hint: measure of dispersion)

### Homework 3
No coding Homework

### Homework 4
Here we are going to test a couple of hypotheses about the Old Faithful data in R. Remember, this is the faithful data frame that is built in to R. You can use data(faithful)to load data set. First split faithful into two separate data frames: (1) those entries with eruption times less than 3 minutes (eruptions < 3) and (2) those entries with eruption times greater than or equal to 3 minutes (eruptions >= 3). Answer the following about the entry wait time (waiting):
1. For the entries with short eruption times, you want to test the hypothesis that the associated waitinglast on average less than 60 minutes. What is the null hypothesis? What is the alternative hypothesis? (Write your own code) (10 pt)
2. Give R commands to compute the statistic that you used in (1) and the resulting p-value. What values did you get? Would you reject the null hypothesis at the α= 0.05 level? (15 pt)
3. For the entries with long eruption times, you want to test the hypothesis that the associated waiting time last on average shorter than 80 minutes. What is the null hypothesis? What is the alternative hypothesis? (Write your own code) (10 pt)
4. Give R commands to compute the statistic you used in (3) and the resulting p-value to test the hypothesis you came up with in part (3). What values did you get? Would you reject the null hypothesis at theα= 0.05 level? (15 pt)
