# Annual Customer Spend Prediction using Linear Regression


## Project Overview
This project analyzes an e-commerce dataset to predict how much a customer is likely to spend annually based on their behavior and demographics.
I built and compared multiple regression models — including Ordinary Least Squares (OLS), Ridge, Lasso, and ElasticNet — to see how regularization affects performance.


## Dataset
Source: Kaggle Dataset

Features include:
Avg. Session Length
Time on App
Time on Website
Length of Membership
And more

The target variable is Yearly Amount Spent.


## Project Steps
### Exploratory Data Analysis (EDA):
Visualized relationships between features and the target.
Checked correlations and patterns.


### Data Preprocessing:
Handled missing values (none found).
Scaled features for regularization.


### Modeling:
Trained an OLS Linear Regression model.
Applied RidgeCV, LassoCV, and ElasticNetCV to test regularization effects.
Compared MAE, MSE, RMSE scores across models.


### Residual Analysis:
Plotted residuals to check assumptions.
Verified no strong patterns → indicates good linear fit.


## Key Results
- The OLS model performed well with minimal overfitting.
- Ridge and ElasticNet gave similar results — confirming the dataset is not highly prone to multicollinearity.
- Lasso underperformed, likely due to its aggressive penalty shrinking coefficients to zero.
- The final residual plots show a good spread with no clear patterns — supporting the use of a simple linear model.


## Conclusion
A simple linear regression is appropriate for this dataset — regularization did not significantly improve performance.


## Author
Kaggle: www.kaggle.com/mauryaghogare

LinkedIn: www.linkedin.com/in/mauryaghogare

