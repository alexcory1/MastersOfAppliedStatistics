Linear Discriminant Analysis

$$δ(x)= x_1 \frac{\mu_k}{\sigma^2} - \frac{\mu_k}{2\sigma^2}+log(\pi_k)$$
$$ \delta(x) = x\frac{5.1-3.4}{4}-\frac{5.1-3.4}{8}+log(.68/.32)$$





LDA us a type of [[Regularized Regression]] similar to [[QDA]], but a simpler model. This is rarely used, but can be sometimes due to the [[Bias-Variance Tradeoff]].


```
library(MASS)

lda_model <- lda(Direction ~ Lag2, data = data_2008)
lda_predictions <- predict(lda_model)
lda_table <- table(lda_predictions$class, data_2008$Direction)
```

Assumptions:
The values of each predictor variable are normally distributed, and have equal variance. We control variance by regularizing the scale.



Homework Problems:
HW8:
Question 1: Concept review
Question 2e: Code


Resources
[IBM](https://www.ibm.com/topics/linear-discriminant-analysis)

