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
$.2=1-(1-p)^{25} \rightarrow.8=(1-p)^{25} \rightarrow.8^{1/25}=1-p\rightarrow p=1-.8^{1/25}$ 
(b) How small should the probability of a defective rivet be to ensure that only 10% of all seams need reworking?

$.1=1-(1-p)^{25} \rightarrow (1-p)^{25}=1-.1\rightarrow(1-p)^{25})\rightarrow.9^{1/25}=1-p\rightarrow p=1-.9^{1/25}$
 
4. In 2006, cyclist Floyd Landis won the sports’ premier event, the Tour de France. After completing the race, the World Anti-Doping Agency released test results which indicated that Landis had high testosterone levels in his urine after one of the race stages. After further litigation, the International Court of Arbitration for Sport upheld the test results, stripped Landis of the Tour de France win, and banned him from professional cycling for two years. During the course of the 2006 Tour de France, Landis submitted 8 urine specimens for analysis. The test results on these 8 specimens depend on the accuracy of the testing procedures. For parts (a) and  
(b) below, assume Landis WAS NOT doping and that each test result is independent of the others. Let the probability of a correct no-doping test result given the assumption that Landis WAS NOT doping to be the value p.  
(a) What is the probability all 8 urine tests would come back with the correct no-doping test result if the value of p = 0.95? What about when the value of p = 0.99? What about for a general value p?  
(b) Determine the value of p so that the probability all 8 urine tests came back with the correct  
no-doping test result is 0.99. Now for parts (c) - (e), assume that Landis WAS doping. Let the probability of a correct doping test result given the assumption that Landis WAS doping to be the value r. (Each test result is still independent of all others).  
(c) What is the probability that zero or one test out of the 8 would have a correct doping test result if the value of r = 0.9?  
(d) What is the probability that zero or one test out of the 8 would have a correct doping test result if the value of r = 0.95?  

(e) Write a general formula using r for the probability that zero or one test out of the 8 would have a correct doping test result.  
(f) In May 2010, Floyd Landis finally admitted to doping during the 2006 Tour de France. Based on this information and your calculations in parts (c) - (e), what do you conclude about the accuracy of the tests used?




5. The Monty Hall problem is a well-known puzzle in probability derived from an American game show, Let’s Make a Deal. (The original 1960s-era show was hosted by Monty Hall, giving this puzzle its name.) Intuition leads many people to get the probabilities associated with the puzzle wrong, and when the Monty Hall problem is presented in a newspaper or discussion list, it often leads to a lengthy argument in letters-to-the-editor and on message boards. The game is played like this:  
• The game show set has three doors. A prize such as a car or vacation is behind one door, and  
the other two doors hide a valueless prize called a Zonk; in most discussions of the problem, the 
Zonk is a goat.  

• The contestant chooses one door. We will assume the contestant has no inside knowledge of which door holds the prize, so the contestant just makes a random choice.  
• The host Monty Hall opens one of the other doors, always choosing one that shows a goat, and always offers the contestant a chance to switch their choice to the remaining unopened door.  
• The contestant either chooses to switch doors, or opts to stick with the first choice.  
• Monty calls for the remaining two doors to open, and the contestant wins whatever is behind  
their chosen door.  For example, let’s say a hypothetical contestant chooses door #2. Monty might then open door #3 and offer the contestant the chance to switch to door #1. The contestant will either stay with door #2 or switch to door #1. Then we will see which door (either door #1 or door #2) the prize is hidden behind.  
The puzzle is: what is the best strategy for the contestant (staying or switching)? Does switching increase the chance of winning the car, decrease it, or make no difference?  
(a) Before you investigate this problem, decide on the strategy you will use in your simulation -  
staying or switching? Explain why you chose this strategy.  
(b) Go to the link with the Module 2 HW assignment in Canvas. Here you can simulate the Monty 
Hall problem. Play the game 20 times using your strategy and enter the number of times you  
won the game on the answer sheet.  
(c) Now play the game another 20 times using the other strategy. Again, enter the number of times you won the game out of your 20 attempts on the answer sheet.  
(d) You can also simulate the puzzle many times automatically using a specified strategy. Using your original choice of strategy, play the game 100 times and enter the number of times you won the game on the answer sheet. (Hint: un-select the Animate button to speed play).  
(e) Now play the game another 100 times using the other strategy. Again, enter the number of times you won the game on the answer sheet.  
(f) For your 120 trials, what proportion of times was the game won using each strategy?  
(g) Given this information, which is the best strategy for playing this game - staying or switching?  
Explain your answer.