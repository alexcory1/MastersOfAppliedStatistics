1. Suppose a continuous random variable Y has the p.d.f.:  
$$
f (y) =  
\begin{cases}
cy, &  0 ≤ y ≤ 2\\  
0,  & elsewhere \\
\end{cases}
$$
(a) Find the value of c that makes f (y) a probability density function.  

$\int_0^2ctdt=1$
$\frac{ct^2}{2}|_{0}^{2}=1$
$\frac{c2^2}{2}-\frac{c0^2}{2}=1\Rightarrow2c=1 \Rightarrow c=\frac{1}{2}$

( b) Find P (0.5 ≤ Y ≤ 1.5) using f (y).

$\int_{\frac{1}{2}}^{\frac{3}{2}}\frac{1}{2}ydy$

$\frac{1}{2}\int_{\frac{1}{2}}^{\frac{3}{2}}ydy$

$\frac{y^2}{4}|^{\frac{3}{2}}_{\frac{1}{2}}$ 

$\frac{\frac{3}{2}^2}{4}-\frac{\frac{1}{2}^2}{4}$

$\frac{1}{4}(\frac{3}{2}^2-\frac{1}{2}^2)$

$\frac{1}{2}$

(c) Find F (y).  

$F(y) = \int_{-\infty}^yf(t)dt=\int_{-\infty}^00dt+\int_0^2\frac{1}{2}tdt+\int^{\infty}_20dt$

$$
F(y) = 
\begin{cases} 
0, & y < 0 \\
\dfrac{y^2}{4}, &  0 \leq y \leq 2 \\
1, & y > 2
\end{cases}
$$

(d) Find P (1 ≤ Y ≤ 2) using F (y).  

P (1 ≤ Y ≤ 2) = $\frac{2^2}{4}-\frac{1}{4}=1-\frac{1}{4}=\frac{3}{4}$

(e) Find y so that P (Y ≤ y) = 0.3  

$\frac{y^2}{4}=.3$
$y^2=1.2$
$y=\sqrt{1.2}$

(f) Find y so that P (Y > y) = 0.55.  

$$
\begin{align}
1-\frac{y^2}{4}=.55\\ 
\frac{y^2}{4}=.45 \\
y^2=4*.45 \\
y=\sqrt{4(.45)} \\
y=\sqrt{1.8}
\end{align}
$$

(g) Find E(Y ).  

$$
\begin{align} \\
\int_{-\infty}^\infty tf(t)dt=\int_{-0}^y t \frac{t}{2}dt=\int_{0}^y \frac{t^2}{2}dt=\frac{y^3}{6}\Big|_{0}^2=\frac{8}{6}-0=\frac{4}{3}
\end{align}
$$


(h) Find V (Y ).

$$
\begin{align} \\
E(Y^2)=\int_{-\infty}^\infty t^2f(t)dt=\int_{0}^y t^2 \frac{t}{2}dt=\int_0^y \frac{t^3}{2}dt=\frac{y^4}{8} \Big |_0^2=\frac{2^4}{8}-0=\frac{16}{8}=2 \\
V(Y)=E(Y^2)-E(Y)^2=2-\left( \frac{4}{3}\right)^2=\frac{2}{9}
\end{align}
$$




2. A supplier of kerosene has a 150-gallon tank that is filled at the beginning of each week. His weekly demand shows a relative frequency behavior that increases steadily up to 100 gallons and then levels off between 100 and 150 gallons. If Y denotes weekly demand in hundreds of gallons, the relative frequency of demand can be modeled by  

$$
f (y) = 
\begin{cases}
   
y, &  0 ≤ y ≤ 1\\  
1, &  1 < y ≤ 1.5 \\ 
0, &  \text{elsewhere}  
\end{cases}
$$
(a) Find F (y).  

$$
F(y)=
\begin{cases} \\
0, & y<0
\\
\int_0^ytdt=\frac{y^2}{2}, & 0 \leq y \leq 1\\ 
\int_0^1tdt+\int_1^y1dt=\frac{t^2}{2}\Big |_0^1+t\Big |_1^y=\frac{1}{2}+(y-1)=y-\frac{1}{2}, & 1<y\leq 1.5\\
1, & y>1.5
\end{cases}
$$

(b) Find P (0 ≤ Y ≤ 0.5).  

$\frac{\frac{1}{2}^2}{2}=\frac{1}{8}$

(c) Find P (0.5 ≤ Y ≤ 1.2).  

