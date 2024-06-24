# Boom Bikes Sharing Case Study
> Case Study of Linear Regression model for a US bike-sharing provider BoomBikes.


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
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands.

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 
 
 ## Objectives :  
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
Please find the Bike Sharing [dataset](./loan.csv) here and Data dictionary (./loan.csv) here.

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
