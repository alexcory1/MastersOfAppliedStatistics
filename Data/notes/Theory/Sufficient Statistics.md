#Statistics
Prerequisite: [[Factorization Theorem]]
Useful for 
[[Maximum Likelihood Estimate]]
[[Rao-Blackwell Theorem]]


A statistic T(X) is sufficient for a parameter $\theta$ if $f(X) = g(T(X)| \theta ) * h(X)$ 
- Try to separate the X's and $\theta$'s as much as possible
- Drag $\theta$ to left, and X to right whenever possible
- Any X's remaining on the left become sufficient statistics

## Example:
Binomial:
- The probability of observing $x_1$ successes in the first $n_1$ trials, $x_2$ successes in the next $n_2$ trials, and $x_3$ successes in the first $n_3$ trials.

${{n_1}\choose{x_1}}\theta ^{x_1}(1-\theta)^{n_1-x_1} * {{n_2}\choose{x_2}}\theta ^{x_2}(1-\theta)^{n_2-x_2} * {{n_3}\choose{x_3}}\theta ^{x_3}(1-\theta)^{n_3-x_3}$ 

Separate

$\theta^{x_1}(1-\theta)^{n_1-x_1} * \theta^{x_2}(1-\theta)^{n_2-x_2} * \theta^{x_3}(1-\theta)^{n_3-x_3} * {{n_1}\choose{x_1}}{{n_2}\choose{x_2}}{{n_3}\choose{x_3}}$ 

Group

$\theta^{x_1+x_2+x_3}(1-\theta)^{n_1+n_2+n_3-(x_1+x_2+x_3) }*{{n_1}\choose{x_1}}{{n_2}\choose{x_2}}{{n_3}\choose{x_3}}$ 

Because there is no way to factor out the $x_1+x_2+x_3$, we can call this T = T(X) = $\Sigma_{i=1}^{3}X_i$ .
This is a sufficient statistic

### Explanation
- If I know the number of successes, that tells me everything about the probability of success. I don't need to know about the order of what occurred, or how the successes and failures were distributed among the various trials
