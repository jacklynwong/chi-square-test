<h1>Chi-Squared Tests</h1>

Chi-Squared tests are used with categorical variables. These variables don’t have a numerical value so we compare the variable counts instead of the actual value of the variable themselves.

<h1>Chi-Squared Goodness-of-Fit Test</h1>

This test compares the distribution of a segment’s categorical data to that of the entire population.

Example: Does the distribution of Claimed Games for aged 40+ PG users match that of the entire PG population?

The segment for aged 40+ PG users has the below Game Title Claims distribution vs the total population. Aged 40+ PG users had 3k Apex Legends game claims. The total population had 8k game claims.


![image](https://user-images.githubusercontent.com/114509199/193664236-d47ec514-5ba7-460f-85c3-c08ec2ee4906.png)



Calculate what the expected claims for each Game Title should be for the segment and use this to find the chi-squared statistic. If this exceeds the critical value (determined by a desired Confidence Level and number of categories you're looking at), then your segment is statistically different than the population.

You can also find the p-value and evaluate that it falls below 0.05 (assuming a 95% Confidence Level).

In our example, we're using a 95% Confidence Level and the chi-squared statistic > critical value and p-value < 0.05. We can conclude the aged 40+ segment is statistically different than the population.




![image](https://user-images.githubusercontent.com/114509199/193664504-ba152a39-5e18-4db3-8908-3efc9ddfe88f.png)





<h1>Chi-Squared Test of Independence</h1>
This test if 2 categorical variables are related or independent. 

Example: Does birth month relate to game genre claimed?

Consider the following data of birth months and game genre claims.

![image](https://user-images.githubusercontent.com/114509199/193664658-03bce477-01ed-4e7f-af9e-dbb9c03d487c.png)


Calculate expected counts of each cell by multiplying the row total for the cell by the column total, then dividing by the total number of observations. Then use the chi-squared formula to see if the variables are independent.

