# Kaggle House Price prediction

House Prices: Advanced Regression Techniques is a competition on Kaggle designed as an entry point for learning. Given data on 1460 house sales I train a model to predict sale prices of 1459 unlabeled house sales. General description and data are available on Kaggle at: 
https://www.kaggle.com/c/house-prices-advanced-regression-techniques. 

My current model is an ensemble of a random forest and a linear regression and is ranked in top 32% of entries. Categorical variables have been included by creating dummy variables for each of them, and I've taken logs of highly skewed numerical variables, including the target sales price, to give them a more normalised distribution.

My first model was a simple linear regression on the numeric features only, with missing values replaced by the median of that feature. The aim was to build an end-to-end pipeline as quickly as possible to get a baseline score and test submitting predictions to Kaggle.

My final model scored an RMSE of 0.12358.
