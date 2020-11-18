# Loan-prediction

<h1 align="center"><font size="1">Classification with Python and Scikit-Learn</font></h1>

In this notebook are applied several Machine Learning algorithms in order to predict whether a loan case will be paid off or not.

A historical dataset(provided by IBM) from previous loan applications is fed to different classifiers, after a previous data cleaning and manipulation.
The goal is to evaluate the accuracy of each algorithm and check which one presents a better performance in the stated objective.

The following algorithms will be used:
- K-Nearest Neighbour
- Decision Tree
- Support Vector Machine
- Logistic Regression

To measure the accuracy of each classifier, the following metrics will be used:
- Jaccard index
- F1-score
- LogLoss


### About the dataset


This dataset is about past loans. The data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

| Field          | Description                                                                           |
|----------------|---------------------------------------------------------------------------------------|
| Loan_status    | Whether a loan is paid off on in collection                                           |
| Principal      | Basic principal loan amount at the                                                    |
| Terms          | Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule |
| Effective_date | When the loan got originated and took effects                                         |
| Due_date       | Since it’s one-time payoff schedule, each loan has one single due date                |
| Age            | Age of applicant                                                                      |
| Education      | Education of applicant                                                                |
| Gender         | The gender of applicant                                                               |


Training set: loan_train.csv

Test set: loan_test.csv


