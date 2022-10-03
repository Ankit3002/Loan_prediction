# Loan_prediction

In this repository I have created a loan prediction model using logistic regression .
I have taken the dataset from kaggle which I have 23 independent attributes and 1 dependent attribute.
The dependent attribute is binary class with y or n ( y-- whether the person is eligible for loan and n-- whether that person is defaulter or not ).

First I have done some preprocessing on dataset.
And than filled the missing values of attributes using mean , median and mode.
Mean and median are used for numerical data.
Mode is used for Categorical data.

than logistic Regression model is built for Prediction
The accuracy of the model is 76%
pred_out is the List which contains Y and N values.
Y -- Eligible person for loan
N -- Defaulter person 
