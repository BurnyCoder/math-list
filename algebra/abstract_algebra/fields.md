# Fields

[Back to Abstract Algebra](./index.md)

A **field** is a special type of ring where every non-zero element has a multiplicative inverse. Fields are fundamental in many areas of mathematics, including algebra, number theory, and analysis.

## Definition

A field is a non-trivial commutative ring \((F, +, \cdot)\) in which every non-zero element has a multiplicative inverse. In more detail, a set \(F\) with two operations \(+\) and \(\cdot\) is a field if it satisfies the following axioms:

1.  **\((F, +)\) is an abelian group**:
    *   Closure, Associativity, Commutativity of addition.
    *   Existence of an additive identity (0).
    *   Existence of additive inverses for all elements.

2.  **\((F \setminus \{0\}, \cdot)\) is an abelian group**:
    *   Let \(F^* = F \setminus \{0\}\).
    *   Closure, Associativity, Commutativity of multiplication for elements in \(F^*\).
    *   Existence of a multiplicative identity (1).
    *   Existence of multiplicative inverses for all non-zero elements.

3.  **Distributivity of multiplication over addition**:
    *   For all \(a, b, c \in F\), \(a \cdot (b+c) = (a \cdot b) + (a \cdot c)\).

Essentially, a field is a set where you can perform addition, subtraction, multiplication, and division (by non-zero elements).

## Examples

*   The set of **rational numbers** \(\mathbb{Q}\) is a field.
*   The set of **real numbers** \(\mathbb{R}\) is a field.
*   The set of **complex numbers** \(\mathbb{C}\) is a field.
*   The set of **integers** \(\mathbb{Z}\) is **not** a field, because most integers do not have a multiplicative inverse that is also an integer (e.g., the inverse of 2 is 1/2, which is not an integer).
*   **Finite Fields**: There exist fields with a finite number of elements. The simplest example is \(\mathbb{Z}_p\) (the integers modulo a prime \(p\)). For example, \(\mathbb{Z}_2 = \{0, 1\}\) is a field with two elements.

## Relationship to other structures

*   Every **field** is a **ring**.
*   Every **field** is an **integral domain** (a commutative ring with no zero divisors).
*   A **ring** is a **field** if and only if it is a commutative ring in which every non-zero element has a multiplicative inverse.
*   A finite integral domain is always a field.

This gives a hierarchy of structures:
**Fields** \(\subset\) **Euclidean Domains** \(\subset\) **Principal Ideal Domains** \(\subset\) **Unique Factorization Domains** \(\subset\) **Integral Domains** \(\subset\) **Commutative Rings** \(\subset\) **Rings**. 