# Lending Club Case Study
> Our objective is to identify predictors of default so that at the time of loan application, we can use
those variables for approval/rejection of the loan.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors
looking to lend money and make a return.

When the company receives a loan application, the company has to make a decision for loan approval based on the
applicant’s profile.
Our objective is to identify predictors of default so that at the time of loan application, we can use
those variables for approval/rejection of the loan.

- Dataset used is loan.csv.
It contains the complete loan data for all loans issued through the time period 2007 to 2011.

## Technologies Used
- numpy 1.23.5
- pandas 1.5.3
- matplotlib.pyplot 3.7.0
- seaborn 0.12.2    

## Conclusions
- Lower the annual Income higher are the chances of getting charged off.
- High interest rate is major contributor in loans getting charged off.
- Charged off proportion increases with grades moving from “A” towards “G”.
- Applicants with low DTI have low chances of getting Charged Off. Higher the DTI, higher will be the interest rate
- Small Business Applicants have high chances of getting charged off.
- More the employment length (experience) more will be the annual income and hence more amount can be funded to the applicant.
- Charged Off loans are more for loans where Loan term is 36 months which means people tend to charge off when the loan term is less.
- More number of charged offs were in December, May and September. In these months interest rates were also slightly higher.

## Acknowledgements
- References 
  stackoverflow.com 
- This project was based on Lending Club

## Contact
Created by @divya4singh and @GaayathriVL - feel free to contact us!
