# Prosper Loan Data Analysis
## by Amanuel Loeta


## Dataset

This prosper loan data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. I have explored and try show some finding from the dataset.  
On the data set I have made some wrangling on Listing Catagory columns to change from numeric value to String.



## Summary of Findings

My main interst in the dataset is about the borrower's detail information. What's their occupation, their state and other details of the borrower. Using some of the features I have found the following findings.
##### On Univariate exploration
- The Borrower loan status distribution is mostly found on Current and on Completed status.
- State of California is the state with highest borrowers, followed by Texas and New York.
- The main cause for a loan is Debt Consolidation.
- Most of Borrowers are employed. The list of them are Retired and Not Employed.
- Borrowers: half of them are home owner and half of them are not.
- Interest Rate for the borrowers are between 5% and 35%.
- Most of the borrower's monthly income are below 25,000. With high distrubtion between 0 and 10,000.
- Most Borrowers debt to income ratio are around 20%.

##### On Bivariate exploration
- The Borrower APR is mostly distributed around 10% - 20% for each Employment status.
- Borrowers which have very less income have high DebtToIncomeRatio.
- Borrower Rate and Prosper Score have high negative coorelation between them.
- On the other hand on the quantitative vs quantitative plot we explored on the relations between DebtToIncomeRatio and Borrower Rate. But, seems like they don't have a positive or a negative coorelation between them.

##### On Multivariate exploration
- On this exploration I found that the prosper score is decreasing when the borrower rate is increasing. And also in the plot there is a high distribution on Completed and Current loan status.
-  Thier is high coorelation between BorrowerAPR and Prosper Score. And also the distribution among the employment status.



## Key Insights for Presentation

My Key insights for the presentation is what is mainly affects borrower interest rate, what status of borrower would affect the loan status, debt to income ratio, and prosper score.  

I have explored it step by step starting from exploring each variablens alone and finding the coorelation with other variables.
