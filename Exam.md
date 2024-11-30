**Question 1:**

Provided you’ve loaded the CSV in a data frame called ‘data,’ what does the function tail(data[, 1])  return?

- 2.654339
- 5.315444
- [1] 3.137415 2.654339 4.619221 6.807575 2.414617 2.414658
- [1] 5.315444 3.137415 0.100000 4.407423 1.373394 1.782187

**Answer:** [1] 5.315444 3.137415 0.100000 4.407423 1.373394 1.782187

**Question 2:**

Consider the following vector—holding all median values for the columns in the real estate data. Which of the following lines of code will result in obtaining the last value in the vector—the median of the Median.Home.Value?

medians

             Crime.Rate           Average.Rooms

               3.031481                6.033179

Public.Transport.Access       Number.of.Schools

               5.000000                5.000000

      Median.Home.Value

              46.912574

- medians[which(names(medians) != "Median.Home.Value")]
- head(medians, 1)
- medians["MedianHomeValue"]
- medians[length(medians)]

**Answer:** medians[length(medians)]

**Question 3:**

The distribution of the median house price resembles which of the following?


**Answer:** Normal distributionLeft skewedRight skewed

**Question 4:**

Do you reject the Null hypothesis?

- Yes
- No

**Answer:** No

**Question 5:**

What is the adjusted R of the linear regression?


**Answer:** 0.75

**Question 6:**

What is the p-value for the average rooms?


**Answer:** 2.2e-16

**Question 7:**

Based on the regression analysis, how would you define the relationship between the average rooms and median home value?

- A linear relationship exists between the average rooms and the median home value, but the relationship isn’t significant. There’s a weak positive correlation between the two variables.
- A linear relationship exists between the average rooms and the median home value, but the relationship isn’t significant. There’s a weak negative correlation between the two variables.
- There is a significant relationship between the average rooms and the median home value, which is linear.There’s a strong positive correlation between the two variables.
- There is a significant relationship between the average rooms and the median home value, which is linear.There’s a strong negative correlation between the two variables.

**Answer:** There is a significant relationship between the average rooms and the median home value, which is linear.There’s a strong positive correlation between the two variables.
