# Linear Algebra

[Back to Algebra](./index.md)

Linear algebra is the branch of mathematics concerning linear equations, linear maps, and their representations in vector spaces and through matrices.

## Core Concepts

### Vectors and Vector Spaces
A **vector space** (or linear space) is a set of objects called **vectors**, which may be added together and multiplied ("scaled") by numbers called **scalars**. Scalars are often taken to be real numbers, but there are also vector spaces with scalar multiplication by complex numbers, rational numbers, or generally any field.

For a set \(V\) to be a vector space over a field \(F\), it must satisfy a set of axioms, including closure under addition and scalar multiplication, associativity, commutativity of addition, existence of identity and inverse elements for addition, and distributivity.

**Example:**
*   The set \(\mathbb{R}^n\) of n-tuples of real numbers is a vector space over the real numbers \(\mathbb{R}\). A vector in \(\mathbb{R}^3\) looks like \((x, y, z)\).
*   Vector addition: \((x_1, y_1, z_1) + (x_2, y_2, z_2) = (x_1+x_2, y_1+y_2, z_1+z_2)\).
*   Scalar multiplication: \(c \cdot (x, y, z) = (cx, cy, cz)\).

### Matrices
A **matrix** is a rectangular array of numbers, symbols, or expressions, arranged in rows and columns. Matrices are used to represent linear transformations and to solve systems of linear equations.

**Example:**
A \(2 \times 3\) matrix:
\[ A = \begin{pmatrix} 1 & 9 & -13 \\ 20 & 5 & -6 \end{pmatrix} \]

Matrix operations include:
*   **Addition**: Adding two matrices of the same size by adding corresponding entries.
*   **Scalar Multiplication**: Multiplying a matrix by a scalar.
*   **Matrix Multiplication**: A more complex operation that produces a new matrix from two matrices.

### Linear Transformations
A **linear transformation** (or linear map) is a mapping \(T: V \rightarrow W\) between two vector spaces that preserves the operations of vector addition and scalar multiplication.
That is, for any vectors \(u, v \in V\) and any scalar \(c \in F\):
1.  \(T(u+v) = T(u) + T(v)\)
2.  \(T(c \cdot u) = c \cdot T(u)\)

Every linear transformation between finite-dimensional vector spaces can be represented by a matrix.

### Eigenvalues and Eigenvectors
For a given linear transformation, an **eigenvector** is a non-zero vector that changes at most by a scalar factor when that linear transformation is applied to it. The corresponding scalar is called the **eigenvalue**.

Formally, if \(A\) is a matrix representing a linear transformation, and \(v\) is a non-zero vector, then \(v\) is an eigenvector of \(A\) if \(Av = \lambda v\) for some scalar \(\lambda\). The scalar \(\lambda\) is the eigenvalue corresponding to \(v\).

Eigenvalues and eigenvectors are very important in many areas of science and engineering, for example in studying vibrations, stability analysis, and quantum mechanics.

### Systems of Linear Equations
A central problem in linear algebra is solving systems of linear equations.
**Example:**
\[
\begin{align*}
2x + y - z &= 8 \\
-3x - y + 2z &= -11 \\
-2x + y + 2z &= -3
\end{align*}
\]
This system can be written in matrix form as \(Ax = b\), where:
\[ A = \begin{pmatrix} 2 & 1 & -1 \\ -3 & -1 & 2 \\ -2 & 1 & 2 \end{pmatrix}, \quad x = \begin{pmatrix} x \\ y \\ z \end{pmatrix}, \quad b = \begin{pmatrix} 8 \\ -11 \\ -3 \end{pmatrix} \]
Techniques like Gaussian elimination or using matrix inverses can be used to find the solution for the vector \(x\). 