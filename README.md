# Lending Club Case Study
> Assignment to apply knowledge of EDA

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the  company has to make a decision for loan approval based on the applicant’s profile. 
- Two types of risks are associated with the bank’s decision:

* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

* If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

- The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

- When a person applies for a loan, there are two types of decisions that could be taken by the company:

1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

* Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

* Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

* Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
 

## Business Goal
- The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 


## Conclusions:
1. People with 36 months loan term  
2. People with Grade B, C, D  
3. People with Sub-grade B3, B5, B4, C1, C2, C3, D2 & D4  
4. People with employment length of 10+ years & <1 year
5. People whose loan was issued in year 2011
6. People with Home ownership as home, rent & other
7. People with Purpose of small_business, renewable_energy & education
8. People with 60 months loan term
9. People from NE (Nebraska), NV (Nevada), SD (South Dakota), AK (Alaska), FL (Florida)

## Other bivariate factors are:
1. As the Grade and the Sub Grades increases, Charged Off Rate increases
1. Top 3 employement length of Charged Off category are 1 year, 0 year (< 1year) & 10 year (> 10 year)
1. Loan amount increases, Charged off rate increases
2. As ineterest increases, Charged off rate increases
5. As the annual income decreases, Charged off rate increases 
6. As the installment rate increases, Charged Off increases
7. As dti value increases, Charged Off rate increases


## Technologies Used
- Language - Python
- Library - Numpy
- Library - Pandas
- Library - matplotlib
- Library - seaborn


## Acknowledgements
- Tutorial video on EDA, Weekend live session on the assignment details, EDA basics and doubt resolution.
- This project was based on (https://learn.upgrad.com/course/3611/segment/26495/162238/498573/2568139).


## Contact
Created by [@Radha-Mishra] - feel free to contact me!

