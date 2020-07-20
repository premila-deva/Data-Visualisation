# Prosper Loan Data Exploration
## What factors affect the Borrower's APR?

## by (Premila)


> This data set contains 113,937 rows with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. My feature of interest is Borrower APR rate and analyse how other features influence it.
> Since there are 81 variables in the dataset, I have only chosen 13 which are I think more relevant to the analysis.
> I had to rename 'ListingCategory (numeric)' variable to 'ListingCategory'.
> Also ListingCategory had numeric entries which should represents the type of loans. I had to replace these nemeric entries to relevant listingCategory.
> Eliminated missing values
> Changed object type variables to categorical type.



## Summary of Findings

> In the exploration I found that Borrower APR has a; negative correlation with Prosper score, Loan original amount and  Current credit lines. Has a positive correlation with with Total Inquries and CurrentDelinquencies. Auto, Business, Home improvement and Debt consolidation types loans had been granted with higher APR rates. Charged off, Defaulted types of loan status had a higher APR rate compared to Final settlement in progress or current loans. Individuals with annual salary more than £100000 had lower APR rate compared to those not working. But it is interesting to see not emplyees were able to borrow a loan even for a APR rate. To extend my investigation on this I plot against loan amount and Borrower APR. Plot revealed not employed had borrowed a maximum of £25000 a median of around of £5000. It is suprise to see that not employed had borrowed a bigger amount than those who work part time. Compared to Homeowners, not home owners had a lower APR rate and Loan for 36 months duration had a higher rate. I continued my analysis looking at the relationships of other variable with Prosper score. Income range of more than £100,000 have a higher median Prosper score. Intrestingly applicants who are not working and earning £0 have an equilavant median Prosper score of those who earn around £1-25,000 and 25,000-50,000.Not employed have a higher median Prosper Score than self-employed. Full-time workers have a highest median of Prosper score. 
>In my multivariate analysis I planned to dig my analysis to more about Employment status with other features and also intrested to see whether being a home owner has influence.
> In conclusion, Borrower APR rate has gone down with a Prosper Score increasment, which concludes if you have a good Prosper score by the time you apply for a loan chances are more likely you would recieve a lower APR rate. Which make sense as Prosper Score represent the creditworthiness of an individual. Borrower APR is very high for a chosen Prosper Score for Not employed, Retired than other employment types
Likewise other numeric features I have chosen such as CurrentDelinquencies, Credit lines, Total Inquries all represents the financial state of an individual. It is evidence from the analysis increasment of these feature values would result higher Borrower APR, Specially if the individual is Not employed, Retired.
Loan Term also the influence the Borrower APR, specially Not employed have recieved a higher median APR rate across all three terms whereas Full time and Employed have a lower rate.
There is a degree of variance in Borrower APR for different type of Loan Status. Comparitively Employed and Full time workers have granted with lower median Borrower APR. Not employer have granted loan with a higher median APR rate than all other types. Interestingly Part time workers manage to get a comparitively lower APR rate for Business loans. Retired people have borrowed medical loan for lower median APR rate.
It is interesting to see Not Employed, applicant with £0 Income Range have been granted with a loan with a higher APR rate. Not Employed Employment Status has a larger range for Past Due payments and Defaulted loan accounts. Employed status have a less number of Defaults and Past due payments comparitively.
Not employed, part-time and retired applicants are mainly for Debt consolidataion, Business and other which makes sense. Also most of the Not employees are Home owners with mortgage on their credit profile or with a proof of bieng a home owner.


## Key Insights for Presentation
> Since I wanted to see continue my analysis about the APR changes for different Employment status I didn't include the analysis of Prosper score and other variables in the final presentation.
>I start by introducing the Borrwer APR, followed by loan original amount distributions. Showed the relationship between the categorical variables using boxplots. Afterwards to visualise the change of Borrower APR across Employment status with many other features I used line plots, heatmaps, stacked bars and point plots. And I add the 'Is borrower Home owner' to analyse is being a home owner is an advanced for various employment status to get a lower rate loans.