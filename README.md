# Loan Default Recommendation
This project aims to predict the probability that a person is going to default on a loan.
The project uses three datasets sourced from the internet.
For the recommendation only one dataset is used because of the features that were convienient for the recommendation process

The recommendation process took into acount various things but mostly focused on the predicted value of whether a person would default on a loan or not. If a person did not default the loan application was accepted otherwise a lower loan amount is recommended

## Steps taken in the project

1. Data Cleaning - dealing with missing values.
2. Preparing the data for modelling - preprocessing (one hot encoding categorical values), correlations
3. Feature selection using Lasso Regression
4. Standardising the data.
5. Dealing with imbalanced dataset - oversampling and undersampling
6. Feature reduction/dimensionality reduction using PCA 
7. Modelling - models used include: Logistic Regression, Decision Trees and a Tensorflow model
8. Prediction on test data.
9. Loan Recommendation.  

## Future Works
Use a machine learning model for the recommendation.
