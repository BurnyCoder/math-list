# Groups

[Back to Abstract Algebra](./index.md)

A **group** is a fundamental algebraic structure, which consists of a set of elements equipped with a single binary operation that satisfies a few basic axioms.

## Definition

A group is a set \(G\) together with a binary operation \(*\) (called the group law of \(G\)) that combines any two elements \(a\) and \(b\) to form an element, denoted \(a * b\), such that the following four group axioms are satisfied:

1.  **Closure**: For all \(a, b \in G\), the result of the operation, \(a * b\), is also in \(G\).
2.  **Associativity**: For all \(a, b, c \in G\), \((a * b) * c = a * (b * c)\).
3.  **Identity element**: There exists an element \(e \in G\) (called the identity element) such that for every element \(a \in G\), the equation \(e * a = a * e = a\) holds.
4.  **Inverse element**: For each \(a \in G\), there exists an element \(b \in G\) (called the inverse element) such that \(a * b = b * a = e\), where \(e\) is the identity element. The inverse of \(a\) is often denoted as \(a^{-1}\).

## Examples

*   The set of **integers** \(\mathbb{Z}\) with the addition operation \(+\).
    *   Closure: The sum of two integers is an integer.
    *   Associativity: \((a+b)+c = a+(b+c)\).
    *   Identity element: 0, since \(a+0 = a\).
    *   Inverse element: For any integer \(a\), its inverse is \(-a\), since \(a + (-a) = 0\).

*   The set of **non-zero rational numbers** \(\mathbb{Q} \setminus \{0\}\) with the multiplication operation \(\times\).
    *   Closure: The product of two non-zero rational numbers is a non-zero rational number.
    *   Associativity: \((a \times b) \times c = a \times (b \times c)\).
    *   Identity element: 1, since \(a \times 1 = a\).
    *   Inverse element: For any \(q = a/b\), its inverse is \(1/q = b/a\).

*   The set of **symmetries of a square** (the dihedral group \(D_4\)). The elements are the transformations (rotations and reflections) that leave the square invariant, and the operation is composition of transformations.

## Abelian Groups

A group \((G, *)\) is called **abelian** (or commutative) if the group operation is commutative, i.e., for all \(a, b \in G\), \(a * b = b * a\).

**Examples:**
*   The integers with addition, \((\mathbb{Z}, +)\), is an abelian group.
*   The non-zero rationals with multiplication, \((\mathbb{Q}\setminus\{0\}, \times)\), is an abelian group.
*   The symmetry group of a square, \(D_4\), is *not* abelian. For example, a rotation followed by a reflection is not the same as the reflection followed by the rotation.

## Subgroups

A **subgroup** \(H\) of a group \((G, *)\) is a subset of \(G\) that also forms a group under the same operation \(*\). This means that \(H\) must be closed under the operation, contain the identity element of \(G\), and contain the inverse of each of its elements.

**Example:**
The set of even integers is a subgroup of \((\mathbb{Z}, +)\). 