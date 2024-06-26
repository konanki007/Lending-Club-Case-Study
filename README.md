# Lending-Club-Case-Study
Lending Club Case Study
# Project Name
> This project is used by lending organistation for the loans in a real business context, specifically in risk analytics within the banking and financial services sector. The goal is to understand how data can be leveraged to minimize the risk of financial loss when lending to customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
1. **Loan accepted:** If the company approves the loan, there are 3 possible scenarios described below:

Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

2. **Loan rejected:** The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)<br><br>

**Business Objectives:**<br><br><br>
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders.

Objective is to identify the risky loan applicants at the time of loan application so that such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment. And thus minimise the risk of losing money while lending to customers.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Customer Grades F & G are high likely to be ChargedOffs with mean Loan Amounts 18k+
- Annaul Income - Avg 75k & Home Ownership - Mortgage have high Charged Offs
- Every year the Charged off customers count as well as the number of loans given are increasing



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Python](https://www.python.org/) - version 3.11.7
- [Matplotlib](https://matplotlib.org/) - version 3.8.0
- [Numpy](https://numpy.org/) - version 1.26.4
- [Pandas](https://pandas.pydata.org/) - version 2.1.4
- [Seaborn](https://seaborn.pydata.org/) - version 0.12.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by live session of upGrad on EDA.
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform


## Contact
- [Ramakrishna K]
- [Purna Chandrarao V] 


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
