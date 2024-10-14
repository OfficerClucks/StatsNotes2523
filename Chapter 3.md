## Conditional Probability

![image](https://github.com/user-attachments/assets/d78040a5-fb6d-4b0e-9150-94a0e5b2463d)

Conditional Probability (P(A|B)):
- This notation represents the probability of event A occurring given that event B has already occurred. It serves as a shorthand for expressing the dependence of probability on prior conditions.
- Events for which the occurrence of one event does not influence the probability of the other event. In the context of conditional probability, independence
implies that P(A∣B)=P(A), indicating that knowledge of event B does not alter the likelihood of event A.

Independence between two events signifies that the occurrence of one event does not influence the likelihood of the other event occurring.

𝑃(𝐴 ∩ 𝐵) = 𝑃(𝐴) × 𝑃(𝐵)

Conditional independence arises when the independence between two events is contingent upon the occurrence of a third event.


## Product Rule
- For Independent events, the multiplucation rule simplifies to the product of their individual probabilites
- However for dependent events, we must account for the conditional probabilities based on the occurrence of prior events.

## Law of total probability 

The law of total probability expresses the probability of an event as the sum of the probabilities of that event given different conditions. It is stated as follows:

![image](https://github.com/user-attachments/assets/1d655584-dc22-4575-9731-1701d7cebbfa)

where A*i* represents mutually exclusive and exhaustiveevents that partition the sample space.
The proof of the law of total probability involves expressing the joint probability P(B∩Ai) as the product of conditional probability P(B∣Ai) and prior probability P(Ai), followed by summing over all possible values of i.

## Bayes' Theorem

Bayes' theorem provides a systematic framework for revising beliefs or predictions in light of observed data.
![image](https://github.com/user-attachments/assets/b7792919-9de0-4bbd-b28a-b686c393b966)

The theorem is derived from the definition of conditional probability and the multiplication rule
