#model-selection 
Type of [[Model Selection]] used when p (# of predictors) is large.
Greedy Algorithm
Find best model based on current information, good approximation but not always the best.
Do not consider all possible options
May lead to suboptimal result


[[Forward Selection]] Algorithm:  
1. Let $M_0$ denote the null model, which contains no predictors.  
2. For k = 0, . . . , $p-1$  
	a. Consider all p-k models that augment the predictors in $M_k$ with one additional predictor.  
	b. Choose the best among these p-k models and call it $M_{k+1}$.  
	Here best is defined as the model with the smallest RSS.  
3. Select a best model $M_1$ , . . . , $M_p$ using cross-validated error,  
	AIC, BIC, Mallow’s $C_p$ , or adjusted R^2

[[Backwards Selection]] Algorithm:
Same as Forward selection, but we start with the full model and remove predictors one at a time


[[Hybrid Selection]] Algorithm:
• Best subset, forward, and backward stepwise will generally  
give similar but not identical models.  
• An alternative is a hybrid version of forward/backward  
selection: stepwise selection.  
• At each step, you are not restricted to one direction. You can  
add and remove predictors.  
• Stepwise selection attempts to mimic subset selection while  
still retaining computational advantage.


### Which algorithm?
If you want to do prediction and can have a more complicated model, use backwards selection
If you want a simpler model, use forward selection.
High dimensional data (p > n) use forward

The two models will generally get similar results, but not typically the same model