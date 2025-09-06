
1. Take two events A and B and their complements.
$(A\cup B) = (A \cap B)\cup(A\cap B^C)\cup(A^C\cap B)$

a.
$(A\cup B^C) = (A\cap B)\cup(A\cap B^C)\cup(A^C\cap B^C)$ 

b.
$(A^C\cup B)=(A^C\cap B)\cup(A^C\cap B^C)\cup(A\cap B)$

c. 
$(A^C\cup B^C) = (A^C\cap B^C)\cup(A^C\cap B)\cup(B^C\cap A)$

2. A sample of four home mortgages is classified as fixed rate (F) or variable rate (V).
a. List all 16 outcomes in S
FFFF FFFV FFVF FFVV
FVFF FVFV FVVF FVVV
VFFF VFFV VFVF VFVV
VVFF VVFV VVVF VVVV

b. Which outcomes belong to the event that exactly three of the mortgages are fixed
FFFV FFVF FVFF VFFF

c. Which outcomes belong to the event that all four mortgages are of the same type?
FFFF VVVV

d. Which outcomes belong to the event that at most one of the four is a variable rate
FFFF FFFV FFVF FVFF VFFF 

e. What are the union and intersection of c and d
Intersection: FFFF
Union: FFFF VVVV FFFV FFVF FVFF VFFF

f. What are the union and intersection of b and c
Intersection: $\emptyset$  
Union: FFFV FFVF FVFF VFFF FFFF VVVV

3. 5 Executives, 2 tickets to conference, 3 males denoted $M_1,M_2,M_3$ and 2 females denoted $F_1, F_2$, order does not matter
a. List the sample space S
${\{M_1,M_2\}}$ $\{M_1,M_3\}$ ${\{M_1,F_1\}}$ $\{M_1,F_2\}$ 
${\{M_2,M_3\}}$ $\{M_2,F_1\}$ ${\{M_2,F_2\}}$
${\{M_3,F_1\}}$ $\{M_3,F_2\}$ 
$\{F_1,F_2\}$ 

b. What is the probability of each simple event in S given that each event is equally likely
$1/10$ 
c. What is the probability of two women
1/10

4. Roll 2 dice
a. Probability of obtaining a sum of 7, 8, or 9
7: 6/36
8: 5/36
9: 4/36
$P(7 \cup8\cup9) = \frac{15}{36}$

b. Probability the smaller of the two values is 1
1 outcome where both are 1
5 outcomes where roll 1 is 1 and roll 2 is not 1
5 outcomes where roll 2 is 1 and roll 1 is not 1
11/36

c. Find the probability the larger of the two values on the dice is equal to 5.
logic follows the same as part b, but without $\{5,6\},\{6,5\}$ 
9/36

5. Consider randomly selecting a student at a certain university, and let A denote the event that the selected individual has a Visa credit card and B be the analogous event for a MasterCard. Suppose that $P(A)=.5;P(B)=.4;P(A\cap B)=.25$ 
a. Probability the selected student has at least one of the cards
$P(A) + P(B) - P(A\cap B) = .5+.4-.25=.65$

b. Probability of neither card
$P(A^C\cap B^C)=1-P(A\cup B)$
$P(A\cup B)=.65$
1-.65=.35

c. Describe, in terms of A and B, the event that the selected student has a Visa card but not a MasterCard, and then calculate the probability of this event
$P(A\cap B^C)$
$P(A\cap B^C) = P(A)-P(A\cap B) = .25$

6. A particular state will elect both a governor and senator. Let A be the event that a randomly selected voter has a favorable view of a certain party's senatorial candidate, and B be the corresponding event for the party's gubernatorial candidate. Suppose that $P(A^C)=.44,P(B^C)=.57,P(A\cup B)=.68$ 
$\Rightarrow P(A)=.56, P(B)=.43$

a. What is the probability that a randomly selected voter has a favorable view of both candidates
.56+.43-.68=.31

b.Probability unfavorable for at least one
$P(A^C\cup B^C)=P(A^C) + P(B^C) - (1-P(A\cup B) =$ $.44+.57-.32=.69$
or
$P(A^C\cup B^C)=1-P(A\cap B) = 1-.31=.69$

c. Probability a voter is favorable for exactly one candidate
$P(A\cup B)-P(A\cap B)=.68-.31=.37$

7. A production facility employs 20 workers on the day shift, 15 workers on the swing shift, and 10 workers on the graveyard shift. A quality control consultant is to select 6 of these workers for in-depth interviews. Suppose the selection is made in such a way that any particular group of 6 workers has the same chance as being selected as does any other group (drawing 6 slips without replacement from among 45)

a. What is the probability that all 6 will be from the day shift
$\frac{{20}\choose{6}}{{45}\choose{6}}$

b. What is the probability that all 6 selected workers will be from the same shift
$\frac{{{20}\choose{6}}+{{15}\choose{6}}+{{10}\choose{6}}}{{45}\choose{6}}$

c. What is the probability that at least two different shifts will be represented among the selected workers
$1-\frac{{{20}\choose{6}}+{{15}\choose{6}}+{{10}\choose{6}}}{{45}\choose{6}}$

d. What is the probability that at least one of the shifts will be unrepresented in the sample of workers

$P(\text{at least one shift unrepresented})= \frac{\binom{25}{6} + \binom{30}{6} + \binom{35}{6} - \binom{20}{6} - \binom{15}{6} -\binom{10}{6}}{\binom{45}{6}}$ 

8. The Powerball lottery game is played in many states across the country, including Iowa. In the game, five white balls and one red ball (called the Powerball) are selected. The grand prize is won if the player matches each of the five white balls and the one red ball. (The order in which the balls are selected does not matter). The probability of winning the grand prize (and the other available prizes) is thus dependent upon the number of white balls and the number of Powerballs in use. Both the number of white and red balls have changed throughout the years as indicated below.

• Old Version 1: 55 white and 42 red
• Old Version 2: 59 white and 35 red
• Current Version: 69 white and 26 red

a. What is the probability of winning the Powerball grand prize in each version of the lottery?
Old 1: $\frac{1}{\binom{55}{5}*42}$
Old 2:$\frac{1}{\binom{59}{5}*35}$
Current: $\frac{1}{\binom{69}{5}*26}$

b. Several other prizes are awarded for matching some of the white and/or red balls drawn. One  
such prize is given for matching 3 of the white balls and not the red ball (the Powerball). What  
is the probability of winning this prize in each version of the lottery?

Old 1:$\frac{\binom{5}{3}\binom{50}{2}*41}{\binom{55}{5}*42}$

Old 2: $\frac{\binom{5}{3}\binom{54}{2}*34}{\binom{59}{5}*35}$

Current: $\frac{\binom{5}{3}\binom{64}{2}*25}{\binom{69}{5}*26}$

c. Another such prize is given for matching 2 of the white balls and the red ball (the Powerball).  
What is the probability of winning this prize in each version of the lottery?
Old 1: $\frac{\binom{5}{2}\binom{50}{3}}{\binom{55}{5}*42}$
Old 2:$\frac{\binom{5}{2}\binom{54}{3}}{\binom{59}{5}*35}$
Current: $\frac{\binom{5}{2}\binom{64}{3}}{\binom{69}{5}*26}$

