# Lending Club Case Study
> Consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

- Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

- Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

- Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

### Business Objective 
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
Steps for EDA :
1) Data Understanding
2) Data Cleaning
3) Univariate Analysis
4) Bivariate Analysis
5) Observation
6) Conclusion
   
- Data Set : Loans.csv

## Conclusions
- Most of the Loan amounts are in range of 5000 - 15000.
- Most of the Interest Rates on loans are in range of 9% - 14%.
- Close to 14% loans were charged off out of total loan issued.
- Most of them live in rented home or mortgazed their home. So Applicant numbers are high from these categories so charged off is high too.
- Most of the loans were taken for debt consolidation and paying credit card bill. Number of charged off count also high too for these loans.
- Count of loan application is increasing every passing year.Number of loans issued in 2008(May-October) got less due to Recession.
- Company should stop giving loans to small business as they are defaulted more.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - 1.4.4
- numpy - 1.21.5
- matplotlib - 3.5.2
- seaborn - 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was lending case study for an online advance course of upgrad.
- https://learn.upgrad.com/


## Contact
Created by [@crackpot1005] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
