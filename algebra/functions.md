# Functions

[Back to Algebra](./index.md)

In mathematics, a **function** is a binary relation between two sets that associates every element of the first set to exactly one element of the second set.

## Definition

Let \(A\) and \(B\) be two non-empty sets. A function \(f\) from \(A\) to \(B\), denoted \(f: A \rightarrow B\), is a rule that assigns to each element \(a \in A\) exactly one element \(b \in B\).

The set \(A\) is called the **domain** of the function, and the set \(B\) is called the **codomain**.

The element \(b \in B\) that is assigned to \(a \in A\) is denoted by \(f(a)\) and is called the **image** of \(a\) under \(f\), or the **value** of \(f\) at \(a\).

The **range** of the function is the set of all images of elements in the domain. The range is a subset of the codomain.

**Example:**
Let \(A = \{1, 2, 3\}\) and \(B = \{a, b, c, d\}\).
Let \(f: A \rightarrow B\) be defined by \(f(1) = a\), \(f(2) = b\), \(f(3) = a\).
*   The domain is \(\{1, 2, 3\}\).
*   The codomain is \(\{a, b, c, d\}\).
*   The range is \(\{a, b\}\).
*   This is a valid function because every element in \(A\) is mapped to exactly one element in \(B\).

## Types of Functions

### Injective (One-to-One)
A function \(f: A \rightarrow B\) is **injective** if for every two distinct elements \(a_1, a_2 \in A\), their images are distinct, i.e., \(f(a_1) \neq f(a_2)\).
Equivalently, if \(f(a_1) = f(a_2)\), then \(a_1 = a_2\).

**Example:**
\(f(x) = 2x\) from \(\mathbb{R}\) to \(\mathbb{R}\) is injective.

### Surjective (Onto)
A function \(f: A \rightarrow B\) is **surjective** if for every element \(b \in B\), there is at least one element \(a \in A\) such that \(f(a) = b\). In other words, the range is equal to the codomain.

**Example:**
\(f(x) = x^3\) from \(\mathbb{R}\) to \(\mathbb{R}\) is surjective.

### Bijective (One-to-One and Onto)
A function is **bijective** if it is both injective and surjective. A bijective function has an inverse function.

**Example:**
\(f(x) = x + 1\) from \(\mathbb{R}\) to \(\mathbb{R}\) is bijective.

## Composition of Functions

Given two functions \(f: A \rightarrow B\) and \(g: B \rightarrow C\), the **composition** of \(g\) with \(f\), denoted \(g \circ f\), is a function from \(A\) to \(C\) defined by:
\[ (g \circ f)(x) = g(f(x)) \]
for every \(x \in A\).

**Example:**
Let \(f(x) = x+1\) and \(g(x) = x^2\).
*   \((g \circ f)(x) = g(f(x)) = g(x+1) = (x+1)^2\)
*   \((f \circ g)(x) = f(g(x)) = f(x^2) = x^2+1\)
Note that function composition is not always commutative. 