
The basis for a random variable w/ a Bernoulli or Binomial Distribution is:
- A random trial with only two possible outcomes, called a success or failure
- Probability of success = p
- Since there are only two outcomes, probability of failure = 1-p = q
- P(S)=p, P(F)=q

A Bernoulli Random Variable is defined as Y=1 if trial is a success, otherwise 0


# Binomial Random Variable
A Binomial Random Variable Y is defined as the number of successes in n independent identical trials of this random event

Example:
- Let Y be the number of heads in 10 flips of a coin
	- n=10,p=.5

The probability mass function of a Binomial Random Variable Y is:
$p(y)=\binom{n}{y}p^yq^{n-y}$
where y is the number of successes
## Moments
Mean of Y: $\mu = E(Y) = np$
Variance of Y: $\sigma^2 = V(Y) = npq$
MGF of Y: $M_Y(t)=(pe^t+q)^n$
# Bernoulli Random Variable
The probability mass function for a Bernoulli Random Variable Y is:
$p^yq^{1-y}$
where y is the probability of success
## Moments
Mean of Y: $\mu =E(Y) = p$
Variance of Y: $\sigma^2=V(Y)=pq$
MGF of Y: $M_Y(t)=pe^t+q$

## Parameters
Parameters for a random variable are values that completely determine the PMF for the distribution

- Bernoulli RV
	- Probability of success = p
- Binomial RV
	- Number of trials = n
	- Probability of Success = p

