# (Prosper Loan Data Exploration)
## by (your name here)


## Dataset

The Prosper Loan dataset contains about 113937 loans borrowed from the San Francisco based company [Prosper MarketPlace](https://www.prosper.com/) which specializes in providing loans at low interest rates.The dataset contains 81 variables for each loan entry such as: LoanOriginalAmount, BorrowerRate, LoanStatus, and more. The complete dataset dictionary can be found [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000)



## Summary of Findings

In the exploration, I found that the when the BorrowerRate is above 20%, the LoanStatuses are mostly Past Dues with the highest rate being Past Due(>120 days), which makes sense since the more you miss payments the likely the interest rate will go up. Most Current LoanStatuses have LoanOriginalAmounts higher than 10000 US Dollars. The BorrowerRate slightly decreases with increasing rank of IncomeRange with the highest rates in range of 1 dollar to 25K dollars. This is what I expected, the higher the income range the less the interest rate on the loan will be. The BorrowerRate has a weak positive relation with the DebtToIncomeRatio and I expected a higher rate with a higher ratio, A more positive correlation. There is a slight change between the relationship between the BorrowerRate and the LoanOriginalAmount in the Not employed, 0 Dollars and the 1 to 24,999 US Dollars ranges. The Loan Amount Increases with Increasing income ranges and loan terms. The Loan amount amplitude increases with higher income ranges and increasing repayment terms.

Outside of the main variables of interest, I found that the BorrowerRate decreases with increasing LoanOriginalAmount. Which makes sense as more money borrowed will lead to a less interest rate in the loan. The LoanOriginalAmount increases with increasing loan Terms, the longer the repayment term the more money borrowed. The LoanOriginalAmount is also related to the IncomeRange with higher ranges borrowing more amounts. The 60 months term for the Not employed range has a LoanOriginalAmount amplitude that is close to the 50,000 to 74,999 US Dollars range for the same term. And the 0 US Dollar range has nearly the same LoanOriginalAmount amplitude as the +100,000 US Dollars income range for the 36 months term. These anomalies may be because Unemployed with no income need loans more and they are more likely to take loans with longer repayment periods.


## Key Insights for Presentation

For the presentation, I focus on features that have an impact on the Borrower's Rate, which are Loan Original Amount and Income Range. I first show the distributions of the BorrowerRate, LoanOriginalAmount,and IncomeRange, variable. I then show the relationship between the BorrowerRate and LoanOriginalAmount. I Lastly show the effect of loan terms on the relationship between the IncomeRange and LoanOriginalAmount. 