# Loan Payoff Prediction
Given a set of factors (load details and socio-economic), can we predict if a loan will be paid off on time or only through collection efforts?

## Introduction
In an ideal world, all customers pay off their loan debts on time or even in advance. In reality, banks spend resources (time, financial, and human resource) in order to collect the loaned amount, or in worst cases, recover part of the loan debt in an attempt to minimize losses. Predicting quality of loans (determine loans that will be paid off or be put on collection) allows bank to plan interventions ahead of time and allows key decision makers decide on making policy changes in giving out loans.

In this repository, we explore different aspects in predictive modeling that we can use in order to inform business decision making associated with loan payoff.

## Data
For this demo repository, we use a loan dataset hosted in kaggle ([link here](https://www.kaggle.com/zhijinzhai/loandata)):

### Variables
The following are the variables in the dataset:
1. Loan ID - unique identifier for the loan
2. Loan Status - our target variable
3. Principal - principal loan amount
4. Terms - terms in paying the debt (can be weekly, biweekly, and monthly)
5. Effective_date - date when the loan took effect
6. Due_date - date by when the loan should be paid off
7. Paidoff_time - The actual time a customer pays off the loan
8. Pastdue_days - How many days a loan has been past due
9. Age, Education, Gender (customer's basic demographic information)

