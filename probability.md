#PROBABILTY
The likelyhood of an event occuring.
eg. flipping o a coin.
we express pobability using 0 and 1.
0 - for absolute certainty of an event not happening. 
1 - for absolute certainty.

# DEFINITION
 A- any event
 p(A)-preferred outcome / sample space
 eg= probability of getting head on a coin .
 P(A)= 1/2.

 #REMEMBER-
 probability of two events occuring at the same time = Product of all the probabilities of the individual events.
 P(A and B)=P(A).P(B)

#EXPECTED VALUES
The average outcome we expect if we run an experiment many times.
 
All the probabilites we get after conducting experiments are experimental probabilites.

These are not equal to the theoretical one"s , it"s easy to compute.
 It uses the same formula.
 P(A) = Successful trials /all trials.

 So, expected value of any event A.
 E(A)=T he outcome we expect when we run an experiment.

E(A)= P(A).n
where P(A)- theoretical probability of the event.
n- no. of trials.

So, expected value is used in trying to predict the future events.


#PROBABILITY FREQUENCY DISTRIBUTION.

--> It is a collection of probabilities for each possible outcome.
-> we can express this probability frequency distribution through a graph or table.
--> The highest bars are of highest probability.

#CHARACTERSTICS OF PROBABILITIES AND EVENTS.

1. COMPLEMENTS= It is everything the event is not.It helps in completing the rest of the sample space.
 Can be calculated as = sum of the probabilities of different events should be 1.

 i.e P(A)+P(B)=1 , 1 means absolute certainity.
 --> If the sum of probabilities is less than 1 P<1 , then it means the event is not guranteed to occur.There must be some part of sample space that we have not counted yet.

 --> If the sum is >1 , then it means you are double counting the outcome.

 So,all events have compliments. They are denoted by  A' and also the complement of the complement is the event itself and denoted as (A')'=A.


 Example- A= rolling an even number.
 A'= not rolling an even number.

 The probability of the complement is counted as P(A')=1-P(A)

 Example- Consider rolling a die then 
 Getting the numbers 1,2,4,5,6.
 Their sum is 
 p(A)= P(1)+P(2)+P(4)+P(5)+P(6)= 1/6+1/6+1/6+1/6+1/6=5/6

Another way of describing getting 1,2,4,5,6 is not getting a three.
 P(B)=1-P(B')
We know ,     P(B')=1/6
   P(B)=1-1/6 = 5/6
   Therefore, P(A)=P(B)


 # COMBINATORICS  

 It deals  with the combinations of objects from a specific finite set.
 It can be applied  to form combinations.
 Restrictions for these are -
 Repitition 
 Order or different criterion.

 The combintorics have three integral parts , which are 
 --> Permutations.
 --> Variations.
 --> Combinations.

1. PERMUTATIONS -The number of possible ways we can arrange a set of elements.
 These elements can be digits , objects and even people.

 Intution-behind computing the total number of permutations for a set of n many elements.
     P<sub>n</sub>= nx(n-1)x(n-2)x....x1=n!

 #FACTORIALS-
   n!= The product of the natural numbers from 1 to n.
   means n!=1x2x3x...xn 
   example- 3!=1x2x3=6

  #IMPORTANT PROPERTIES-
 --> Negative numbers don't have a factorial
 -->0!=1
 -->For any natural nuber n , n!=(n-1)!xn
 similarly, (n+1)!=n!x(n+1)
 example - n=6
 6!=5!x6
 7!=6!x7
 could be expanded to express- (n+k)!&(n-k)!
 --> (n+k)!=n!x(n+1)x(n+2)x..x(n+k)
 --> (n-k)!=n!/(n-k+1)x(n-k+2)x...xn

-->Two Factorials
If we have two natural numbers n and k, then
if n>k
n!/k!=(k+1)x(k+2)x...xn
example - n =7, k=4
7!/4!=1x2x3x4x5x6x7/1x2x3x4=5x6x7

2.VARIATIONS- The total number of ways we can pick and arrange some elements of a given set

-->Notation and Formula=
<span style="text-decoration: overline;">V</span><sub>p</sub><sup>n</sup>=n<sup>p</sup>
where, n= the total number of elements we have available.
       p=the number of positions we need to fill.

It is described as ,the number of variations with repetition when picking p-many elements out of n elements,is equal to n to the power of p.

*Why we use variations instead of permutations?
we use variations when we have to first pick and then arrange some (but not all) elements  of the sample space.

#Variations without repetition-
In this we can not repeat the element that we have already chosen.
That's what makes it different from variations with repitition.

#NOTATION AND FORMULA-

V<sup>n</sup><sub>p</sub>=n!/(n-p)!
The number of variations without repetition when arranging p elements out of a total of n.

example= p=4,n=5
5!/(5-4)!

3.COMBINATIONS- The number of different ways we can pick certain elements of a set.

 FORMULA-
 The number of combinations for choosing p-many elements out of a smaple space of n elements.
 So, the number of combinations equals the numbers of variations over the number of permutations.
  i.e C<sup>n</sup><sub>p</sub>=V<sup>n</sup><sub>p</sub>/P<sub>p</sub>

  we get the formula = C<sup>n</sup><sub>p</sub>=n!/p!(n-p)!
  #SYMMETRY OF COMBINATIONS-
  Unlike permutations and variations ,picking more elements can lead to having fewer combiantions.
  when p>n/2>n-p
  Apply symmetry to avoid calculating factorials of large numbers.
. We use symmetry to simplify the calculations.













