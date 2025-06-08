# Set Theory

[Back to Foundations](./index.md)

Set theory is the branch of mathematical logic that studies sets, which can be informally described as collections of objects.

## Basic Concepts

### Set
A **set** is a well-defined collection of distinct objects, considered as an object in its own right. The objects that make up a set are called its **elements** or **members**.

**Example:**
The set \(A\) containing the first three natural numbers is written as:
\[ A = \{1, 2, 3\} \]
The elements of this set are 1, 2, and 3. We can write \(1 \in A\), which means "1 is an element of A".

### Subset
A set \(A\) is a **subset** of a set \(B\) if every element of \(A\) is also an element of \(B\). This is denoted by \(A \subseteq B\).

**Example:**
If \(A = \{1, 2\}\) and \(B = \{1, 2, 3\}\), then \(A\) is a subset of \(B\).
If \(A = \{1, 2, 4\}\) and \(B = \{1, 2, 3\}\), then \(A\) is not a subset of \(B\) because \(4 \in A\) but \(4 \notin B\).

Every set is a subset of itself. A subset that is not equal to the original set is called a **proper subset**, denoted \(A \subset B\).

### Basic Set Operations

Given two sets \(A\) and \(B\):

*   **Union (\(\cup\))**: The union of \(A\) and \(B\), denoted \(A \cup B\), is the set of all objects that are a member of \(A\), or \(B\), or both.
    **Example:** If \(A = \{1, 2\}\) and \(B = \{2, 3\}\), then \(A \cup B = \{1, 2, 3\}\).

*   **Intersection (\(\cap\))**: The intersection of \(A\) and \(B\), denoted \(A \cap B\), is the set of all objects that are members of both \(A\) and \(B\).
    **Example:** If \(A = \{1, 2\}\) and \(B = \{2, 3\}\), then \(A \cap B = \{2\}\).

*   **Difference (\(-\) or \(\setminus\))**: The set difference of \(B\) from \(A\), denoted \(A \setminus B\), is the set of all members of \(A\) that are not members of \(B\).
    **Example:** If \(A = \{1, 2\}\) and \(B = \{2, 3\}\), then \(A \setminus B = \{1\}\).

*   **Complement**: If we are working within a universal set \(U\), the complement of a set \(A\), denoted \(A^c\) or \(A'\), is the set of all elements in \(U\) that are not in \(A\).
    **Example:** If \(U = \{1, 2, 3, 4, 5\}\) and \(A = \{1, 2\}\), then \(A^c = \{3, 4, 5\}\).

### Special Sets

*   **Empty Set (\(\emptyset\))**: The unique set having no elements. It is a subset of every set.
*   **Power Set (\(P(A)\))**: The set of all subsets of a set \(A\).
    **Example:** If \(A = \{1, 2\}\), then \(P(A) = \{\emptyset, \{1\}, \{2\}, \{1, 2\}\}\).

### Relations to other areas
Set theory is fundamental to all of mathematics. The concept of a [function](./../algebra/functions.md) is defined using sets. [Topology](./../geometry/topology.md) is built upon set theory. 