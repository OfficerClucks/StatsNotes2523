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

## Examples
Coin Flip example with the axioms:
Variables H (Heads), T (Tails)
Axiom 1 says that P(H)≥ 0, and P(T) ≥ 0 
Axiom 2 says that 0 ≤ P(H) ≤ 1 and  0 ≤ P(T) ≤ 1
Axiom 3 says that P(H,T) = P(H)+P(T)

