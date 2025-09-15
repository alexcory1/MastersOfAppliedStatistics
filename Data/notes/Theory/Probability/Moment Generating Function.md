
Extends from [[Moment]] 
# Discrete
A Moment Generating Function (MGF) for a Discrete Random Variable Y is defined as 
$M_Y(t)=E(e^{tY})=\sum_ye^{ty}p(y)$ 

## Obtaining a [[Moment]] from a MGF
Let $M_Y(t)$ be the moment generating function for a discrete random variable 

$E(Y^r) = \left. \frac{\partial^r M_Y(t)}{\partial t^r} \right|_{t=0}$
