# Lending-Club

Team : Daffney Viswanath
       Aishwarya Deokuliar
       Hardika Ganatra

It is important to be able to estimate credit risk of each borrower as precisely as possible.
Hence, our project focuses on modelling three different classification models namely Logistic Regression, Naive Bayes, and Decision Tree.
Our goal is to determine whether a borrower will default or not on the basis of several factors such as income, age, location and interest rate.
We will also compare the three models to determine the best model on the basis of AUC score and cross validation score.

Data:
The dataset is sourced from Kaggle.
Data Source: https://www.kaggle.com/wendykan/lending-club-loan-data




TABLE OF CONTENTS
I. PROJECT OVERVIEW

II.DATA

III. DATA UNDERSTANDING

1.Import Libraries:
2. Loading the Data
3. Checking Dimensions
4. Understanding columns in the Dataframe
5. Description of the columns
IV. DATA CLEANING

1. Parsing loan_status
2.Removing the columns having more than 90% missing values
3. Converting datatypes
  b) Earliest Credit Line (earliest_cr_line)
  c) Issue Date (issue_d)
V. EXPLORATORY DATA ANALYSIS AND DATA PRE-PROCESSING

1.Delinquincy
2.Loan Amount
3.Interest Rate
4.Grade and Subgrade
5.Purpose
6.Installment
7.Home Ownership
8.Term
9.Annual Income
10.Verification Status
11.DEBT TO INCOME
VI. DATA PREPARATION:

1. Target and Predictor Variable :
2. LOAN STATUS- Good or Bad?
3. Splitting Test and Train Data
4. Weight of Evidence and Information Value
Rules we followed for categorizing variable by WOE:-
    a) Discrete Variables: Categorizing by WOE
        i) Home Ownership, Address State and Grade:
        ii) Address State:
        iii) Verfication Status and Purpose:
    b) Continuous Variables: Categorizing by WOE
        i) Issue Date:
        ii) Interest Rate:
        iii) Funded Amount:
        iv) Earliest Reported Credit Line:
        v) Delinquincy for past 2 years:
        vi) Number of Inquiries in last 6 months:
        vii) Open Account:
        viii) Public Record:
        xi) Total Credit Account Factor:
        x) Borrower's Delinquint Accounts:
        xi) Total revolving high Credit Limit:
        xii) Annul Income:
        xiii) Month since Last delinquincy:
        xiv) Debt to Income Ration:
        xv) Term, Employee Length and Installment
    c)Test Data Preparation:
VI. FEATURE SELECTION FOR MODEL BUILDING:

VII. MODELLING

Model 1: Logistic Regression
  Model Evaluation - Cross-validation
Model 2: Naive Bayes
  Model Evaluation- Cross Validation
Model 3:DecisionTree Classifier
  Model Evaluation: Cross Validation
AUC Scores of all models
  Logistic Regression Model
  Naive Bayes:
  Decision Tree Classifer:
VIII. MODEL COMPARISON:

IX. CONCLUSION:

REFERENCE:
