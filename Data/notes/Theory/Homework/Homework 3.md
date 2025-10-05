1. When the health department tested private wells in a county for two impurities commonly found in drinking water, it found that 20% of the wells had neither impurity, 40% had impurity A, and 50% had impurity B. If a well is randomly chosen from those in the county, find  

(a) the probability distribution for Y , the number of impurities found in the well.  

$P(A\cap B) = 1-P(A^C\cap B^C)=1-.2=.8$

$P(Y=1)=P(A\cap B^C)\cup(A^C\cap B)=P(A)+P(B)-2P(A\cap B)=.9-2(.1)=.7$
$P(Y=2)P(A\cup B) = P(A)+P(B)-P(A\cap B) = .4+.5-.8=.1$


| Y   | P(Y) |
| --- | ---- |
| 0   | .2   |
| 1   | .7   |
| 2   | .1   |

(b) the theoretical mean number of impurities in the well.  
$E(Y)=0(.2)+1(.7)+2(.1)=.9$

(c) the theoretical variance of impurities in the well.  
$V(Y)=0(.2)+1^2(.7)+2^2(.1)-.9^2$

2. Let the random variable Y be the maximum observed value when two 6-sided dice are rolled.  

(a) Find the probability distribution for Y .  

| Y    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | 10   | 11   | 12   |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| P(Y) | 1/36 | 2/36 | 3/36 | 4/36 | 5/36 | 6/36 | 5/36 | 4/36 | 3/36 | 2/36 | 1/36 |
(b) Find the theoretical mean for Y .  
$\sum_{i=2}^{12}y_ip ( y_i)  = \frac{2*1}{36}+\frac{3*2}{36}+...+\frac{12*1}{36}=7$ 

(c) Find the theoretical variance for Y .

$E(Y^2)=\sum_{i=2}^{12}y_ip ( y_i)  = \frac{2^2*1}{36}+\frac{3^2*2}{36}+...+\frac{12^2*1}{36}=54.8\bar{33}$
$V(Y)=54.8\bar{33}-7^2=5.8\bar3$

3. The manager of a stockroom in a factory has constructed the following probability distribution for the daily demand (number of times used) for a particular tool.  
$$
\begin{array}{|c|c|}
\hline
y & p(y) \\
\hline
0 & 0.1 \\
1 & 0.4 \\
2 & 0.5 \\
\hline
\end{array}
$$
It costs the factory $100 each time the tool is used. Find the mean and variance of the daily cost of the tool to the factory.

$E(Y)=\mu=0*.1+1*.4+2*.5=1.4$
$V(Y)=0^2*.1+1^2*.4+2^2*.5-1.4^2=.44$ 

4. The Powerball Lottery has two bins, the first containing numbers 1-69, and the second containing numbers 1-26. Five numbers are drawn without replacement from the first bin, and one number, the Powerball, is drawn from the second bin. The cost of playing the Powerball lottery game is $2 and players can win the game in nine different ways depending on how many of the five numbers from the first bin and the one number from the second bin they match on their ticket (order is unimportant).  

The nine ways to win along with the corresponding prize money are listed in the table below.
$$

\begin{array}{|l|c|r|}
\hline
\text{Match} & \text{Prize} & \text{Number of Ways to Win} \\
\hline
5 \text{ numbers plus Powerball} & \text{Grand Prize} & 1 \\
5 \text{ numbers} & \$1,000,000 & 25 \\
4 \text{ numbers plus Powerball} & \$50,000 & 320 \\
4 \text{ numbers} & \$100 & 8,000 \\
3 \text{ numbers plus Powerball} & \$100 & 20,160 \\
3 \text{ numbers} & \$7 & 504,000 \\
2 \text{ numbers plus Powerball} & \$7 & 416,640 \\
1 \text{ number plus Powerball} & \$4 & 3,176,880 \\
\text{Powerball} & \$4 & 7,624,512 \\
\hline
\end{array}

$$

a) Find the number of possible sets of 5 numbers plus the Powerball in the Powerball Lottery game. This is the number in the denominator of the probabilities.  

$\binom{69}{5}\binom{26}{1}$

(b) How many possible sets of 5 numbers plus the Powerball will win you no prize in the Powerball Lottery game?  

$N_{Lose}=N_{Total}-N_{Win}=26\binom{69}{5}-1-25-320-8000-20160-504000-416640-3176880-7624512$

(c) For the remainder of this problem, assume the Grand Prize for a particular drawing is $500 million. What is the expected earnings (or loss) when playing the Powerball Lottery for this drawing? (Hint: Don’t forget to subtract the two dollars it costs to purchase a ticket at the end of your calculations).

$E(Y)=\frac{7624512*4+3176880*4+416640*7+504000*7+20160*100+8000*100+320*50000+1000000*25+500000000*1}{26\binom{69}{5}}-2=.031$

(d) In the above calculation, we have ignored two factors that will determine how much money you receive. First, grand prizes are paid out as an annuity over a 30 year period. You can opt to receive the prize all at once (a lump-sum payment), but the grand prize is then approximately 40% of the advertised amount. For example, for a $500 million grand prize, the actual amount received would be $500 ∗ 0.4 = $200 million. What is the expected earnings (or loss) when playing the Powerball Lottery if you take this grand prize as a lump-sum payment?  

$E(Y)=\frac{7624512*4+3176880*4+416640*7+504000*7+20160*100+8000*100+320*50000+1000000*25+200000000*1}{26\binom{69}{5}}-2=-.9957$
(e) Second, the Internal Revenue Service will want payment of taxes from the three largest prizes (we will ignore taxes on prizes of $100 or less). They will charge you tax of 24% of your winnings up front - so you will receive only 76% of the prize amount. You would probably owe more taxes, but the actual amount would be highly variable depending on the situation, so we will just use the up front tax charge to take taxes into account. What is the expected earnings (or loss) when playing the Powerball Lottery if you take the grand  prize as a lump-sum payment and you factor in taxes on the three largest prizes?

$E(Y)=\frac{7624512*4+*3176880*4+416640*7+504000*7+20160*100+8000*100+.76*320*50000+.76*1000000*25+.76*200000000*1}{26\binom{69}{5}}-2=-1.1919$

5. An individual claims to have extrasensory perception (ESP). As a test, a fair coin is flipped ten times, and he is asked to predict in advance the outcome.

(a) If the individual does not have ESP, what is the probability he will correctly guess the outcome on any given coin flip?  

.5

(b) If the individual does not have ESP, what is the probability that he will correctly guess 7 or more out of 10 flips?  

$\sum_{i=7}^{10}\binom{10}{i}.5^i*.5^{10-i}=0.171875$ 

(c) If the individual does not have ESP, what is the probability that he will correctly guess 9 or more out of 10 flips?  

$\binom{10}{9}.5^9.5^1+\binom{10}{10}.5^{10}.5^0=0.01074219$


(d) The test is conducted and the individual guesses correctly on 6 out of 10 coin flips. What do you think about the individual’s claim that he has ESP? Explain your answer.  

$p=\sum_{i=6}^{10}\binom{10}{i}.5^i.5^{10-i}=0.3769531$

The odds of guessing at least 6 out of 10 coin flips correctly is more than 1/3, therefore the likelihood of the individual possessing ESP is low.

(e) A new test is devised where the person is asked to predict the outcome in advance for 100 coin flips. The test is conducted and the individual guesses correctly on 60 out of 100 coin flips. What do you think about the individual’s claim that he has ESP? Explain your answer.

$\sum_{i=60}^{100}\binom{100}{i}.5^i.5^{100-i}=0.02844397$ 

6. Medical researchers have in recent years discovered a gene named BRCA 1 that increases the risk a woman will develop certain types of cancers (including breast and ovarian) during her lifetime. Current estimates are that women carrying this gene have a 60% chance of developing breast cancer during their lives (compared with a 12% chance for women who do not have this gene). Suppose we have 1,000 non-related women who have the BRCA 1 gene.  

