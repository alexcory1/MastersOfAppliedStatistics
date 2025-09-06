#model-selection
[[Model Selection]] technique similar to [[AIC]] but favoring smaller models due to the heavier penalty.
More consistent model, if true model is in the candidate pool it will find it
$n*log(\frac{RSS}{N}) + p*log(n)$ 