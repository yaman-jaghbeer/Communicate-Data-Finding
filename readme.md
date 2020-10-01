# (Loan Data from Prosper)
## by (Yaman Jaghbeer)


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

This [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) explains the variables in the data set. We are not expected to explore all of the variables in the dataset! Will focus exploration on about 10-15 of them.

## Summary of Findings

I found strong correlation between Loan Status and following features:

- BorrowerAPR (Will include in the explanatory slides)
- ProsperRating
- Term
- EmploymentStatus (Will include in the explanatory slides)
- IncomeRange (Will include in the explanatory slides)

I am not including "ProsperRating" because it seems it gives the same reading as Loan Status. It feels like the same variable addressed in a different way,

The "Term" seem biased toward 36 months due to approval procedure.

I found the following feature interesting and want to explore it more:
- LoanOriginalAmount
Will include it in the explanatory slides as it gives depth the analysis.

The following has a weak or no apparent relation with the Loan Status:
- EmploymentStatusDuration
- IsBorrowerHomeowner: Doesn't give any indication
- DebtToIncomeRatio: has lot of outliers values which seem unreasonable.




## Key Insights for Presentation

Borrower APR is a strong indicator if the loan will default or be completed.
Also security at job plays main role.

## Feedback

Feedback from audience of 3:
- Simple and easy to follow
- Graphs with 3 variables were challenging to understand with reading the comments with it