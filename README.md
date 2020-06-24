# Prosper-Loan-Data-Analysis


## Dataset

> Prosper is a marketplace lending company that provides unsecured personal loans for any purpose. This dataset, includes 61 columns and 113937 rows, provides valuable information about loan listings and related variables including borrower as well as lender information. In this analysis, we are interested in focusing on variable Borrower's Annual Percentage Rate (APR) for the loan - will be referred as APR in the rest of this notebook, and the factors that have an impact on borrower's APR.

## Summary of Findings

> In this dataset, APR has a minimum value of 0.006 and a maximum value of 0.513, with which, the rage of 0.35-0.38 are the most common rates, followed by the APRs within the rage of 0.15-0.25. California has the highest number of loan listings, way higher than rest of the states. Majority Prosper users had the income rage from 25,000 to 74,999, followed by the users who had income rage from 75,000 to 100,000+. $4,000,  $15,000 and $10,000 are the most popular loan amounts users request. Current and completed loans account for the majority of the loan status in our dataset, compared to the charged off and defaulted loans, indicating a healthy financial environment. 

> The borrowers with the following characteristics tend to receive a lower APR:
- a high prosper score
- working as a computer programmer or analyst
- high income
- is a home owner
- a high loan original amount 
- a large amount of open credit lines


## Key Insights for Presentation

> APR and estimated loss have the strongest positive correlation. Both APR and estimated loss are strongly negatively correlated with prosper score. When predicting what APR a borrow will receive, one can look into the estimated loss associated with the borrower, one important indication of estimated loss is borrower's prosper score. 

## Resource
> https://www.prosper.com/
