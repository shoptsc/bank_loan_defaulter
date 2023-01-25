# Bank Loan Default Prediction with Machine Learning

# Introduction
Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.

It is a classification problem where we have to predict whether a loan would be approved or not. In a classification problem, we have to predict discrete values based on a given set of independent variable(s).

# Dataset
For this practice problem, we have been given three CSV files: train, test and sample submission.

- Train file will be used for training the model, i.e. our model will learn from this file. It contains all the independent variables and the target variable.
- Test file contains all the independent variables, but not the target variable. We will apply the model to predict the target variable for the test data.

## Steps that I followed :
>Firstly I import the test.csv and train.csv using pandas.read_csv()

> Performed EDA 
> Data Preprocessing i.e. missing data removal, onehotencoding

>Then i applied different machine learning models:
-   Logistic Regression
-   Random Forest
-   SVC
-   Decision Tree

> Random Forest is giving the best accuracy of 75%

# Tool:

 - Jupyter