$1.2-.5-\frac{.5^2}{2}=.575$

(d) Find y so that P (Y ≤ y) = 0.25  

$\frac{y^2}{2}=.25$
$y^2=.5$
$y=\sqrt{.5}$

(e) Find y so that P (Y > y) = 0.25  

$P(Y>y)=1-P(Y\leq y) = 1-F(y) = 1-.25=.75$
$y-\frac{1}{2}=.75$
$y=1.25$
(f) Find E(Y ).  

$E(Y)=\int_0^1t^2dt+\int_1^{1.5}tdt=\frac{t^3}{3}\Big|_0^1+\frac{t^2}{2}\Big|_1^{1.5}=\frac{1}{3}-0+\frac{1.5^2}{2}-\frac{1}{2}=\frac{1}{3}+\frac{1.25}{2}=\frac{2}{6}+\frac{3.75}{6}=\frac{5.75}{6}$

(g) Find V (Y ).

$E(Y^2)=\int_0^1t^3dt+\int_1^{1.5}t^2dt=\frac{t^4}{4}\Big|_0^1+\frac{t^3}{3}\Big|_1^{1.5}=\frac{1}{4}-0+\frac{1.5^3}{3}-\frac{1}{3}=\frac{1}{4}+\frac{3.375}{3}-\frac{1}{3}=\frac{3}{12}+\frac{13.5}{12}-\frac{4}{12}=\frac{12.5}{12}$
$V(Y)=\frac{12.5}{12}-\frac{5.75}{6}^2=\frac{71}{576}$


3. Let the random variable Y have a Uniform distribution with $θ_1 = 0$ and $θ_2 = 1$. Show that  
P (a ≤ Y ≤ a + b) for a ≥ 0, b ≥ 0, a + b ≤ 1 depends only on the value of b.

$\int_a^{a+b}=f(t)dt=\int_a^{a+b}1dy=(a+b)-a=b$


4. As a measure of intelligence, mice are timed when going through a maze to reach a reward of food.  The time (in seconds) required for any mouse is a random variable Y with a density function given by  

$$
f (y) =  
\begin{cases}
\frac{60}{y^2}, &  y ≥ 60\\  
0, &  elsewhere \\
\end{cases}\\
$$
where 60 seconds is the minimum possible time needed to traverse the maze.  

(a) Show the p.d.f. f(y) has the properties of a probability density function.  

