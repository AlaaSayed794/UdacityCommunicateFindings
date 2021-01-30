# Prosper Loan Data
## by Alaa Sayed
## Dataset

> This [data set](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1611859174834000&usg=AOvVaw1BF_rdNDnuEPhjYmfLq2_M) contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
This [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI) explains the variables in the data set.
You are not expected to explore all of the variables in the dataset! Focus your exploration on about 10-15 of them


## Summary of Findings

> The main variable of interest was the borrower APR, this is the summary of the findings
- APR is negatively correlated with both monthly income and loan's amount
- APR's decrease with loan's amount and income slows down when the number of current loans increase<
- The 36 months term seems to have the least exceptions for the clients (highest APR)


## Key Insights

>The term of interest is the borrower's APR, so we chose from the data the variables that should be significant, which are the number of current loans, the loan's term, the monthly income and the loan's amount (there are of course another factors).Firstly we show the APR's distribution, then we show its relation with the loan's amount , the loan's term and the number of loans. monthly income is highly correlated with the loan's amount so I discarded it in the presentation.



##Resources 
- https://dillinger.io/
- [Box plot explanation](https://statisticsbyjim.com/basics/graph-groups-boxplots-individual-values/#:~:text=Categorical%20variables%20represent%20groups%20in,I%20show%20in%20this%20post).
- https://pandas.pydata.org/
- [StackOverFlow post on How to count the NaN values in a column in pandas DataFrame](https://stackoverflow.com/questions/26266362/how-to-count-the-nan-values-in-a-column-in-pandas-dataframe)
- Udacity example and template found in classroom's resources