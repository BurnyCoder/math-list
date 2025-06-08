# Real Analysis

[Back to Analysis](./index.md)

Real analysis is a branch of mathematical analysis that studies the behavior of real numbers, sequences and series of real numbers, and real-valued functions. It is a rigorous formulation of the concepts found in calculus.

## Core Concepts

### Sequences and Limits
A **sequence** of real numbers is a function from the natural numbers to the real numbers, \(a: \mathbb{N} \to \mathbb{R}\), usually denoted \((a_n)\).

A sequence \((a_n)\) has a **limit** \(L \in \mathbb{R}\) if the numbers \(a_n\) get closer and closer to \(L\) as \(n\) becomes very large.
Formally, we say \(\lim_{n \to \infty} a_n = L\) if for every \(\epsilon > 0\), there exists a natural number \(N\) such that for every \(n \ge N\), we have \(|a_n - L| < \epsilon\).

**Example:**
The sequence \(a_n = 1/n\) converges to the limit 0.

### Series
A **series** is the sum of the terms of an infinite sequence of numbers.
Given a sequence \((a_n)\), the corresponding series is \(S = \sum_{n=1}^{\infty} a_n\).
The **partial sum** \(S_k\) is the sum of the first \(k\) terms: \(S_k = \sum_{n=1}^{k} a_n\).
The series **converges** to a limit \(L\) if the sequence of its partial sums \((S_k)\) converges to \(L\).

**Example:**
The geometric series \(\sum_{n=0}^{\infty} r^n\) converges to \(\frac{1}{1-r}\) if \(|r| < 1\).

### Continuity
A function \(f: \mathbb{R} \to \mathbb{R}\) is **continuous** at a point \(c \in \mathbb{R}\) if \(\lim_{x \to c} f(x) = f(c)\).
This means that small changes in the input \(x\) result in small changes in the output \(f(x)\).

**Epsilon-Delta Definition:** A function \(f\) is continuous at \(c\) if for every \(\epsilon > 0\), there exists a \(\delta > 0\) such that for all \(x\) with \(|x-c| < \delta\), we have \(|f(x) - f(c)| < \epsilon\).

### Differentiation and Integration
Real analysis provides the formal, rigorous proofs for the concepts of differentiation and integration introduced in calculus. It uses the limit definitions to build up the theory of derivatives (e.g., Mean Value Theorem, Taylor's Theorem) and the Riemann or Lebesgue integral.

### Uniform Convergence
Uniform convergence is a stronger type of convergence than pointwise convergence for a sequence of functions. It is crucial for justifying the interchange of limit operations, such as swapping a limit with an integral or a derivative.
A sequence of functions \((f_n)\) converges uniformly to \(f\) on a set \(E\) if for every \(\epsilon > 0\), there exists an \(N\) such that for all \(x \in E\) and all \(n \ge N\), \(|f_n(x) - f(x)| < \epsilon\). 