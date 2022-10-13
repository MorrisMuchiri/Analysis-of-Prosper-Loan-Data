# Exploration of Loan Data from Prosper
## By: Morris Muchiri Mugo


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. I got the data set from Udacity's Project Data Options in [this link](https://docs.google.com/document/d/e/2PACX 1vQmkX4iOT6Rcrin42vslquX2_wQCjIa_hbwD0xmxrERPSOJYDtpNc_3wwK_p9_KpOsfA6QVyEHdxxq7/pub). 

Some of the questions I was investigating were:
* What affects the borrower APR or Interest Rate?
* Which Listing category had the highest and which had the lowest number of people taking Loans?
* How has the Borrower Rate been over the years?

I started by 1st cleaning the data then afterwards I started with the **Univariate Exploration** of the data set which helped me clean the data once more and afterwards I save the columns I was interested with in a new dataframe and also in a new csv so that I can be able to get the cleaned version of the dataset afterwards if I needed it. Afterwards I went ahead and ploted some **Bivariate** plots, whereby in the scatter plots I placeed the `dependent variable` on the `y-axis` and the other variables of interest on the `x-axis` and also came up with some boxplots, barghraphs and timeseries which all assisted in explaining relationships between 2 different variables. I finally finished with ploting **Multivariate plots** with introductions of `point plots` and here I was able to observe the relationship between 3 variables.

## Summary of Findings

Starting with **Univariate Plots** from the bargraph of `prosper rating` I observed that prosper rating of `AA` which is the lowest risk score had the least amount of people with prosper rating of `C` having the highest. From the bargraph of `Listing Category` I observed that the category which had the highest amount was people who listed that the loan was for `Debt consolidation` with the least amount of people listing it was for `RV`. From the rest of the bargraph I observed that majority of the people taking the loan were `Employed`, their loan status was `Current` and they were Home owners. 

In the **Bivariate Plots** from the time series I observed that the `Borrower rate` has been increasing from 2009 till 2011 then it started to fall and the `monthly income` of people taking loans has been increasing over the years. I also observed that the majority of people who their `loan status` was either `current` or `completed` most were home owners and also their `Borrower rate` was lower than the rest. There was also a ngative correlation between the `Borrower rate` and `Monthly loan payment` and there was a positive correlation between `Debt to income ratio` and `Borrower rate`.

And finally in the **Multivariate Plots** from the `point plot` of `LoanStatus`, `MonthlyLoanPayment` and `Prosper Rating` we can see that those who had a Proser Rating of `A` and `AA` did not go past the FinalPaymentInProgress stage and most of them had high Monthly Loan Payments and those who had a Prosper Rating of `HR(which is the lowest rating)` had the lowest Monthly Loan Payments throughout all the Loan Status. And from the point plot of `LoanStatus`, `MonthlyLoanPayment` and `Employment Status` we can see that those who were Employed had the highest Monthly Loan Payments and those who were Retired or were part-time had the lowest Monthly Loan payments. I plan bringing some of the major plots which I have explained the findings here in the explanatory presentation.

## Key Insights for Presentation

In the **Univariate plots** I choose the distribution of `prosper rating`,`lsiting category`,`employment status` and `loan status` to place in the explanatory analysis since they clearly show the distribution of the people who take the loans on the different categories and will assist the loan company to know where to focus on mostly. And on the `listing category` distribution I change the `x-axis` to display names of the listing category.

In the **Bivariate plots** I choose to place the time series of the `Borrower rate` and `Stated monthly income` and the barchart of the `loan status` and `Home ownership` the boxpot and scatter plots of `Borrower rate` and the variables of interest since they can assist also in the decision making regarding the loans.

And finally in the **Multivariate plots** I will place the 2 point plots since they clearly show the relationship between the 3 variiables involved and can be useful in decision making.
