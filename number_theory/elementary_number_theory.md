# Elementary Number Theory

[Back to Number Theory](./index.md)

Elementary number theory is a branch of number theory that uses elementary methods to study the integers, without using techniques from other areas of mathematics. It is concerned with properties of integers such as divisibility, prime numbers, and congruences.

## Divisibility
An integer \(a\) is **divisible** by a non-zero integer \(b\) if there exists an integer \(c\) such that \(a = bc\). This is denoted as \(b | a\).

**Division Algorithm**: Given any integers \(a\) and \(b\) with \(b > 0\), there exist unique integers \(q\) (the quotient) and \(r\) (the remainder) such that \(a = bq + r\) and \(0 \le r < b\).

**Greatest Common Divisor (GCD)**: The GCD of two integers \(a\) and \(b\), denoted \(\text{gcd}(a, b)\), is the largest positive integer that divides both \(a\) and \(b\). The GCD can be found using the **Euclidean algorithm**.

## Prime Numbers
A **prime number** is a natural number greater than 1 that has no positive divisors other than 1 and itself. A natural number greater than 1 that is not prime is called a **composite number**.

**Fundamental Theorem of Arithmetic**: Every integer greater than 1 is either a prime number itself or can be represented as a product of prime numbers, and this representation is unique, up to the order of the factors.

**Example:**
\[ 1200 = 2^4 \cdot 3^1 \cdot 5^2 \]

## Modular Arithmetic (Congruences)
Two integers \(a\) and \(b\) are said to be **congruent modulo n**, written as
\[ a \equiv b \pmod{n} \]
if their difference \(a-b\) is an integer multiple of \(n\).

**Example:**
*   \(38 \equiv 14 \pmod{12}\) because \(38 - 14 = 24\), which is a multiple of 12.
*   The hours on a clock are an example of modular arithmetic modulo 12.

Modular arithmetic forms a ring, \(\mathbb{Z}/n\mathbb{Z}\), which is a field if and only if \(n\) is a prime number.

### Important Theorems in Modular Arithmetic
*   **Fermat's Little Theorem**: If \(p\) is a prime number, then for any integer \(a\), \(a^p \equiv a \pmod{p}\). If \(a\) is not divisible by \(p\), then \(a^{p-1} \equiv 1 \pmod{p}\).
*   **Euler's Totient Theorem**: If \(n\) and \(a\) are coprime positive integers, then \(a^{\phi(n)} \equiv 1 \pmod{n}\), where \(\phi(n)\) is Euler's totient function (which counts the positive integers up to a given integer \(n\) that are relatively prime to \(n\)).
*   **Chinese Remainder Theorem**: This theorem provides a way to solve a system of simultaneous congruences with different moduli, if the moduli are pairwise coprime. 