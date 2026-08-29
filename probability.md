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

NEW TYPE OF COMBINATION- A combination can be a mixture of different smaller individual events.
 Calulating the total number of combinations is by multiplying the number of options available for each individual event.

#DISTINCTIONS-
PERMUTATIONS- You always arrange the entire set of elements in the sample space..It is differ from variations in this way.

#SETS-
--> Every event have a set outcome(favourable outcomes)
--> Values of a set don't always have to be numerical.
--> Upper case letter is to express a set and lower case for its individual elements.

--> Any set can be either empty or have values in it .
A set with no elements is called an empty set or null set.It is denoted by a crossed zero (phi).

NON-EMPTY SETS-
They can be finite or infinite, depending on the no. of elements they have 
--> If we want to express if an element is a part of a set or not we use  
         xEA,here E means "belongs to" or "in"

--> If an element is not a part of a set then we just diagonally cross the E .       

Some symbols used in this -
: = such that , It is used when we want to make statements about a specific group of elements within a set.

#SUBSET-
A set that is fully contained in another set.
Eg- Every element of A is also an element of B , then  A is a subset of B.

NOTE- Every set contains atleast two subsets , itself and the null set.
-->Events can be expressed by drawing circles. These circles can never touch,intersect or completely overlap with each other.
-->If two events never touch then two events can never happen simultaneously.Event A occuring guarantees that event B is not occuring and vice versa.
--> If the events intersect then means that the two events can occur at the same time.
-->If one circle completely overlaps with another,that means that one event can only occur if the other one does as well.

#INTERSECTIONS-Two events are  intersecting if all the outcomes that are favourable for both event A and event B simultaneoysly. 
It is denoted by using "and".
Eg- The intersection of all hearts and all diamonds is the empty set.There are no outcomes which satisfy both events simultaneously.

Eg- The intersection of all diamonds and all queens is represented by the Queen of diamonds. This card is the only one that satisfies being a queen and being a diamond at the same time.

#UNION- It is defined as the combination of all outcomes preferred for either A or B.
--> The symbol we use for union is "U" , for intersection this "U" is flipped upside down."or" is used to represent this.

Eg- If the sets A and B do not touch at all,their union would simply be their sum.It means no element is in both sets simultaneously ,so no double counting.
 --> If any events intersect , the area of the union is represented by the sum of the two sets minus their intersection.

 A U B = A+B-A ∩ B

 # MUTUALLY EXCLUSIVE SETS-Sets,which are not allowed to have any overlapping elements.Their circles never intersect.
 -->INTERSECTION- Mutually exclusive sets have the empty set as their intersection.Therefore, if the intersection of any number of sets is the empty set, then they must be mutually exclusive.

 -->UNION- If some sets are mutually exclusive, then their union is simply the sum of all separate individual sets.

 COMPLIMENTS OF SETS-Sets have compliments too.
 Complement set- All values that are part of the sample space, but not part of the set.
 Eg- A set consisting all the odd numbers , its complement would be set of even no's.

 -->Complements are always mutually exclusive.
 -->Not all mutually exclusive sets are complements.

# INDEPENDENT EVENTS- The Independent events are those whose theoretical probability remains unaffected by other events.
Eg- Flipping a coin, you always have the chance of getiing tails regardless of what the previous outcome was.

#DEPENDENT EVENTS-Probabilities of dependent events vary as conditions change.

# NOTATIONS- Two events A and B- The probability of getting A, if we are given that B has occured 
         P(A|B) ,called as P of A given B .
This is called conditional probability, we use it to distinguish dependent from independent events. 

# CONDITIONAL PROBABILITY- It is the likelihood of an event occuring assuming a differnet have already happened.

NOTATION - P(A|B)= P(A AND B)/P(B) , only if P(B)>0.
Because if P(B)=0 , Event b would never occur
A|B= Not interpretable

About the formula-T o satisfy the conditional probability we need both events B and A to occur simultaneously.This means that the intersection of A and B would consist of all favourable outcomes for this probability.
The conditional probability requires that event B occurs.

# IMPORTANCE-
-->The order in which we write the elements is crucial

# ADDITIVE LAW-The probability of the union of two sets is equal to the sum of the individual probabilities of each event ,minus the probability of their intersection.
      
      P(AUB)=P(A)+P(B)-P(A and B)
Eg- suppose 38% of people in a office use Tableau and 45% in SQL.
P(T)=38%
P(S)=45%
66% of the people in the office are good with one of the two , P(T U S)=66%. What is the probability of somebody being able to implement sql and tableau simultaneously?
Ans- To solve this we can rearrange the additive law to get the intersection of tableau and sql users equal the sum of them and minus their union.
P(T AND S)=P(T)+P(S)-P(T U S)
           =38%+45%-66%
           =17%
           =0.17%
