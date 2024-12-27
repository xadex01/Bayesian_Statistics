## Conditional Probability
Conditional probability is the probability of an event occurring given that another event has already occurred. It is denoted as \(P(A|B)\), which represents the probability of event \(A\) occurring given that event \(B\) has occurred.

The formula for conditional probability is:
\[ P(A|B) = \frac{P(A \cap B)}{P(B)}, \quad \text{where } P(B) > 0 \]
Here:
- \(P(A \cap B)\): The joint probability of both \(A\) and \(B\) occurring.
- \(P(B)\): The probability of event \(B\).

## Bayes' Theorem
Bayes' Theorem is a fundamental result in probability theory that relates the conditional probabilities of two events. It provides a way to update our beliefs about a hypothesis (\(H\)) based on new evidence (\(E\)).

The formula for Bayes' Theorem is:
\[ P(H|E) = \frac{P(E|H)P(H)}{P(E)} \]
Here:
- \(P(H|E)\): The posterior probability of the hypothesis \(H\) given the evidence \(E\).
- \(P(E|H)\): The likelihood, or the probability of observing the evidence given the hypothesis.
- \(P(H)\): The prior probability of the hypothesis \(H\).
- \(P(E)\): The marginal probability of the evidence, calculated as:
  \[ P(E) = \sum_{i} P(E|H_i)P(H_i) \]
  where \(H_i\) represents all possible hypotheses.