(a) Find the expected number of women who will develop breast cancer during their lifetimes.  

$.60*1000=600$

(b) Find the variance of the number of women who will develop breast cancer during their lifetimes.

$1000*.6*.4=240$

7. Use R to graph the probability mass function of a Binomial random variable for the following parameters:

• p = 0.5 and n = 5, 10, 20, 50  
• p = 0.1 and n = 25, 50, 100, 250  
• p = 0.9 and n = 25, 50, 100, 250  

```
plot_binom_pmfs <- function(p, n_values) {
  par(mfrow=c(2,2))  
  for (n in n_values) {
    x <- 0:n
    pmf <- dbinom(x, size=n, prob=p)
    barplot(pmf, names.arg=x, main=paste("n =", n, ", p =", p),
            xlab="k", ylab="P(X=k)", col="skyblue")
  }
}

#p = 0.5
plot_binom_pmfs(0.5, c(5, 10, 20, 50))

#p = 0.1
plot_binom_pmfs(0.1, c(25, 50, 100, 250))

#p = 0.9
plot_binom_pmfs(0.9, c(25, 50, 100, 250))

```

Use your graphs to answer the following questions.  
(a) For which value of p are all of the graphs symmetric?  

p=.05

(b) For which values of p are the graphs mirror images of each other for a given sample size?  
.9 and .1

(c) For which value of p are the graphs skewed right for smaller values of n and more symmetric for larger values of n?  

p=.1

(d) For which value of p are the graphs skewed left for smaller values of n and more symmetric for larger values of n?

p=.9

(e) For each value of p, the smaller of the values of np and n(1 − p) for the four distributions are the same: 2.5, 5, 10, and 25. How would you describe the shape of the last two distributions for each value of p?

The last value is the least skewed and the most symmetric

8. The number of people arriving for treatment at an emergency room can be modeled by a Poisson process with a mean of λ = 5 per hour.  

(a) Find the probability that exactly four arrivals occur during a particular hour.  

$\frac{5^4e^{-5}}{4!}$

(b) Find the probability that at most 2 people arrive during a particular hour.  

$\sum_{i=0}^2\frac{5^ie^{-5}}{i!}$

(c) Find the probability that at least four people arrive during a particular hour.  

$1-\sum_{i=0}^3\frac{5^ie^{-5}}{i!}$

(d) What is the mean and variance of the number of people you expect to arrive during a particular hour.  

E(Y)=5
V(Y)=5

(e) Find the probability that in a particular 8 hour shift there would be at least one hour with at least 7 patients.

$1-(\sum_{i=0}^6\frac{5^ie^{-5}}{i!})^8$

9. Use R to graph the probability mass function of a Poisson random variable when λ = 1, 5, 25, and 50.  
Describe the differences you see in the shape of the distribution as the parameter λ changes.

```
library(ggplot2)
library(gridExtra)

plot_poisson_pmf <- function(lambda, title) {
  x_min <- max(0, floor(lambda - 4 * sqrt(lambda)))
  x_max <- ceiling(lambda + 4 * sqrt(lambda))
  x <- x_min:x_max
  
  prob <- dpois(x, lambda = lambda)
  df <- data.frame(x = x, probability = prob)
  
  ggplot(df, aes(x = x, y = probability)) +
    geom_bar(stat = "identity", fill = "steelblue", width = 0.7) +
    geom_point(color = "orange", size = 1.5) +
    labs(title = title,
         x = "Number of Events (k)",
         y = "Probability") +
    theme_minimal() +
    theme(plot.title = element_text(hjust = 0.5))
}

p1 <- plot_poisson_pmf(1, "Poisson(lambda = 1)")
p2 <- plot_poisson_pmf(5, "Poisson(lambda = 5)")
p3 <- plot_poisson_pmf(25, "Poisson(lambda = 25)")
p4 <- plot_poisson_pmf(50, "Poisson(lambda = 50)")

grid.arrange(p1, p2, p3, p4, ncol = 2, nrow = 2)
```

For low lambda values the distribution is right skewed, but gets more normal as lambda increases