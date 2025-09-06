#model-selection

Intuition: Each model has to pay a penalty to be in the model
If the decrease in RSS is enough to offset the price it gets to be in the model, and our criterion will be larger

When p is small use exhaustive search ([[Best Subset Selection]])
when p is large (p $\geq$ 30) we use greedy algorithms ([[Forward Selection]]/[[Backwards Selection]] or [[Stepwise Selection]])




With the exception of Adjusted $r^2$, the following models aim to minimize [[RSS]]
Add a penalty for the number of predictors to compensate for adding a predictor
Models:
[[AIC]] = $n*log(\frac{RSS}{N}) + 2p$ 
[[BIC]] = $n*log(\frac{RSS}{N}) + p*log(n)$ 
[[Adjusted r2]] 
[[Mallow's CP]] = $\frac{RSS}{\sigma^2} - n + 2p$ 