$$
\begin{align}
\text{Total Probability = 1: }\int_{-\infty}^{\infty}tdt=\int_{60}^y \frac{60}{t^2}dt=60\int_{60}^\infty t^{-2}=60(-y)^{-1}\Big|_{60}^{\infty}=60(0-\left( -\frac{1}{60} \right)=1\\

\text{Non-Negative: } 
\begin{cases} \\
0\geq0,\\
\frac{60}{y^2} >0,\forall y > 60 &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &  &      
\end{cases}
\end{align}
$$

(b) Find P (Y > 60 + c) for a positive constant c.  

$$
\begin{align}
P(Y > 60 + c) 
  &= \int_{60 + c}^{\infty} \frac{60}{y^2}\,dy \\
  &= 60 \int_{60 + c}^{\infty} y^{-2}\,dy \\
  &= 60-y^{-1}\Big|_{60 + c}^{\infty} \\
  &= 60(0 - (-\frac{1}{60 + c})) \\
  &= \frac{60}{60 + c}
\end{align}
$$



(c) Show E(Y), the expected number of seconds required to reach the reward, is infinite.

$E(Y)=\int_{60}^\infty t\frac{60}{t^2}dt=\int_{60}^\infty 60t^{-1}dt=60ln(t)\Big|_{60}^\infty=60ln(\infty)-60ln(60)=\infty$

(d) Find the distribution function F (y) for the random variable Y.
$F(y)=\int_{60}^y f(t)dt=\int_{60}^y60t^{-2}=60\int_{60}^yt^{-2}=60(-t^{-1})\Big|_{60}^y=-\frac{60}{t}\Big|_{60}^y=-\frac{60}{y}-\left( -\frac{60}{60} \right)=-\frac{60}{y}+1=1-\frac{60}{y}$
(e) Use R to generate 10,000 observations of the random variable Y. Find the minimum and maximum values for these 10,000 observations. What do you notice about your values?  

Using inverse transform sampling:
$Y=F^{-1}(U), u=1-\frac{60}{y}, y=\frac{60}{1-u}$

```
n <- 10000
U <- runif(n)
Y <- 60 / (1 - U)

min(Y)
max(Y)
```

Max Y = 524084.3
Min Y = 60.00662

(f) Make a histogram for your 10,000 observations. How would you describe this histogram?  

![[Pasted image 20251010021609.png]]

Using a logarithmic scale for visibility due to outliers, we can see that the distribution has an extreme right skew centered around 60 (log(60) in the case of the graph above).

(g) Find the mean of these 10,000 observations. How do you explain the discrepancy between the infinite theoretical mean and the mean of your 10,000 observations?

Mean: 606.4281


The tail as y approaches infinity is extremely heavy, which causes the integral to diverge, but the finite sample causes a non-infinite sample mean. A larger sample size would cause an arbitrarily large sample mean.

Another reason is a technical limitation with R and computers being unable to generate truly infinite numbers, due to R's 64-bit double limit.


5. Wires manufactured for use in a certain computer system are specified to have resistances between 0.12 and 0.14 ohms. The actual measured resistances of the wires produced by Company A have a normal distribution with a mean of 0.13 ohm and a standard deviation of 0.005 ohm.  

(a) What is the probability that a randomly selected wire from Company A’s production will meet the specifications?  

```
pnorm(.14, .13, .005) - pnorm(.12, .13, .005)
```

0.9544997

(b) If four such wires are used in the system and all are from Company A, what is the probability  
that all four will meet the specifications?

$0.9544997^4=0.830048$ 

6. A soft drink machine can be regulated so that it discharges an average of μ ounces per cup. If the ounces of fill are normally distributed with standard deviation equal to 0.3 ounce, give the setting for μ so that 8-ounce cups will overflow only 1% of the time.

$\frac{8-\mu}{.3}=z_{.99}\Rightarrow -\mu=.3z_{99}-8\Rightarrow\mu=8-.3z_{.99}$

```
mu = 8-(qnorm(.99)*.3)
```
7.302096


7. The weekly amount of down time Y (in hours) for an industrial machine has a gamma distribution with α = 3 and β = 2.  

(a) Find the probability the machine will be down for more than 3 hours.  

$P(Y>3)=1-P(Y<3)$
```
> 1 - pgamma(3, shape = 3, scale = 2)
[1] 0.8088468
```

(b) For 95% of all weeks, the machine will be down less than how many hours?  

```
> qgamma(0.95, shape = 3, scale = 2)
[1] 12.59159
```

(c) The loss (in dollars) to the industrial operation as a result of down time is the function L =  
$30Y + 2Y^2$. Find the expected loss.

$E(Y)=\mu=\alpha\beta=6$
$V(Y)=\alpha\beta^2=3*2^2=3*4=12$
$E(Y^2)=V(Y)+E(Y)^2=12+36=48$
$E(L)=30(6)+2(48)=180+96=276$


8. Explosive devices used in mining operations produce nearly circular craters when detonated. The radii of these craters are exponentially distributed with a mean of 10 feet.  

(a) Find the probability that one of these explosive devices will produce a radii between 6 and 12 
feet.  

$P(6\leq Y\leq12)=P(Y<12)-P(Y<6)$

```
> pexp(12,1/10)-pexp(6,1/10)
[1] 0.2476174
```

(b) Find the probability that an explosive device will produce an area larger than 64π ft2.  
radius = 8
$P(Y>8)=1-P(Y<8)$
```
> 1-pexp(8,1/10)
[1] 0.449329
```

(c) Find the 75th percentile of the distribution of the areas produced by the explosive device.  
radius:
```
> qexp(.75, 1/10)
[1] 13.86294
```
area:
$\pi*13.86294^2=603.7547$


9. During an eight-hour shift, the proportion of time Y that a sheet-metal stamping machine is down for maintenance or repairs has a Beta distribution with α = 1 and β = 2.  

(a) Find the probability that machine will be down between 20% and 60% of the time.  

```
> pbeta(0.6, shape1 = 1, shape2 = 2) - pbeta(0.2, shape1 = 1, shape2 = 2)
[1] 0.48
```

(b) Find the expected proportion of time the machine will be down for maintenance or repairs.  
$E(Y)=\frac{\alpha}{\alpha+\beta}=\frac{1}{3}$
(c) Find the variance of the proportion of time the machine will be down for maintenance or repairs.
$V(Y)=\frac{\alpha\beta}{(\alpha+\beta)^2(\alpha+\beta+1)}= \frac{1}{18}$
