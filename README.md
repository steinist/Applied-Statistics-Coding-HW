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

### Homework 5
In this homework, we will be playing with the US stock data collected in the past few months. You can download the filestock.zip from Canvas. The .zipfile have 4 .csv files, which includes price information of four stocks from January 23 to March 23, 2020:

1. VTI seeks to track the performance of the CRSP US Total Market Index. See (https://investor.vanguard.com/etf/profile/VTI).
2. DIS: The Walt Disney Company, commonly known as Disney, see (https://thewaltdisneycompany.com/).
3. AMD: Advanced Micro Devices, Inc. is a semi conductor company that developed the Ryzen CPUs and the Radeon graphic cards, see (https://www.amd.com/).
4. ZM: Zoom Video Communications, Inc. is an communications technology company, which provided the software for our online lectures and meetings, see (https://zoom.us/). 

We have seen a particularly wild stock market in March. We will apply ANOVA to see if there is a difference in the stock return of the four stocks. To study the stock return, we will be looking at the log return, defined as rt=log(pt/pt−1) where pt is the stock price at day t. We will use the closing price (the close column in the data) as pt. Now, answer the following questions.

1. Calculate the log-return for each of the four stocks. Check if we can assume that the log return follows the normal distribution. Use both the histogram and the Q-Q plot. (20 pt)
2. Use the Bartlett’s test to check if we can assume that the variance from the four population is the same at significance level α= 0.1. (10 pt)
3. Perform the ANOVA test at significance level α= 0.1 without using the built-in functions.(10 pt)
4. Perform the ANOVA test at significance level α= 0.1using the built-in functions. (10 pt)
5. Use pair-wise T-test with Bonferroni adjustment to find the pairs that are significantly different in mean. (10 pt)
6. State your findings from this study. (5 pt)
