Gamma and Exponential Distributions
* Used to model continuous positive values who's distribution is right skewed

Chi-Square Distribution
* Plays an important role in Theory
* Connections to Normal, t, F distributions

A random variable Y with a Gamma distribution with parameters $\alpha$ and $\beta$ has the PDF 
$f(y)=\frac{y^{\alpha-1}e^{-y/\beta}}{\beta^\alpha\gamma(\alpha)}$, where $\gamma(\alpha)=\int_0^\infty y^{\alpha-1}e^{-y}dy$

$\alpha>0$, shape parameter
$\beta>0$, scale parameter

Properties of Gamma Distribution
Shape:
* Skewed right
* Alpha controls amount of skew
* As alpha increases, distribution becomes more symmetric

mean = $\alpha \beta$
variance = $\alpha \beta^2$ 


#### MGF
$M_Y(t)=(1-\beta t)^{-\alpha}$

#### Gamma CDF
$F(y) = P(Y\leq y)=\int_0^yf(t)dt=\int_0^y\frac{t^{\alpha-1}e^{-t/\beta}}{\beta^\alpha\gamma(\alpha)}dt$
No good closed for solution for most values
Use R

Probabilities: pgamma(y,alpha,1/beta)
Percentiles: qgamma(p,alpha,1/beta)


# Exponential Distribution
A r.v. Y with an Exponential Distribution with parameter $\beta$ has the pdf
$f(y)=\frac{1}{\beta}e^{-y/\beta}$ where y > 0
$\beta = \mu=\sigma$ 
$\sigma^2=\beta^2$
Same as gamma distribution, with alpha = 1
Always the same shape


CDF:
$F(Y)=P(Y\leq y)= \int_0^yf(t)dt=\int_0^y\frac{1}{\beta}e^{-t/\beta}dt$

Percentiles: $P(Y\leq y) = 1-e^{-y/\beta}=p \Rightarrow y=-\beta ln(1-p)$

Probabilities: pexp(y,1/beta)
Percentiles: qexp(p,1/beta)

# Chi-Square Distribution
A rv Y with a ChiSq distribution with the parameter $\nu$ has the pdf 
$f(y)=\frac{y^{\nu/2-1e^{-y/2}}}{2^{\nu/2\gamma(\nu/2)}}$
$\gamma(\frac{\nu}{2})=\int_0^\infty y^{\nu/2-1}e^{-y}dy$

Parameters:
$\nu$ = degrees of freedom (n-1)

Gamma Distribution with $\alpha=\frac{\nu}{2}, \beta=2$
Denoted as $\chi^2_\nu$

Shape: Skewed right 
As nu increases, distribution becomes more symmetric
$\nu=\mu$
$2\nu=\sigma^2$