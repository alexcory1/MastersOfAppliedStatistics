A Continuous random variable Y is a random variable whose possible values are in an interval  
of the real line.  

Unlike a Discrete random variable, there are infinitely many possible values for a Continuous  
random variable Y.  


## Probability Density Function:
$P(a<Y<b)=\int_{a}^b f(y)dy$ 

### Properties
Let Y be a Continuous Random Variable with CDF F(y) and PDF f(y)
* for all PDFs f(y)
	* $f(y)=\frac{\partial F(y)}{\partial y}$
	* For all but a finite number of values y. These values of y are located at any discontinuity points of the function f(y).
	* For all y, f (y) ≥ 0
	* For all PDFs f (y),
		* $\int_{-\infty}^{\infty}f(y)dy=1$

## Cumulative Distribution Function:
$F(y)=P(Y\leq y)\int_{-\infty}^yf(t)dt. \forall y$ 

### Percentiles of Y
CDF can be used to find percentiles of Y
The pth percentile of Y is the value of y such that
$P(Y\leq y)=F(Y)=p$

ex. 
$F(Y)=.25$
$\frac{1}{8}y^3=.25$
$y^3=2$
$y=2^{1/3}$ 


## Properties
Let Y be a Continuous Random Variable with cdf F(y) and pdf f(y)
* F(Y) is continuous everywhere in y
* For all values of y, $0\leq F(y)\leq1$
* Limit approaching $-\infty$ is 0, positive infinity is 1
* F(y) is a non-decreasing function in y
* $\forall a,b. a<b,P(a\leq Y \leq b)=F(b)-F(a)$
*
