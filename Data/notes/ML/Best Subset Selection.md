Best subset selection is an exhaustive form of [[Model Selection]] used in [[Regression]]

1. For all K=1...p
		a. fit all ${p}\choose{k}$ models that contain exactly k predictors (fit all models of each # of selector)
		b. pick the best model (Smallest [[RSS]]) among these, call it $M_k$.
2. For $M_1, ...,  M_k$ 
		a. Select best of "candidate models" 

This is an exhaustive search, and will give the optimal model
This **cannot** be used on models with large predictors due to computational intensity. (np-hard)