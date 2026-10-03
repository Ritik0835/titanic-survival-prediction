# Titanic Survival Prediction

Logistic Regression model predicting passenger survival on the Titanic dataset.

## What I did
- Cleaned missing values (Age, Embarked), dropped Cabin/Name/Ticket/PassengerId
- Encoded Sex and Embarked (one-hot)
- EDA: survival rate by sex, class, age, fare
- Trained Logistic Regression — 81% test accuracy
- Reviewed model coefficients to confirm Sex and Pclass were strongest predictors

## Tools
Python, pandas, scikit-learn, seaborn, matplotlib
