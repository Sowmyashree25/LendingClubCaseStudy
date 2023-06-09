# Project Name
Lending Club is a consumer finance marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to
lend money and make a return. It specialises in lending various types of loans to urban customers. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss. Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
Lending Club company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

**Background**:<br />
       There are two type of decision taken by the company when a person applies for a loan as below <br />
**Loan accepted**: If the company approves the loan, there are 3 possible scenarios described below:<br />
   
   -**Fully paid**: Applicant has fully paid the loan (the principal and the interest rate)<br />
   -**Current**: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.<br />
    -**Charged-off**: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan <br />

**Loan rejected**: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset) <br />

 **Business Objective**:<br />
         When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:<br />
                - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company<br />
                - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company<br /><br />
  **Data Set**<br />
             - Data File named 'loan.csv' contains the complete loan data for all loans issued through the time period 2007 t0 2011.<br />
             - Data Dictionary named 'Data_Dictionary.xlsx' provides the explaination of the data columns.<br />



## Conclusions
 **Univariate Analysis**:<br />
    - Fully paid loans are way more than compared to Charged Off<br />
    - 75% of the loans are sanctioned for the term of 36 Months<br />
    - Loan Amount varies from 500 to 35K and approx. 80% of the loans are sanctioned for loan amount in range of 500 – 15K<br />
    - 75% of loans defaulted are in the loan amount range of 5k – 10K.<br />
    - More than 30% of overall intrest between 9-13%<br />
    - Around 50% of Charged Off loans are in 13-21% intrest rate range<br />
    - Loans taken for Debt Consolidation purpose are major defaulters, followed for credit card & others. Same for Charged off loans<br />
    - 60 month terms has higher numbers of defaulters<br />
    - Loan applications with 10+ years of experience are most likely to default loans.<br />
    
**Segmented Univariate Analysis**:<br />
    - 60 month term loans are more chance of defaulting loans, where as 36 month term loans have higher chance of being fully paid.<br />
    - Loans availed for purpose of Debt Consolidation have highest number of loans, also have highest number of Fully Paid and Charged Off Loans.<br />
    
**Bivariate Analysis**: <br />
    - Interest Rate for Charged Off Loans is higher than the Fully Paid loans for both 36 months and 60 months term. Indicates that loans with higher interest rate are more likely to be defaulted.<br />
    - Charged Off loans are lower for Grade A, the defaulted loans steadily increase as we move from higher grades to lower grades.<br />
    - Higher Grades have lower loan amount and interest rates than lower grades, this indicates that lower the grade higher the risk and hence higher interest rates. Also, the fact that lower grades have higher loan amount sanctioned.<br />
    -Even though the loan applicants whose Source of Income is not verified is higher, the defaulted loans are higher for loan applicants whose source of income is verified.<br />
    - Higher Interest Rates for Charged Off Loans<br />
    - Fully Paid Loans have significantly lower intrest Rates than the Charged Off laons<br />


## Technologies Used

|Techonology | Version |
|-----:|-----------|
|Jupyter notebook| anaconda version 3|
|Numpy| 1.21.5    |
|Pandas|1.5.3 |
|matplotlib.pyplot|3.5.2|
|Seaborn|0.11.2|
|Python|2.7.18|

## Acknowledgements
Credits -
- Respective documentations sites for numpy, panda, matplotlib, and python. 
- https://stackoverflow.com/
-  https://www.wikipedia.org/


## Contact
Created by @Sowmyashree25 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->
