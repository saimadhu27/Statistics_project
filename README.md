# Understanding Customers Using Statistics
In this project we have used a marketing campaign dataset which consists of Segments of customers, the number of orders they placed and the number of different products they bought. Our study aims to find insights between these variables and inferences for better understanding customers. The entire project has been done on R Studio, the PDF files are knitted R Markdown files.

## First Hypothesis test - Non parametric tests:
1.We want to test the hypothesis that mean number of online orders placed by different groups of customers in Education is different to orders placed by a particular group of customers. We used a non parametric test called Kruskal-Wallis test to test this hypothesis and found that the mean number of online orders placed by different group of customers in Education differ significantly.

2.We also want to test the hypothesis that low income people spend less on gold products while higher income people spend more on gold products. To test this hypothesis, we have used an non parametric t-test called Wilcoxon Rank Sum test. We have used this instead of independent two sample t-test becuase the income groups doesn't follow a normal distribution. After performing the non-parametric t test we found that higher income people spend more gold products than low income people.

## Second Hypothesis test: Chi-square test of Independence:
Second hypothesis tests to see if the number of children a customer has and amount of sweet products(C) he/she purchases is dependent, and we found that these two variables are actually dependent on each other.

## Third Hypothesis test - Multiple linear regression:
Lastly, the third hypothesis test is to check if the number of kids the customer has and their Education status have any impact on the amount they spend on wines.After performing the multiple linear regression, we found out that the number of kids a customer has and their Education status have a significant impact on the amount they spend on wines.
