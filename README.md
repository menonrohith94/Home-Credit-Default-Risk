# Home-Credit-Default-Risk
Predicting how capable each applicant is of repaying a loan (Kaggle Challenge).

# Getting Started
Insufficient or non-existent credit records make it difficult for many people to get loans. Unfortunately, untrustworthy lenders frequently take advantage of this group.

By delivering a pleasurable and secure borrowing experience, Home Credit aims to increase financial inclusion for the unbanked. Home Credit uses a range of alternative data, such as telecom and transactional information, to anticipate their clients' repayment capacities in order to ensure that this underserved demographic has a favorable lending experience.

While Home Credit is presently making these predictions using a variety of statistical and machine learning approaches, they are pushing Kagglers to help them realise the full potential of their data. As a result, customers who are competent of repayment will not be turned down, and loans will be issued with a principal, maturity, and repayment schedule that will enable their clients to succeed.

https://www.kaggle.com/c/home-credit-default-risk
The goal of this competition is to forecast whether or not a borrower will be able to repay a loan using prior loan application data. This is an example of a typical supervised classification task:

Supervised: The labels are included in the training data and the goal is to train a model to learn to predict the labels from the features.

Classification: The label is a binary variable, 0 (will repay loan on time), 1 (will have difficulty repaying loan)

Various algorithms were used to identify loan defaulters in
this paper. To start with, we handled missing values by identifying their appropriate types such as NMAR/MCAR/MAR and
eliminated only those variables which were found to be highly
correlated with each other, using an appropriate statistical test.
We then analysed the outliers and treated multicollinearity
among the variables by calculating their VIF scores. Further
to reduce the dimensionality of the data we applied the
FAMD technique as there was a combination of multiple
quantitative and qualitative variables. At last, before predictive
analysis, we handled the imbalanced target column using
SMOTE analysis

We evaluated multiple Machine Learning
models in two different stages as mentioned in the evaluation
section of this paper. Logistic Regression, Neural Networks
and Extreme Gradient Boosting (XGB) were used to achieve
the best results. In comparison to Logistic Regression, the
Gradient Boosting technique produces better results. Further,
from the overall research, these models can be used to make
better judgements about loan applications, potentially saving
a financial institution from massive losses.Various algorithms were used to identify loan defaulters in
this paper. To start with, we handled missing values by identifying their appropriate types such as NMAR/MCAR/MAR and
eliminated only those variables which were found to be highly
correlated with each other, using an appropriate statistical test.
We then analysed the outliers and treated multicollinearity
among the variables by calculating their VIF scores. Further
to reduce the dimensionality of the data we applied the
FAMD technique as there was a combination of multiple
quantitative and qualitative variables. At last, before predictive
analysis, we handled the imbalanced target column using
SMOTE analysis and we evaluated multiple Machine Learning
models in two different stages as mentioned in the evaluation
section of this paper. Logistic Regression, Neural Networks
and Extreme Gradient Boosting (XGB) were used to achieve
the best results. In comparison to Logistic Regression, the
Gradient Boosting technique produces better results. Further,
from the overall research, these models can be used to make
better judgements about loan applications, potentially saving
a financial institution from massive losses.

## Installing
Clone this repository and explore jupyter notebook file.
The required libraries installation are mentioned in the file.

## Running
Navigate inside the "Home-Credit-Default-Risk" folder and run jupyter notebook.
If you are unable to access the dataset from the id given, kindly download the dataset from the kaggle and link it with the jupyter notebook.

# Running the notebook
Jupyter Notebook - Project Jupyter exists to develop open-source software, open-standards, and services for interactive computing across dozens of programming languages.
scikit-learn - Machine Learning in Python.
Pandas - pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.
etc

# License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Acknowledgments
Sumit Khopkar

Sagar Ramachandra Murthy

Chinmaya Kaundanya