A likelihood of 0.17% for somebody in the office to be able to proficiently implement SQL and Tableau.

# MULTIPLICATION LAW- From the cnditional probability formula we can modify it into multiplication law -
       P(A|B).P(B)=P(A and B)

Eg- Suppose the probability of an event  B P(B)=0.5  and P(A|B)=0.8 . This means that event B occurs 50% of the time and event A occurs 80% of those 50% when B occured .
So the likelihood of A and B occuring at the same time P(A and B)=0.8 X 0.5= 0.4 

# BAYE'S LAW- Suppose any two events A and B
     P(A|B)=P(B|A)X P(A)/P(B) - Conditional prbability formula 
     P(A AND B)=P(B|A)X P(A) - multiplication ruke 

This is called Baye's Theorem.
--> It allows us to find a relationship between the different conditional probabilities  of two events.

Eg- It is most prominently used in meidcal research while trying to find the relationship between diff symptoms , what causeds the other.
     
# Baye's Rule in independent events-Take two events sun and code error .After solving it is seen that the chances of your algo performing as intended neither increase , nor decrease based on the weather.

# DISTRIBUTION- The possible values a variable can take and how frequently they occur.
Probability frequency distribution- Probabilities measure the likelihood of an outcome.
--> Used when we have finite number of probabilities.

Characterstics of distribution- Mean = average value.(μ)
Variance= How spread out the data is.The more dispersed the data the higher its variance will be .(σ²)

# TYPES OF PROBABILITY DISTRIBUTIONS-
If we have finite no. of outcomes then its Discrete Distribution.
If we have infinitely many outcomes then its Continuous Distributions.
DISCRETE DISTRIBUTIONS-
1. Events with only two outcomes true and false , they belong to bernoulli distribution.Any event with two outcomes can be transformed into a bernoulli event.

2.If  we carry out a similar experiment several times in a row then it is Binomial Distribution.It has two outcomes per iteration and has many iterations.

3.The poisson distribution we use it to test out how unusal an event frquency is for a given interval.

CONTINUOUS DISTRIBUTIONS-The probability distribution would be a curve.

1.Normal distrn- these are often observed in nature.
eg- it is observed that the weight of a polar bear is around 500kg. However ther is been records of individual spcecies weighing between 350kg to 700kg .Extreme values like 350 and 700 are called outliers, and do not feature very normally in the normal distribution.

soemtimes we have limited data for event that resemble a normal distributon,in those cases we observe STUDENT'S T DISTRIBUTION.
It serves as a small approximation of a normal distribution.It acoomodates extreme values signifcantly better.
CHI SQUARED DISTRIBUTION-It is the first asymmetric distribution that we are dealing with as it only consists of non negative values.
it means that it always start form the zero on the left.The curve of this is skewed to the right.
It does not offer mirror real life events.
often used in hypothesis testing. To determine the goodness of fit.
EXPONENTIAL DISTRIBUTION-it is present when we are dealing with the events that are rapidly changing early on.
eg- like the article on the internet gets most clicks when the topic is fresh and relevant but with the time passes it gets old and starts to get irrelevant.

LOGISTIC DISTRIBUTION-used in forecast analysis.and also useful for determinng a cut off point for a successful outcome.

UNIFORM DISTRIBUTION-U(a,b) eg- X-->U(3,7) means variable X folloes a discrete unifrom distribution ranging form 3 to 7.
-->the events that all have equal probability follows it.many everyday situations uses it. 
-->Expected value in it provides us no relevant info.
so main thing is that when an event follows uniform ditribution each outcome is equally likely, Both the mean and the variance are uninterpretable and have no predictive power.


BERNOULLI DISTRIBUTION-Bern(p) eg- X--> bern(p) means that X follows a bernoulli distribution with the probability of success equal to p.
The type of events that follows it are = where we have 1 trial , 2 possible outcomes. eg- a coin flip.
Graph- it has two bars one would rise up to its probability p and other would be 1-p.we have to assign which outcome is xero and which is 1 . then we calculate the expexted value.
Usually we denote the higher probability with p and lower one with 1-p.and assigns p -->1 and 1-p -->0.That way the expected value represents the likelihood of the favoured event.
if we write p and 1-p into the variance formula we would find that the variance of bernoulli event would be p(1-p).

The variance -σ²=p(1-p)
σ=square root p(1-p)

BINOMIAL DISTRIBUTION- A sqquence of bernoulli events.
Notation- B(n,p) where n is the of trials,p is the probability of success in each one. 
eg- guessing an entire quiz is binomial event and guessing only 1 question is bernoulli event.
Graph- of this describes the likelihood of attaining our desired outcome for a specific no. of times.