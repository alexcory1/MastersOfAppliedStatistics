• One of the most important techniques in all of data  
science/statistics.  
• Widely applicable, extremely powerful, computationally  
intensive.  
• Literally involves just resampling from the data.  
• No distributional assumptions.  
• Sample size cannot be too small.

Inference: Assume normality



Algorithm:
For 1:B, where B is a large number
Draw n observations with replacement to be the training set
Compute estimate

SE($\hat{\beta}_1$) = $\sqrt{\frac{1}{B-1}\Sigma_{b=1}^B (\hat{B}_1^{(b)}- \overline{B}_1})^2$ 


Homework examples:
HW7:
Problem 1: Code
Problem 2: Properties
