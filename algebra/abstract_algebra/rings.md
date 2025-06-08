# Rings

[Back to Abstract Algebra](./index.md)

A **ring** is another fundamental algebraic structure that generalizes the arithmetic of integers. A ring is a set equipped with two binary operations that generalize the operations of addition and multiplication.

## Definition

A ring is a set \(R\) equipped with two binary operations \(+\) and \(\cdot\) (called addition and multiplication) satisfying the following axioms:

1.  \((R, +)\) is an **abelian group**:
    *   **Closure under addition**: For all \(a, b \in R\), \(a+b \in R\).
    *   **Associativity of addition**: For all \(a, b, c \in R\), \((a+b)+c = a+(b+c)\).
    *   **Identity element of addition**: There exists an element \(0 \in R\) such that for all \(a \in R\), \(a+0 = a\).
    *   **Inverse element of addition**: For each \(a \in R\), there exists \(-a \in R\) such that \(a+(-a) = 0\).
    *   **Commutativity of addition**: For all \(a, b \in R\), \(a+b = b+a\).

2.  \((R, \cdot)\) is a **monoid**:
    *   **Closure under multiplication**: For all \(a, b \in R\), \(a \cdot b \in R\).
    *   **Associativity of multiplication**: For all \(a, b, c \in R\), \((a \cdot b) \cdot c = a \cdot (b \cdot c)\).
    *   **Identity element of multiplication**: There exists an element \(1 \in R\) such that for all \(a \in R\), \(a \cdot 1 = 1 \cdot a = a\). (Some definitions of a ring do not require a multiplicative identity, calling such structures rngs. We assume rings have a 1).

3.  **Multiplication distributes over addition**:
    *   For all \(a, b, c \in R\), \(a \cdot (b+c) = (a \cdot b) + (a \cdot c)\) (left distributivity).
    *   For all \(a, b, c \in R\), \((b+c) \cdot a = (b \cdot a) + (c \cdot a)\) (right distributivity).

## Examples

*   The set of **integers** \(\mathbb{Z}\) with the usual addition and multiplication is a ring.
*   The set of **real numbers** \(\mathbb{R}\), the **rational numbers** \(\mathbb{Q}\), and the **complex numbers** \(\mathbb{C}\) are all rings.
*   The set of all \(n \times n\) matrices with real entries is a ring under matrix addition and multiplication.
*   The set of polynomials \(\mathbb{R}[x]\) with real coefficients is a ring under polynomial addition and multiplication.

## Commutative Rings

A ring \((R, +, \cdot)\) is **commutative** if its multiplication operation is commutative: for all \(a, b \in R\), \(a \cdot b = b \cdot a\).

**Examples:**
*   \(\mathbb{Z}\), \(\mathbb{Q}\), \(\mathbb{R}\), and \(\mathbb{C}\) are all commutative rings.
*   The ring of \(n \times n\) matrices (for \(n>1\)) is a non-commutative ring.

## Ideals

An **ideal** is a special subset of a ring that is closed under addition and absorbs multiplication by elements of the ring. An ideal \(I\) of a ring \(R\) is a subset of \(R\) such that:
1. \((I, +)\) is a subgroup of \((R, +)\).
2. For every \(r \in R\) and every \(x \in I\), both \(r \cdot x\) and \(x \cdot r\) are in \(I\).

**Example:**
The set of even integers is an ideal in the ring of integers \(\mathbb{Z}\). 