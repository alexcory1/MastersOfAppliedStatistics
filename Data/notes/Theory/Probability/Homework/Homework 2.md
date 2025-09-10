1. Three plants manufacture hard drives and ship them to a warehouse for distribution. Plant I produces  54% of the warehouse’s inventory with a 4% defect rate. Plant II produces 35% of the warehouse’s inventory with an 8% defect rate. Plant III produces the remainder of the warehouse’s inventory with a 12% defect rate.  

Let plant I be denoted as A, II as B, and III as C

(a) A warehouse inspector selects one hard drive at random. What is the probability that it is a  
defective hard drive and from Plant II?  
$P(B\cap\text{defective}) = .35 * .08 = 0.028$
(b) What is the probability that a randomly selected hard drive is defective?  
$P(A\cap\text{defective})+P(B\cap\text{defective})+P(C\cap\text{defective}) = .54*.04+.35*.08+.11*.12=.0628$
(c) Suppose a hard drive is defective. What is the probability that it came from Plant II?
$P(B|\text{defective}) = \frac{P(\text{defective|B})P(\text{B})}{P(defective)} = \frac{..08*.35}{.0628}$ 

2. At a gas station, 40% of the customers use regular gas, 35% use midgrade gas, and 25% use premium gas. Only 30% of customers using regular gas fill their tanks, while this percentage is 60% for midgrade gas and 50% for premium gas.  

Let Regular gas be A, midgrade be B, and premium be C
Let filling the tank be F, and not filling the tank be $F^C$

(a) What is the probability that the next customer will request midgrade gas and fill the tank?  
$P(B\cap F)=P(B)*P(F|B)=.35*.6=.21$ 
(b) What is the probability that the next customer fills the tank?  
$P(F)=P(A\cap F)+P(B\cap F)+P(C\cap F)=.4*.3+.35*.6+.25*.5=.455$
(c) If the next customer fills the tank, what is the probability that regular gas is requested?
$P(A|F) = \frac{P(F|A)P(A)}{P(F)}=\frac{.3*.4}{.455}$

3. An aircraft seam requires 25 rivets. The seam will have to be reworked if any of these rivets is defective. Suppose rivets are defective independently of one another, each with the same probability.  
(a) If 20% of all seams need reworking, what is the probability that a rivet is defective?  
$.2=1-(1-p)^{25} \rightarrow.8=(1-p)^{25}$ 
$\Rightarrow \frac{.2}{25}=P(F)=.008$
(b) How small should the probability of a defective rivet be to ensure that only 10% of all seams need reworking?

$.1=25P(F) \rightarrow \frac{.1}{25}=P(F)=.004$