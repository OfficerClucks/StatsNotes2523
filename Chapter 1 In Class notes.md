# Probability Fundamentals 
Basic probability, probability models, and introduction to discrete and continuous random variables.

# What is Probability?
- Probability, denoted as *P(A)* are maps that assign numbers to subsets within a defined sample space. Probability has to be within 0 - 1 
![image](https://github.com/user-attachments/assets/853750dc-b70a-4f25-87de-9a0c3134fe60)

- Ω a sample space often represented as a rectangle or square
- Objectivits: Relate probability to the relative frequency of outcomes
- Subjectivits: View it as a degree of belief called **Bayesian probability**

 A probability measure, denoted as P, must satisfy two key properties: the probability of the whole space is 1, and the probability of the empty event is 0.

**The Classical Interpretation of Probability:** Assumes that all outcomes are equally likely to happen. An example of this would be a coin toss. Two equally likely results. The **formula of calculating probability** is: 
![image](https://github.com/user-attachments/assets/41a5137c-da95-4dc0-a4c8-f54d63a91225)
The number of ways an event (A) can occur is effectively a sample size. The classical approach faces issues when the data doesn't have an equal chance of occurring. In which you would use another method such as the empirical or subjective approach. 
Challenges of the Classical Interpretation:
- Needs to not have a vague outcome.
- {HH,HT,TT} The probability of an outcome of 2 heads is either 1/3 or 1/4 depending on how you define the outcome.

**The relative frequency view of probability:** An approximation of probability is a method that relies on observations and empirical data. When observing a coin flip multiple times it might not be 50/50
The Key steps are:
1. Conduct Procedure: Repeat the procedure a specific number of times.
2. Count Occurrences: In each repetition, count the number of times the event 'A' occurs
3. Calculate Probability Estimate: Use the formula below.
![image](https://github.com/user-attachments/assets/e4117944-013a-45a0-960f-dfabc51ec777)

Challenges of relative frequency:
- Needs data / to be observed
- You need infinite repeats of an experiment to make sure you have correct data.
- Probability can only be measured in terms of a measurement dependent error but the error is defined as a probability.
  
**The Bayesian View (Belief View):** 
It asserts that probability reflects individual beliefs, a departure from the notion of an objective frequency governing events. Probability reflects beliefs symmetry makes a coin fair, and predicting 50% heads in further tosses is a belief. Most people get that if you flip a fair coin, there's an equal chance it lands heads or tails – 1 out of 2 or ½.

Challenges of the Bayesian View:
- Is a combo of the challenges of the last two
- Subjectivity in Prior Probability
---
# Axiomatic Approach
All of the approaches use a defined probability between 0 - 1.
If we used 

1. Non-negative Axiom: For any event A the probability of A is greater than or equal to 0 *P(A)≥0*
 -In other words, the likelihood of an event occurring cannot be negative – it is inherently positive or zero.

2. Normalization or unit measure Axiom: For the entire sample space *S* is equal to 1. *P(S)=1*
 - The normalization axiom guarantees that the total prob of all possible outcomes is 1

3. Additivity (or Sigma-Additivity) Axiom: For any sequence of mutually exclusive events A1,A2,A3,..., the probability of their union is the sum of their individual probabilities:
   
![image](https://github.com/user-attachments/assets/071fd805-c89f-4e42-a5f7-2ecb64890ea2)

 - The additivity axiom allows us to calculate probabilities for complex events by summing the probabilities of simpler, mutually exclusive events.

These are another perspective of the above axioms. 

1. Monotonicity: The principle of monotonicity states that if one event is a subset of another, then the probability of the subset is less than or equal to the probability of the superset.
2. Complement Rule: The complement rule states that the probability of the complement of an event is equal to one minus the probability of the event itself
 - The complement of event A happening is everything that happens when not A
3. Numeric Bound: The numeric bound on probabilities states that probabilities always lie between zero and one, inclusive. This fundamental property reflects the inherent limitations of probabilistic reasoning, where probabilities quantify degrees of belief or uncertainty ranging from complete impossibility (zero probability) to absolute certainty (probability one).

A **Set** is a collection of elements
 - Sets are always in capital letters
An **Element** is something inside a set
 - Elements are typically denoted with lowercase letters

x ∈ A x is an element of A 
x ∉ A x is not an element of A

The **Universal set** Ω is the set of all elements that could possibly be considered aslo called the **Sample Set**
 - Depends on the contest of the set
   - For tossing a coin Ω = {H,T}
   - For Dice Ω = {1,2,3,4,5,6}
   - For noise voltage Ω = {𝑥: −1 ≤ 𝑥 ≤ 1}

The **Subset** is a set in which every element of that set is an element in another set
 -Specifically, 𝐴 ⊂ 𝐵 if every member of 𝐴 is a member of 𝐵
  - Note that we can use the definition of subsets to define set equality: 𝐴 = 𝐵 if and only if (iff) 𝐴 ⊂ 𝐵 and B ⊂ 𝐴

The **Null** ∅ set is an empty set.
 - The null set is a subset of every set

## An Event

A Subset of Ω (Universal Set) is called an Event
- Events are groups of possible distinct outcomes. Distinct does not mean exclusive.
 - An example would be A = {1,2,6} B = {4,3,2} are said to be events defined by the sample space Ω = {1,2,3,4,5,6}

Set Partition: All of the Subsets are mutually exclusive from each other but still make up the whole universal set. 
![image](https://github.com/user-attachments/assets/5f61eb51-f2a0-4113-9d5b-ece8f293b8a0)

### Outcome vs Events

Every trial results in only one ***outcome***, that is, only one of the
elements in 𝑆 can be the observed outcome. The observed outcome is a member of several different
subsets – or events – and all of these events are said to have
occurred.

**Fundamental notion**: on each trial of the experiment, one
outcome occurs, but many events can occur. 

## Examples
Coin Flip example with the axioms:
Variables H (Heads), T (Tails)

Axiom 1 says that P(H)≥ 0, and P(T) ≥ 0 

Axiom 2 says that 0 ≤ P(H) ≤ 1 and  0 ≤ P(T) ≤ 1

Axiom 3 says that P(H,T) = P(H)+P(T)

---
Mutually Exclusive:

![image](https://github.com/user-attachments/assets/139eb966-e008-41df-92d1-df8f0bda17df)

Collectively Exhaustive:

![image](https://github.com/user-attachments/assets/ec990d68-7d5a-4683-8317-99009ca49b58)

Set Partition:

![image](https://github.com/user-attachments/assets/9fc4bb66-2fba-42f0-8c8d-86054d3a4cb2)

(Ec)c=E: The complement of the complement of an
event E is the event E itself.

➢ E∪Ec=S: The union of an event and its complement
is the entire sample space S.

➢ E∩S=E: The intersection of an event with the
sample space is the event itself.

➢ E∩Ec=∅: The intersection of an event and its
complement is the empty set.
