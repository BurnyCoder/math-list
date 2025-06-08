# Calculus

[Back to Analysis](./index.md)

Calculus is a major branch of mathematics that studies rates of change and accumulation. It has two major branches: differential calculus and integral calculus.

## Differential Calculus

Differential calculus is concerned with the study of the rates at which quantities change. It is based on the concept of the **derivative**.

### The Derivative
The derivative of a function of a real variable measures the sensitivity to change of the function value (output value) with respect to a change in its argument (input value). The derivative of a function \(f(x)\) at a point \(x_0\) is the slope of the tangent line to the graph of \(f\) at the point \((x_0, f(x_0))\).

The derivative of \(f(x)\) with respect to \(x\) is denoted as \(f'(x)\) or \(\frac{dy}{dx}\). It is defined as:
\[ f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h} \]

**Example:**
If \(f(x) = x^2\), then its derivative is \(f'(x) = 2x\). This means that the slope of the tangent to the parabola \(y=x^2\) at any point \(x\) is \(2x\).

### Rules of Differentiation
*   **Power Rule**: If \(f(x) = x^n\), then \(f'(x) = nx^{n-1}\).
*   **Product Rule**: \((f \cdot g)' = f'g + fg'\).
*   **Quotient Rule**: \((\frac{f}{g})' = \frac{f'g - fg'}{g^2}\).
*   **Chain Rule**: If \(h(x) = f(g(x))\), then \(h'(x) = f'(g(x)) \cdot g'(x)\).

## Integral Calculus

Integral calculus is concerned with the accumulation of quantities, and areas under and between curves. It is based on the concept of the **integral**.

### The Indefinite Integral
The indefinite integral, or **antiderivative**, of a function \(f\) is a differentiable function \(F\) whose derivative is equal to the original function \(f\).
\[ F'(x) = f(x) \]
It is written as \(\int f(x) dx\).

**Example:**
Since the derivative of \(x^2\) is \(2x\), the indefinite integral of \(2x\) is \(x^2\). Because the derivative of a constant is zero, the indefinite integral is not unique. So we write \(\int 2x dx = x^2 + C\), where \(C\) is an arbitrary constant of integration.

### The Definite Integral
The definite integral of a function \(f(x)\) from \(a\) to \(b\), denoted \(\int_a^b f(x) dx\), can be interpreted as the signed area of the region in the xy-plane that is bounded by the graph of \(f\), the x-axis and the vertical lines \(x=a\) and \(x=b\).

### The Fundamental Theorem of Calculus
The Fundamental Theorem of Calculus links differentiation and integration. It states that if \(f\) is a continuous function on a closed interval \([a, b]\) and \(F\) is its antiderivative, then:
\[ \int_a^b f(x) dx = F(b) - F(a) \]
This theorem provides a powerful method for evaluating definite integrals. 