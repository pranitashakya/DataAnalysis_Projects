# Analyzing borrowers’ risk of default
## Project description
This project is to prepare a report for a bank’s loan division. We need to find out if a customer’s marital status and the number of children have an impact on whether they will default on a loan. The bank already has some data on customers’ creditworthiness.

The report will be considered when building a credit scoring of a potential customer. Credit scoring is used to evaluate the ability of a potential borrower to repay their loan.

## Table of contents
- 1. Data Description
- 2. Technology Used
- 3. Steps to follow
- 4. Goal


## 1. Description of the data
- children: the number of children in the family
- days_employed: how long the customer has been working
- dob_years: the customer’s age
- education: the customer’s education level
- education_id: the identifier for the customer’s education
- family_status: the customer’s marital status
- family_status_id: the identifier for the customer’s marital status
- gender: the customer’s gender
- income_type: the customer’s income type
- debt: whether the customer has ever defaulted on a loan
- total_income: monthly income
- purpose: the reason for taking out a loan

## 2. Technology Used
Python
Jupyter Notebook
Pandas

## 3. Steps to follow
### Step 1. Open the data file /datasets/credit_scoring_eng.csv and have a look at the general information.
### Step 2. Preprocess the data:
- Identify and fill in missing values
- Replace the real number data type with the integer type
- Delete duplicate data
- Categorize the data
### Step 3 Answer these questions:
- Is there a connection between having kids and repaying a loan on time?
- Is there a connection between marital status and repaying a loan on time?
- Is there a connection between income level and repaying a loan on time?
- How do different loan purposes affect on-time loan repayment?
### Step 4 Write an overall conclusion.

## 4. Goal
- apply preprocessing on credit score data and perform demographic analysis
- evaluate the ability of potential borrowers to repay their loan