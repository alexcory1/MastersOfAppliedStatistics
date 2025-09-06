#cross-validation

1. Let $M_0$ denote the null model, which contains no predictors.  
2. For k = 0, . . . , $p-1$  
	a. Consider all p-k models that augment the predictors in $M_k$ with one additional predictor.  
	b. Choose the best among these p-k models and call it $M_{k+1}$.  
	Here best is defined as the model with the smallest RSS.  
3. Select a best model $M_1$ , . . . , $M_p$ using cross-validated error,  
	AIC, BIC, Mallow’s $C_p$ , or adjusted R^2

[[Backwards Selection]]
[[Stepwise Selection]]
