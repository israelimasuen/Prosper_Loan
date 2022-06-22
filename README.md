# Part II - Loan Data from Prosper Analysis
## by Nosakhare Imasuen


## Dataset

> There are 113,937 loans in this data collection, each containing factors such as loan amount, borrower rate (or interest rate), current loan status, borrower income, and more. The data set can simply be described to contain data about the individual (borrower) and details about the loan in service.

>I'll be performing data analysis on a Prosper loan data collection. Each loan in the data set has 81 factors, including borrower rate, loan status, borrower income, borrower job status, borrower credit history, and so on. Variables with missing values were removed from the Dataset to improve its accuracy. The primary goals of this project is to describe the features of factors that might impact loan status and to get some insight into the interactions between numerous variables by utilizing summary statistics and data visualizations.


## Summary of Findings

>Borrower APR is negatively related to monthly payback, which means that the higher the repayment amount, the lower the APR. The data also show that the lower the BorrowerAPR, the better the Current Credit line. There is a negative correlation between ProsperRating and BorrowerAPR. ProsperRating has an influence or impact on the percentage of the borrowerAPR. The better the Prosper Rating the lesser the BorrowerAPR. Also, it was observed that BorrowerAPR falls as loan duration lengthens significantly. Furthermore, there is also a slight negative correlation between BorrowerAPR and work status. This indicates that someone that is employed, has their own business, or work as part-time has a lower BorrowerAPR compared to either unemployed, retired or others.

>The data also reveals that for all terms, there are more loans on 12-month terms compared to other terms across all salary ranges of the borrowers. Also, an income range of above $100,000 has the highest monthly repayment for all the repayment terms. Current Credit Lines are inversely connected with BorrowerAPR, which makes sense because the better the current credit line, the lower the borrowerAPR. Furthermore, the statistics show that the current credit line has no linear relationship with the debt-to-income ratio.


## Key Insights for Presentation

> My investigation focuses on factors that may influence the borrowerAPR. I started by displaying the distribution of several variables. Also, highlight the link between BorrowerAPR and other variables in the dataset.
The data dictionary was analyzed in order to properly grasp each variable in order to make sense of the data. Following then, the BorrowerAPR became the key focus of the investigation.

>The data was then cleared of empty roles, particularly BorrowerAPR and Occupation, during the wrangling step. In addition, column(s) with no data after the initial cleansing were removed from the list of variables. The goal of the cleaning is to guarantee that the data that was analyzed can satisfy their obligations."# prosper_loan" 
"# prosper_loan" 
