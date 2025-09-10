# Titanic-Dataset
This project predicts Titanic passenger survival using machine learning. After cleaning and analyzing the dataset, features like age, gender, and class were engineered. Models such as Logistic Regression, Random Forest, and Gradient Boosting were trained and evaluated to demonstrate classification on structured data.
Titanic Survival Prediction

This project builds a machine learning model to predict the survival of Titanic passengers based on demographic and travel information. The dataset originates from the Kaggle Titanic competition and contains attributes such as passenger class, gender, age, family size, and embarkation port.

Dataset

The dataset includes the following features:

Pclass: Ticket class (1st, 2nd, 3rd)

Name: Passenger name

Sex: Gender

Age: Age in years

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Ticket: Ticket number

Fare: Passenger fare

Cabin: Cabin number

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Survived: Target variable (0 = Did not survive, 1 = Survived)

Objective

The goal is to create a predictive model that classifies whether a passenger survived based on the given features.

Methodology

Data Cleaning: Handling missing values and dropping irrelevant columns.

Exploratory Data Analysis: Identifying relationships between survival and passenger characteristics.

Feature Engineering: Encoding categorical variables and scaling numerical features.

Model Training: Implementing and comparing multiple classifiers, including Logistic Regression, Random Forest, and Gradient Boosting.

Evaluation: Assessing model performance using accuracy and other relevant metrics.

Results

The Random Forest and Gradient Boosting models achieved strong predictive performance, outperforming baseline approaches. Feature importance analysis highlighted that passenger class, gender, and age were the most influential predictors of survival.

How to Run

Clone this repository:

git clone https://github.com/YOUR_USERNAME/titanic-ml-model.git
cd titanic-ml-model


Install dependencies:

pip install -r requirements.txt


Run the notebook or script:

jupyter notebook titanic_model.ipynb

Key Learnings

Practical handling of missing and categorical data in real datasets.

Importance of feature engineering for predictive accuracy.

Comparison of different classification algorithms on structured data.
