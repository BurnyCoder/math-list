# Enumerative Combinatorics

[Back to Combinatorics](./index.md)

Enumerative combinatorics is an area of combinatorics that deals with the number of ways that certain patterns can be formed. The two basic principles of counting are the **rule of sum** and the **rule of product**.

## Basic Counting Principles

### Permutations
A **permutation** is an arrangement of objects in a specific order. The number of permutations of \(n\) distinct objects is \(n!\) (n factorial).
\[ n! = n \times (n-1) \times \dots \times 2 \times 1 \]
If we want to choose and arrange \(k\) objects from a set of \(n\) objects, the number of ways is denoted by \(P(n, k)\) or \(nPk\).
\[ P(n, k) = \frac{n!}{(n-k)!} \]

**Example:**
How many ways can we arrange 3 books from a set of 5?
\(P(5, 3) = \frac{5!}{(5-3)!} = \frac{120}{2} = 60\).

### Combinations
A **combination** is a selection of objects from a collection, such that the order of selection does not matter. The number of combinations of \(k\) objects from a set of \(n\) objects is denoted by \(C(n, k)\) or \(\binom{n}{k}\) ("n choose k").
\[ \binom{n}{k} = \frac{n!}{k!(n-k)!} \]

**Example:**
How many ways can we choose 3 books from a set of 5?
\(\binom{5}{3} = \frac{5!}{3!(5-3)!} = \frac{120}{6 \times 2} = 10\).

## Binomial Theorem

The binomial theorem provides a formula for the expansion of \((x+y)^n\) for any positive integer \(n\).
\[ (x+y)^n = \sum_{k=0}^{n} \binom{n}{k} x^{n-k} y^k \]
The coefficients \(\binom{n}{k}\) are the binomial coefficients, which are the same numbers as from the combinations formula. They can be visualized in **Pascal's Triangle**.

## Inclusion-Exclusion Principle

The inclusion-exclusion principle is a counting technique which generalizes the familiar method of obtaining the number of elements in the union of two finite sets.
For two sets A and B:
\[ |A \cup B| = |A| + |B| - |A \cap B| \]
For three sets A, B, and C:
\[ |A \cup B \cup C| = |A| + |B| + |C| - (|A \cap B| + |A \cap C| + |B \cap C|) + |A \cap B \cap C| \]
This principle can be generalized to any number of sets. It is used to solve many common counting problems. 