# Prosper Loans Data Exploration
## by Job Wachira


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
The data can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) while you can learn more about the variables
[here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).

Before visualising the data, I did some preliminary wrangling where I removed null values, remaining with a smaller subset of around 83,520 observations and 17 variables, including my main variables of interest. I also changed the dtype of the loan orignination date variable.



## Summary of Findings

We observed that the most common loan term is 36 months with 69% of loans taken. We also saw that the monthly repayment amount is positively skewed with most amounts being less than 1000 dollars. From our exploration, home owners took out more loans at 53% compared to non home-owners. We also note that the distribution of borrower APR is not unimodal and is dotted with peaks here and there. The prosper score almost follows a normal distribution but also has peaks at 4,6 and 8.

By exploring using bivariate plots, we observed that the mean borrower APR went up from before 2009, peaked at 2011 then gradually dropped. We also observed that the borrower APR and borrower rate are very linearly correlated. Thre does not seem to be a very clear relationship between the borrower APR and the number of open credit lines though we saw that may borrowers have between 5 and 10 credit lines. The loan original amount seems to increase as you move up the income range and it seems that those employed seem to access longer payment terms. We also see that the higher the prosper score a borrower has, the lower their borrower APR.

From our multivariate exploration, we saw that the borrower APR seems to have an inverse relationship with the credit score upper range. We also saw that the borrowe APR seems to decrease with a higher income range. The 36 month term seems to have a higher APR mean.Those employed seems to access larger loan amounts at lower APRs and across all listing categories, home owners on average enjoy a lower APR than none home owners.


## Key Insights for Presentation

I will focus on the relationship between borrower APR, home ownership, income range and the custome prosper score. My key insignt will be that the Prosper Score, income range and homeownership all have an effect on the borrower APR one can get. The higher your prosper score, the lower your APR. The higher your income range the lower the APR you get and home owners seem to on average enjoy a lower APR across listing categories.