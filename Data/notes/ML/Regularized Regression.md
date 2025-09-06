#Regression
Better prediction accuracy and model interpretability
On a normalized scale
Has an analytical solution

Intentionally introduce a little bias to decrease variance
If decrease in variance is greater than increase in bias, the test MSE will go down

[[Ridge Regression]] 
[[Lasso Regression]]

### Ridge Vs Lasso
Neither is universally better
Lasso is usually better when few predictors have meaningful impact
Ridge performs better when many meaningful predictors
Number of predictors related to response is rarely known beforehand

### Effects of Shrinkage as Lambda Increases
Regression Coefficients: 
- Ridge approaches 0
- Lasso becomes 0
Training MSE: Increases due to reduced flexibility
Test MSE: Decrease initially then increases
Bias: Higher
Variance: Lower

shrinkage_methods.r
