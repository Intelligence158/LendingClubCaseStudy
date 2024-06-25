# Project Name
Project Name: Lending Club Case Study from Upgrad
Submission by: Nilima Dani and Yesha DesaiDate: 25 Jun 2024

Description:
This project about Lending case club study to identify problem statements and to analyse the possible resolution/risk notes from huge data list of loan.

Topics:
General Information
Business Objectives
Problem Statement
Analysis
Conclusion
Technologies Used
Acknowledgements
Contact

General Information:
Business Understanding:
You work for a consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
 
The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
 
In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
When a person applies for a loan, there are two types of decisions that could be taken by the company:
Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

Business Objectives

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
 
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
 
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
 
In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilize this knowledge for its portfolio and risk assessment. 
To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

Problem Statement:
1. To identify list of defaulters named “charged off” only.
2. To identify who is the highest defaulter from the list.
3. To analyse the portfolio/title identified as major defaulters from the list.

Analysis: Refer graph in attached PPT for this section
1. To identify list of defaulters named “charged off” only.
2. To identify who is the highest defaulter from the list.
3. To analyse the portfolio/title identified as major defaulters from the list.

Conclusion:
1. To identify list of defaulters named “charged off” only.
   Conclusion:   Per statistics of portfolio in analysis slide section.
Out of total loan owners: 38,577 
Full Paid loan total number – 32950
Charged off (defaulters) total number - 5627

2. To identify who is the highest defaulter from the list.
   Conclusion:Per statistics of portfolio in analysis slide section.
- The mortgage grp from house ownership shows highest bar for defaulters, however as per loan taken Vs charged off it shows that the loan with ‘own title’ are major defaulters
- The annual income graph shows 112K-140K with highest bar, however as per loan taken Vs charged off it shows that the loan with ‘3k to 31K ’ are major defaulters.

   
3. To analyse the portfolio/title identified as major defaulters from the list.
   Conclusion: Per statistics of portfolio in analysis slide section.
- The purpose of loan, for small business shows highest bar for defaulters, however as per loan taken Vs charged off it shows that the loan with ‘others’ are major defaulters

Technologies Used
Github - git version 2.45.2.windows.1
Jupyter notebook: Python 3.12.4

Acknowledgements
This project was inspired by upgard/IIIT-B learning platform.

Contact: 
Github repository link below:
https://github.com/Intelligence158/LendingClubCaseStudy.git
In addition refer attached ppt and text file.
















