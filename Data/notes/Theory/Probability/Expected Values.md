# For Discrete Distributions
$\mu =E(Y)=\displaystyle\sum\limits_{y}y*p(y)$     

Example: Suppose you are playing a game where you flip 3 coins and earn $3 if you flip no heads, $1 if you flip 1 heads, and lose $2 if you flip 2 or 3 heads

| y    | 0   | 1   | 2   | 3   |
| ---- | --- | --- | --- | --- |
| g(y) | 3   | 1   | -2  | -2  |
| p(y) | 1/8 | 3/8 | 3/8 | 1/8 |
$E(g(Y))=\displaystyle\sum\limits_{y}g(y)p(y)$
$=3\left( \frac{1}{8} \right)+1\left( \frac{3}{8} \right)-2\left( \frac{3}{8} \right)-2\left( \frac{1}{8} \right)$ 

# For Continuous Distributions
$\mu=\displaystyle\int_{-\infty}^{\infty}g(y)(f(y)dy$ 

# General Properties
## Expected Value of Constants
EV of constants is just the constant

Constants can be pulled out of an expectation formula 
Ex.
$E(2Y)=2E(Y)$
$E(5Y^2)=5E(Y^2)$ 

## Expected Values of Sums
The expected value of sums is the sum of the expected values

$E[g_{1}(Y)+\dots+g_{k}(Y)]=E[g_{1}(Y)]+\dots E[g_{k}(Y)]$

Ex.
$E[2Y+Y^2+2]=2E[Y]+E[Y^2]+2$ 