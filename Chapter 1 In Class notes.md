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
It asserts that probability reflects individual beliefs, a departure from the notion of an objective frequency governing events. 
Challenges of the Bayesian View:
- Is a combo of the challenges of the last two
- Subjectivity in Prior Probability
---
# Axiomatic Approach
All of the approaches use define probability between 0 - 1.
If we used 
