# Chapter 2 What is counting?

**Counting Objects**: Determining the number of ways objects and be arranged or combined.

**Combinations and Arrangements**: arranging or selecting objects such as choosing outfits or forming teams for a sport

**Probability and Chance**: Counting theory is closely related to probability theory which is predicting the likelyhood of events.

**Permutations in Everyday Language**: Arrangements in a particular order.

**Combinations in Decision-Making**: In decision-making processes, people often need to select a subset of items from a larger set without regard to the order.

## Three Fundamental Concepts

- Product Rule :  : The product rule addresses scenarios where a **sequence** of
tasks or choices is performed **independently**, with each task having multiple possible outcomes. 

It states that if there are n1 ways to perform the first task, n2 ways
to perform the second task, and so on until the kth task with nk
ways, then the total number of outcomes is the product of the
number of ways for each task.

(And) = product rule: set A and Set B 

The product rule can be expressed mathematically as:

𝑇𝑜𝑡𝑎𝑙 𝑛𝑢𝑚𝑏𝑒𝑟 𝑜𝑓 𝑜𝑢𝑡𝑐𝑜𝑚𝑒𝑠 = 𝐧𝟏 × 𝐧𝟐 × ⋯ × 𝐧𝐤

Product rule assumes:
-The independance of events
  - The outcomes of each task or event are independent of eachother.
- Need a Finite number of choices
  - Has to be able to be counted
- Non-Replacement
  - A choice annot be repeated or replaced in subsequent steps.
    - Like taking a piece of candy then putting it back  
---

- Sum rule: The sum rule serves as a companion to the product rule,
stepping in when there exist multiple mutually exclusive ways to
accomplish a task.

