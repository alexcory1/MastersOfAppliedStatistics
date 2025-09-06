

 Type of [[Cross-Validation]] where data set is split into k groups, called folds, then use all but one fold as training set and the one left out as the test set. 
 Functions very similarly to [[Leave One Out Cross Validation]], but uses groups of values instead of each individual value, meaning we go from running n times to k times.
$CV_k = \frac{1}{k} \Sigma_1^k test MSE_k$ 