# Boom Bikes Sharing Case Study
> Linear Regression model for a US bike-sharing provider BoomBikes.


## Table of Contents :
* [Problem Statement](#problem-statement)
* [Objectives](#objectives)
* [Approach](#approach)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Glossary](#glossary)
* [Team](#team)


## Problem Statement :
Lending Club is a consumer finance marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return.
It specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant's profile.
Like most other lending companies, *lending loans to ‘risky’* applicants is the largest source of financial loss *(called credit loss)*. The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.
In other words, **borrowers** who **default** cause the largest amount of **loss to the lenders**. In this case, the customers labelled as *'charged-off' are the 'defaulters'*.
The core objective of the excercise is to **help the company minimise the credit loss**. There are two potential sources of **credit loss** are:
* Applicant **likely to repay the loan**, such an applicant will bring in profit to the company with interest rates. Rejecting such applicants will result in loss of business.
* Applicant **not likely to repay** the loan, i.e. and will potentially default, then approving the loan may lead to a financial loss for the company
 
 ## Objectives :  

The goal is to *identify these risky loan applicants*, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA using the given [dataset](./loan.csv), is the aim of this case study.
If one is able to *identify these risky loan applicants*, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
In other words, **the company wants to understand the driving factors (or driver variables)** behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

## Approach :

- Step 1: Data Understanding
- Step 2: Data Cleaning and Outlier Treatment
- Step 3: Segmentation of Variables
- Step 4: Segemented Univariate Analysis
- Step 5: Bivaraiate Analysis
- Step 6: Multivariate Analysis
- Step 5: Results , Inferences and Recommendations

## Technologies Used :
- python           : 3.11.5 
- numpy            : 1.26.4
- pandas           : 2.2.2
- seaborn          : 0.13.2
- matplotlib	   : 3.9.0
- IPython          : 8.15.0
- ipykernel        : 6.25.0
- ipywidgets       : 8.0.4
- jupyter_client   : 7.4.9
- jupyter_core     : 5.3.0
- jupyter_server   : 1.23.4
- jupyterlab       : 3.6.3
- nbclient         : 0.5.13
- nbconvert        : 6.5.4
- nbformat         : 5.9.2
- notebook         : 6.5.4
- qtconsole        : 5.4.2
- traitlets        : 5.7.1
- conda            : 23.7.4

## Conclusions :

#### The above analysis with respect to the charged off loans. There is a more probability of defaulting when : 
1. Borrowers with high interest and 10+ years of employment length. Also when employment length is 10yrs and loan amount is 12k-14k 
2. Borrowers living on mortgage with loan amount greater than 12000.
3. Loan for debt consolidation, credit card, small business with loan amount greater than 12000.
4. Loan provided for house purpose with average interest grater than 12%.
5. Loan provided with an average of 11% interest rate for 36months of tenure.
6. Loan provided with an average of 14% interest rate for 60months of tenure.
7. Average loan amount greater than 15000 with grade  F, G .
8. Installments between 800 - 12000 with average interest greater than 15%.
9. Average interest rate of 17% with installment greater than 1200.
10. Applicants taking loan for 'home improvement' and have income of more than 60k 
11. Applicants taking loan for 'renewable energy' and have income of more than 45K. 
12. Applicants whose home ownership is 'MORTGAGE and have income of 60-70k
13. Applicants who receive interest at the rate of 21-24% and have an income of 70k-80k
14. For grade G and interest rate above 17%
15. When the loan is verified and loan amount is above 16k
16. Applicants who have taken a loan for small business and the loan amount is greater than 12K
17. Applicants whose home ownership is 'MORTGAGE and have loan of 14-16k

## Acknowledgements :

- The project reference course materieals from upGrads curriculm 
- The project references insights and inferences from presentation in upgrad live class given by [Shivam Garg] ( https://www.linkedin.com/in/shivam-garg-0494a2ab )

## Glossary :

- Data Visualisation
- EDA - Exploratory Data Analytics

## Team :
* [Arnab Bera] ( https://www.linkedin.com/in/arnabbera1994/ )
* [Arpit Nigam] (https://www.linkedin.com/in/arpit-nigam0401/)