![image](https://github.com/user-attachments/assets/6b4be5a4-fe40-41ee-bb32-bbbb36260390)

Here, n1,n2,...,nk represent the number of options or choices available
for each task or event. The sum of these options yields the total number
of possible outcomes.

(or) means summation: Set A or Set B

Conditions to use the Sum rule:
- Mutual exclusivity
  - like flipping a coin for one experiment then rolling a dice for a different experiment. 
- Finite set of options

Application of the Sum Rule:
- Probability Theory
  - Analyzing events with multiple mutally exclusive outcomes
- Statistics
  - Calculating cumulative possibilites in data
- Decision Making
  - Weighing alternative options with distinct consequences

  
---

- Bijections: Bijections, also known as one-to-one correspondences, are fundamental concepts in mathematics that provide a powerful tool for establishing relationships between sets we'll delve into the foundational concepts of counting methods.

Such a correspondence is often denoted by the symbol " " or represented using functions.

Types of Bijection
- Injectivity: A bijection is injective if each element in the domain
maps to a distinct element in the codomain. This property ensures
that no two distinct elements in the domain are mapped to the same
element in the codomain. (One to One)

- Surjectivity: A bijection is surjective if every element in the
codomain is mapped to by at least one element in the domain. This
property guarantees that there are no "gaps" or "missing elements" in
the mapping. (Onto) 

- Bijectivity: A bijection is bijective if it is both injective and
surjective. In other words, it establishes a perfect one-to-one
correspondence between the elements of the domain and the
elements of the codomain (one to one , and onto)

![image](https://github.com/user-attachments/assets/0c79987a-6906-4d66-896a-db1bcfe73009)

---

## Three fundamental methods:

- Permutations: Permutations are a fundamental concept in combinatorics,
providing a framework for understanding the arrangements of objects in a
specific order

- Combinations: Combinations play a central role in combinatorics, the
branch of mathematics concerned with counting, arranging, and analyzing
discrete objects.

- Inclusion-Exclusion: The Inclusion-Exclusion Principle is a profound
concept in combinatorics and set theory, serving as a cornerstone for
systematically counting elements within the union of multiple sets

**Permutations**
- This concept encapsulates the essence of orderliness,
illustrating how objects can be systematically
organized to create distinct configurations.

- The significance of arrangement lies in the fact that
the order of objects matters.

-  By systematically rearranging objects, we uncover
new configurations and patterns, each with its own
distinct characteristics.

![image](https://github.com/user-attachments/assets/2f1d0833-9392-4769-bbb8-8c95e4921dfa)

Here's a breakdown of the components:
- n! represents the factorial of n, which is the product of all positive
integers up to n.

- (n−k)! represents the factorial of n−k, capturing the number of
permutations of the remaining objects.

- The division n!/(n−k)! ensures that repetitions and order are considered
in the arrangement.

---
Binomial Coefficients

Binomial coefficients are fundamental in combinatorics and represent the
number of ways to choose k elements from a set of n distinct elements,
regardless of the order.

Binomial coefficients provide a method to calculate the number of
combinations (unordered selections) of k elements from a set of n distinct
elements.

Formula:

![image](https://github.com/user-attachments/assets/ec926193-b2d6-487a-b389-f22fb0c0ed9b)

The (n-k)! is used to cancel out the top half of the numerator.

---
## Fundamental Concepts

**Probability Distribution:**

• A probability distribution describes the likelihood of each value
of a random variable. It specifies the probabilities associated
with each possible outcome.

**Discrete Probability Distribution:**

• Assigns probabilities to each possible value of a discrete
random variable. Examples include the Bernoulli, binomial,
and Poisson distributions.

**Continuous Probability Distribution:**

• Describes the probabilities associated with intervals of values
of a continuous random variable. Common examples include
the normal (Gaussian) and exponential distributions.

**Probability Mass Function (PMF):**

• For discrete random variables, the PMF gives
the probability of each possible value.

**Probability Density Function (PDF):**

• For continuous random variables, the PDF
specifies the density of probabilities over
intervals of values.

**Cumulative Distribution Function (CDF):**

• Provides the probability that a random variable
is less than or equal to a certain value.

**Expected Value and Variance:**

• Measures of central tendency and variability
for random variables, representing the mean
and spread of the distribution, respectively.
  - The expected value doesn't have to be one of your outcomes.
    - **Linearity:** The expectation of a linear combination of random variables is equal to the linear combination of their individual expectations.
      That is, for constants a and b and random variables X and Y, we have E(aX+bY)=aE(X)+bE(Y).
    - **Monotonicity:** If X and Y are random variables such that X≤Y for all outcomes, then E(X)≤E(Y).
    - **Translational Invariance:** Adding a constant c to a random variable X shifts its expectation by the same constant. That is, E(X+c)=E(X)+c.

**Variance**
- **Linearity of Variance:** The variance of a linear
combination of random variables is equal to the
sum of the variances of the individual variables
plus twice the covariance between them. That is,
for constants a and b and random
variables X and Y, we have 𝑉𝑎𝑟 𝑎𝑋 + 𝑏𝑌 = 𝑎2𝑉𝑎𝑟 𝑋 + 𝑏2𝑉𝑎𝑟 𝑌 + 2𝑎𝑏𝐶𝑜𝑣 (𝑋, 𝑌).

- **Non-Negativity:** The variance of a random variable
is always non-negative, i.e., Var(X)≥0.

- **Homogeneity of Variance:** Multiplying a random
variable X by a constant c scales its variance by 𝑐2.
That is, 𝑉𝑎𝑟(𝑐𝑋) = 𝑐2𝑉𝑎𝑟(𝑋).

---
### Multinomial Coefficients
Multinomial coefficients extend the concepts of binomial coefficients and
permutations with repetition to scenarios where a set of objects is divided
into multiple categories, and objects within each category may be
indistinguishable.

Multinomial coefficients allow us to count the number of ways to arrange a
set of objects when they are divided into multiple categories, and objects
within each category are identical.

The multinomial coefficient is calculated using the formula:

![image](https://github.com/user-attachments/assets/8965d10f-5f85-413f-ae08-f0d23185fc07)

--- 
## Combinations 

![image](https://github.com/user-attachments/assets/0ad491bd-665e-4238-9bc9-806a70b283a3)

Here's what each component of the formula represents:

- n! (read as "n factorial") represents the factorial of n, which is the
product of all positive integers from 1 to n.

- k! represents the factorial of k, similarly defined as the product of all
positive integers from 1 to k.

- (n−k)! represents the factorial of n−k, which is the product of all
positive integers from 1 to n−k

