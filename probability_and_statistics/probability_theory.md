# Probability Theory

[Back to Probability and Statistics](./index.md)

Probability theory is the branch of mathematics concerned with probability. Although there are several different probability interpretations, probability theory treats the concept in a rigorous mathematical manner by expressing it through a set of axioms.

## Kolmogorov Axioms

Modern probability theory is based on three axioms, known as the Kolmogorov axioms:

Let \((\Omega, F, P)\) be a probability space.
*   \(\Omega\) is the **sample space**, the set of all possible outcomes.
*   \(F\) is the **event space**, a set of subsets of \(\Omega\). An event is a set of outcomes.
*   \(P\) is the **probability measure**, a function that assigns a probability to each event.

1.  **Non-negativity**: The probability of an event is a non-negative real number.
    \[ P(E) \ge 0 \quad \forall E \in F \]
2.  **Unit Measure**: The probability of the entire sample space is 1.
    \[ P(\Omega) = 1 \]
3.  **Additivity**: For any sequence of disjoint events \(E_1, E_2, \dots\), the probability of their union is the sum of their probabilities.
    \[ P\left(\bigcup_{i=1}^{\infty} E_i\right) = \sum_{i=1}^{\infty} P(E_i) \]

## Random Variables

A **random variable** is a variable whose value is a numerical outcome of a random phenomenon.
*   A **discrete random variable** can take on a finite or countably infinite number of values.
*   A **continuous random variable** can take on any value in a given range.

The behavior of a random variable is described by its **probability distribution**. For a discrete random variable, this is the **probability mass function (PMF)**, which gives the probability of each possible value. For a continuous random variable, it is the **probability density function (PDF)**, where the probability of falling within a range is the integral of the PDF over that range.

## Conditional Probability and Independence

**Conditional Probability**: The probability of an event A occurring, given that event B has already occurred. It is denoted by \(P(A|B)\) and is calculated as:
\[ P(A|B) = \frac{P(A \cap B)}{P(B)} \]
assuming \(P(B) > 0\).

**Independence**: Two events A and B are **independent** if the occurrence of one does not affect the probability of the other. This is true if and only if:
\[ P(A \cap B) = P(A)P(B) \]

**Bayes' Theorem**: A fundamental theorem that describes the probability of an event, based on prior knowledge of conditions that might be related to the event.
\[ P(A|B) = \frac{P(B|A)P(A)}{P(B)} \]

## Expected Value and Variance

*   **Expected Value (E[X])**: The long-run average value of a random variable. It is a weighted average of all possible values, where the weights are the probabilities. For a discrete random variable \(X\):
    \[ E[X] = \sum_i x_i P(X=x_i) \]
*   **Variance (Var(X))**: A measure of how spread out the values of a random variable are from its expected value.
    \[ \text{Var}(X) = E[(X - E[X])^2] = E[X^2] - (E[X])^2 \]
The square root of the variance is the **standard deviation**. 