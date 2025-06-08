# Complex Analysis

[Back to Analysis](./index.md)

Complex analysis is the branch of mathematical analysis that investigates functions of complex numbers. It is a powerful tool with a wide range of applications in other areas of mathematics and in physics and engineering.

## Core Concepts

### Complex Numbers
A **complex number** is a number that can be expressed in the form \(z = a + bi\), where \(a\) and \(b\) are real numbers, and \(i\) is the imaginary unit, satisfying the equation \(i^2 = -1\).
*   \(a\) is the **real part** of \(z\), denoted \(\text{Re}(z)\).
*   \(b\) is the **imaginary part** of \(z\), denoted \(\text{Im}(z)\).

Complex numbers can be represented as points in the **complex plane**, with a horizontal real axis and a vertical imaginary axis.
A complex number can also be written in **polar form**: \(z = r(\cos\theta + i\sin\theta) = re^{i\theta}\), where \(r = |z|\) is the modulus and \(\theta\) is the argument.

### Holomorphic Functions
A function \(f: U \to \mathbb{C}\) defined on an open subset \(U\) of the complex plane is said to be **holomorphic** (or analytic) at a point \(z_0\) if it is complex differentiable at \(z_0\). This means the following limit exists:
\[ f'(z_0) = \lim_{z \to z_0} \frac{f(z) - f(z_0)}{z - z_0} \]
This is much stronger than real differentiability. If a function is holomorphic on a domain, it is infinitely differentiable and can be represented by its Taylor series.

### Cauchy-Riemann Equations
A key test for holomorphicity is the Cauchy-Riemann equations. If we write \(f(z) = u(x,y) + i v(x,y)\) where \(z=x+iy\), then \(f\) is holomorphic if and only if \(u\) and \(v\) have continuous first partial derivatives and satisfy:
\[ \frac{\partial u}{\partial x} = \frac{\partial v}{\partial y} \quad \text{and} \quad \frac{\partial u}{\partial y} = -\frac{\partial v}{\partial x} \]

### Contour Integration
Contour integration is a method of evaluating certain integrals along paths in the complex plane.

**Cauchy's Integral Theorem**: If \(f(z)\) is holomorphic in a simply connected domain \(D\), then for any closed path \(\gamma\) in \(D\), the contour integral of \(f(z)\) along \(\gamma\) is zero.
\[ \oint_\gamma f(z) dz = 0 \]

**Cauchy's Integral Formula**: This is a central result which states that a holomorphic function defined on a disk is completely determined by its values on the boundary of the disk.
\[ f(a) = \frac{1}{2\pi i} \oint_\gamma \frac{f(z)}{z-a} dz \]

### Residue Theorem
The residue theorem is a powerful tool to evaluate line integrals of analytic functions over closed curves; it can also be used to compute real integrals.
It states that the value of a contour integral of a function with isolated singularities is \(2\pi i\) times the sum of the residues of the function at the singularities enclosed by the contour.
\[ \oint_\gamma f(z) dz = 2\pi i \sum_{k=1}^n \text{Res}(f, a_k) \] 