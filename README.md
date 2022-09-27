# Analyze-A-B-Test-Results

## Intro
A/B tests are very commonly performed by data analysts and data scientists. 

## Brief description
A company has developed a new web page in order to try and increase the number of users who "convert", meaning the number of users who decide to pay for the company's product. The goal of the following projects is to walk through an A-B Test to help a company understand if they should implement a new page, keep the old page, or perhaps run the experiment longer to make their decision. The data within this project has been collected by Udacity and is part of the Practical Statistics final exam.

## Conclusions
As a resulte, in this analysis we have used several methods in order to gather proof that our preliminary observation to not change the current page to the new one is worth pursuing. Therefore, we have used the hypothesis testing by finding the p-value via sampling distribution of the mean difference, Z_test and logistic regression.
Also, we have included an additional variable to the logistic regression model i.e. three countries namely Canada, the United Kingdom and the United States.
This being said, we can say with 95% confidence that we do not have enough proofs to reject the null hypothesis where the old page is providing the same rate of convergence.
Also, we can add that the convergence rate for the UK is the highest among the three, with CA having the lowest amongst them.
At this point, we can emphasise two types of practical significance of this analysis. First is that the data suggest that one variable has a positive coefficient value that would indicate actions toward that particular area. For example, we saw that the UK provides the highest convergence rate for the new page. However, the overall convergence rate of the new page reduces its practical significance. Nonetheless, the second type of practical significance is extracted from the fact that the convergence rate of the new page is low enough to make improvements or to give up this project. Also, since the UK had the highest convergence rate among the three countries, we can develop a new investigative project to better understand the reason behind this rate. Chances are we could dive deeper into what makes a page work better in the UK and therefore, extrapolate the idea that each country has its particularities that could be used for a new project.
