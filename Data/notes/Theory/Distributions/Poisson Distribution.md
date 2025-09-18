Used to model the random variable Y=number of events that occur in a given dimension (space, time, volume)

Poisson distribution has broad applications to many areas
Must assume a random variable has a Poisson distribution
Check that Poisson distribution would be a reasonable approximation for the distribution of observed data


## Assumptions

- Average number of events in a given time period or space is $\lambda$
- Number of events in non-overlapping time periods or spaces is independent
- Probability of one event in a short time period or space h is $\lambda h$
- Probability of more than one event in a short time period or space h is 0

## Uses
- Number of accidents that occur within a week at a given intersection
- Number of telephone calls handled by a switchboard in a given time interval
- Number of radioactive particles that decay in a particular time period
- Number of automobiles using a freeway access ramp in a 10 minute interval


## Probability Mass function

$P(Y=y)=p(y)=\LARGE{\frac{\lambda^ye^{-\lambda}}{y!}}$


## Moments
- Parameter: $\lambda$
- Mean of Y: $\mu=E(Y)=\lambda$
- Variance of Y: $\sigma^2=V(Y)=\lambda$
- MGF of Y: $M_Y(t)=e^{\lambda(e^t-1)}$

