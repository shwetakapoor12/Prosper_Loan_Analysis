This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, borrower employment status, borrower credit history, and the latest payment information. The dataset can be download here: https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1547358770029000


Variables Explored:

Term : Amount of month customers opted for loan

LoanStatus : Current status of the loan like chargedoff, completed, defauted etc...

LenderYield : The Lender yield on the loan. Lender yield is equal to the interest rate on the loan less the servicing fee.

ProsperScore : Risk Factor score from 1 to 10. 10 being least risky

BorrowerAPR : The Borrower's Annual Percentage Rate (APR) for the loan.

BorrowerRate : The Borrower's interest rate for this loan.

ListingCategory..numeric. : Prosper rating for borrowers in numbers

EmploymentStatus : Current type of employment

Occupation : Occupation of borrower at the time of listing

EmploymentStatusDuration : How long the employee has been employed

IsBorrowerHomeowner : Does the borrower owns house at the time of listing (True & False)

ProsperRating..Alpha. : Prosper rating for borrowers in alphabets

StatedMonthlyIncome : Monthly income of the borrower

MonthlyLoanPayment : Monthly loan payment amount

DebtToIncomeRatio : The debt to income ratio of the borrower at the time the credit profile was pulled.

LoanOriginalAmount : Original amount of the loan

LoanOriginationQuarter : Quarter of the month when loan was originated







Summary Findings:
After analyzing the variables across dataset, Borrower APR and Lender yield are directly positively correlated which is obvious as more the APR, more will be the interest and more will be lender's yield. However, CreditScoreRangeUpper and ProsperScore negatively correlated to BorrowerAPR. 
Scatter plot and Heatmap were also created to find out that ProsperScore and BorrowerAPR were negatively correlated as higher the prosper score lower will be the risk attached hence lower will be the APR and that further lowers down the yield.
Multiple box plots were analyzed for variables Loan status, APR and Employment Status. We can very well see that for For each category of loan status, the lowest APR is for Employed and Full-time. Whereas highest APR is for Not employed. That means borrower APR is related to Employment status. More secure jobs get low APR and vice versa.
