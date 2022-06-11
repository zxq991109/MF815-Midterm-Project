# MF815-Midterm-Project
## Loan Default Prediction

## Background
You are provided a dataset for vehicle loan default prediction where you need to predict the
customer who will default for paying the EMI (Equated Monthly Instalments).
Financial institutions incur significant losses due to the default of vehicle loans. This has led
to the tightening up of vehicle loan underwriting and increased vehicle loan rejection rates.
The need for a better credit risk scoring model is also raised by these institutions. This
warrants a study to estimate the determinants of vehicle loan default. A financial institution
has hired you to accurately predict the probability of loanee/borrower defaulting on a vehicle
loan in the first EMI on the due date. Following Information regarding the loan and loanee
are provided in the datasets:
Loanee Information (Demographic data like age, Identity proof etc.)
Loan Information (Disbursal details, loan to value ratio etc.)
Bureau data & history (Bureau score, number of active accounts, the status of other loans,
credit history etc.)

Doing so will ensure that clients capable of repayment are not rejected and important
determinants can be identified which can be further used for minimising the default rates.

## Executive Summary
Conducted feature engineering techniques on datetime and categorical features. 
Conducted oversampling method to solve the problem of highly imbalanced distribution of the target variable.
Utilized Logistic regresion, Random forest, and Xgboost classifiers to predict loan default on the test data set.
