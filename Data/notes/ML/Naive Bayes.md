Foundational Material:
[[Bias-Variance Tradeoff]], [[Bayes Theorem]]

This is a [[Regularized Regression]] model

Assumptions:
- Within kth class, assume predictors are conditionally independent of one another

Why is this meaningful:
- Normally we would have to deal with marginal and joint distributions
- Here we only care about marginal distributions

What's the catch?
- We don't really believe this assumption, but it still gives somewhat good results, thus it is a  naive assumption

Introduces some bias but reduces some variance

### Advantages:
Excels with qualitative predictors because normality does not apply

When n is not large relative to p, naive Bayes out performs [[LDA]] and [[QDA]]. 

### Homework Examples
Homework 8
Question 2g: Code