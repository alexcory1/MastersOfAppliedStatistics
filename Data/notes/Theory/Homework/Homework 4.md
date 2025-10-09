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

