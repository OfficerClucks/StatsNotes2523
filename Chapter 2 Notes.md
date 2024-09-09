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
