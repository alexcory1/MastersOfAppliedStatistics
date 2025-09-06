#Regression
Least Absolute Selection and Shrinkage Operator
Type of [[Regularized Regression]]
Resolves disadvantages of Ridge Regression
Performs selection and regularization

$\hat\beta^{lasso} = min_{\hat{\beta}}(||Y-X\hat{\beta}||^2_2 + \lambda ||\beta||_1)$  

Lasso has no closed form analytical solution
Bias at $\lambda$ = 0 = 0
Variance at $\lambda = \infty = 0$
Select optimal $\lambda$ using [[Cross-Validation]]
Lasso assumes some coefficients truly equal 0

Able to set some coefficients = 0 because the constraint region is a diamond in lasso,
Whereas in [[Ridge Regression]], the squared penalty term almost acts to smooth the constrained region into a circle.