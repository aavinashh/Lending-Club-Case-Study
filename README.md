# Lending Club Case Study

The aim of this case study is to get an idea of how real world business problems are solved using EDA. 

> * Applying different EDA techniques 
> * Develop an understanding of risk analytics in the BFSI domain
> * How the data is used to minimise loss of money while leanding to customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

Business Understanding 

When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.

**There are two types of risks are associated with the bank’s decision:**

> * If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
> * If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

When a person applies for a loan, there are two types of decisions that could be taken by the company:

> **Loan accepted:** If the company approves the loan, there are 3 possible scenarios described below:
> * **Fully paid**: Applicant has fully paid the loan (the principal and the interest rate)
> * **Current**: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
> * **Charged-off**: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
>
> **Loan rejected:** Not Considered as there is no transactional history of those applicants with the company and so this data is not available with the company

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
A huge spike was observed in the total loans that have been waivered is for people who have who do not own a house and borrowed money for debt consolidation and a high amount of loan is being charged off from customers who are verified and have either mortgaged their home or customers who stay in rented homes. The same is true for customers who take loans for debt consolidation. Contrary to what was observed in the overall trend, the most charged off loans for zip code 945xx was for grade C and grade E. Grade G loans were not granted to people residing in this zip code

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
pandas
matlotlib
seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


