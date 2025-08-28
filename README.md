# World-Happiness-Ratings Predictive Modeling using WHR2023 dataset
# About the Dataset:
The World Happiness Report is an annual publication that gives rankings based on happiness levels.
The dataset aims to provide insights into the factors that contribute to happiness.
The dataset allows for comparative analysis of happiness.
# Objective: 
To predict the next top 10 using Machine Learning Models.
# Methodology:
1. Correlation Analysis – to determine the relationship between two or more variables and whether they are related and, if so, how strongly.
2. Scatter Plots -  to visualize the correlation between two continuous variables.
3. Multiple Linear Regression - to model the relationship between one dependent variable and two or more independent variables.
4. Residual Plot – to show the graphical representation used in regression analysis to assess the goodness of fit of a model.
5. Q Plot – The QQ (quantile-quantile) plot compares the sample quantiles to the theoretical quantiles of a normal distribution. 
6. Heteroscedasticity test - for validating the assumptions of regression models, ensuring the efficiency of estimates, and improving the accuracy of inference.
7. Forecasting - to predict the top 10 happiest countries for next year.
# Results:
1. Linear Regression: Cross-validated MSE is 0.224, looks like it is the best fit model. It suggests that the linear model is capturing the underlying patterns in the data effectively.
2. Ridge Regression: Cross-validated MSE is 0.227, which is very close to the linear regression model. This indicates that Ridge regression is also a good fit for the data, and it might be beneficial if we have concerns about overfitting, as Ridge regression adds a penalty to the coefficients.
