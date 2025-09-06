#Regression

Foundational material:
[[Regularized Regression]], [[Bias-Variance Tradeoff]], [[Cross-Validation]]

Foundational for:
[[Lasso Regression]]


Coefficients must be standardized before ridge can be done
$(X^TX+\lambda I)^{-1}$ always exists, no multicollinearity issues with perfect correlation
Shrinks coefficients towards 0, but never to 0.
Ridge is not good for inference

Goal of Ridge regression is to select the best value for lambda, which controls the tradeoff between fit and shrinkage.
Each lambda will give a different set of coefficient estimates

$\beta ^R$ is biased because of the injected bias 
Penalty term is not added to intercept




 $\beta^{\text{R}} = \underset{\beta}{\min} \left( \sum_{i=1}^{n} \left( y_i - X_i \beta \right)^2 + \lambda \sum_{j=1}^{p} \beta_j^2 \right)$

$E(\hat{\beta}^R) = (X^TX+\lambda II)^{-1}X^TYX\beta$ 
$var(\hat{\beta}^R) = \hat{\sigma}^2 (X^TX+\lambda I)^{-1} X^TX(X^TX+\lambda I)^{-1}$ 

To select lambda:
choose a grid of lambda values
compute [[Cross-Validation]] error for each value of lambda
select smallest value
refit model using all data, this is the final model