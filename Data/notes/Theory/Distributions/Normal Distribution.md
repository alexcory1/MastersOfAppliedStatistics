Denoted as $N(\mu,\sigma^2)$
Shape:
* Unimodal Bell-Shaped
* Symmetric around $\mu$ 

Mean:
* Parameter $\mu$
* Location of Symmetry

Variance:
* Parameter $\sigma^2$
* Controls variability of curve


### Empirical Rule
About 68% of observations within one standard deviation
95% within 2
99.7 within 3
ex. 
$\mu=52.5, \sigma^2=1.44,$
$68\%:  \mu-\sigma=52.5\pm1.2=(51.3,53.7)$ 
$95\% \mu-2\sigma=52.5\pm 2(1.2)=(50.1,54.9)$


### MGF

$M_Y(t)=e^{\mu t+1/2t^t\sigma^2}$
ex.
$\mu=65,\sigma^2=6.25$
$e^{65t+1/2t^2*6.25}$


### CDF
$F(y)=P(Y\leq y)=\int_{-\infty}^yf(t)dt=\int_{-\infty}^y\frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{(t-\mu)^2}{2\sigma^2}}$ 

No closed form solution, use R  

Probabilities:
pnorm($y,\mu,\sigma$)

Quantiles:
$qnorm(\%ile, \mu,\sigma)$ 

## Standard Normal (z distribution)
$\mu=0,\sigma^2=1$
$f(z)=\frac{1}{\sqrt{2\pi}}e^{z^2/2}$


Let Y have a normal distribution with mean $\mu$ and variance $\sigma^2$
$Z=\frac{Y-\mu}{\sigma}$ will have a standard normal distribution

Let Z have a standard Normal distribution, then
$Y=\mu+\sigma*Z$ 