# House Price Prediction
> Predicts the price of house (lasso and ridge models)


## Table of Contents
* Python File - Containing python code
* PDF file - containing the subjective questions

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Predicting house price using Advanced Regression techniqics.
- Predict using Linear Regression and Multi Linear Regression
- Predict using Lasso and Ridge models

## Conclusions
- From regular LR model there was a lot of multi collinearity between the features though the RSquare of train and test are nearly 90 but this model cannot be dependent for future use. Nearly 100 features after RFE so removing features manually after this is tough one, so applied advanced regression techniqics.
- Got optimal Ridge model with alpha=2.
- Got optimal Lasso Regression model with alpha =0.001. Used this model for prediction as it has not only penalised the coefficients but also eliminated some of the features.
