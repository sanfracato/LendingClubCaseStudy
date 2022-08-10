# Lending Data - Case Study
> Analyse the loan applications to determine the risks associated with approval decision
--- Lending Club is a website/service that operates as an interface between borrowers and lenders. Their business model requires them to provide verification data  to lenders on the borrowers to help determine the action required on a loan application - Either acceptance or rejection.


## Table of Contents
* Problem statement
* Technologies used
* Conclusion
* Acknowledgments



## Problem Statement
- The problem at hand is to analyse the dataset which holds information about the borrower's data  who have applied for a loan and determine various factors/variables that will lead to borrower defaulting the loan.
- This key information that comes out of the data analysis task will help the lenders take an well informed decision to either accept the loan application (so borrower would pay in full - leading to profit) or reject the application (again leading to prevention of loss)

- Dataset used is 'LENDING DATA'


## Technologies Used
- Python  - version 3.8 
- Google Colab
- Microsoft Office Tools


## Conclusions
1. Loan status is impacted by the state the borrower resides in and home ownership. States with higher cost of living and low income will result in borrowers defaulting

2. Loan status is impacted by the grade the borrower belongs to. When the borrowers are in grades A, B and C and low income, then if annual income is not verified properly chances of defaulting is higher

3. Loan status is impacted by the DTI of the borrower. When DTI is higher and borrower has a low annual income, they are more likely to default

4. Loan status is impacted by loan amount when borrower has a low income and lesser loan amount, defaulting chances are higher. This could be due to human factor that we can somehow repay as the loan amount is lower and keep skipping instalments

5. Loan status is impacted by the purpose when the borrower has higher DTI and low, medium annual income.

6. Loan amount approved should be lower when a borrower has a higher DTI and number of terms is higher. 

7. When annual income is low, irrespective of the loan amount and number of terms, chances for default is higher. These are huge risk borrowers.

8. When the length of employment is lesser (less than 3 years), the annual income is lesser. These are high risk borrower


## Acknowledgements

- Dataset    - Thanks to UpGrad for sharing the dataset.
- References - Data dictionary for Lending Data


## Contact
Created by Durga Srinivasan [@durgaavrs] and Abbas Bagwala [@sanfracato]---feel free to contact us!
