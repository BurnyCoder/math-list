# Differential Equations

[Back to Analysis](./index.md)

A **differential equation** is a mathematical equation that relates some function with its derivatives. In applications, the functions usually represent physical quantities, the derivatives represent their rates of change, and the equation defines a relationship between the two.

## Ordinary Differential Equations (ODEs)

An ordinary differential equation is an equation containing a function of one independent variable and its derivatives.

### First-Order Linear ODEs
A first-order linear ODE can be written in the form:
\[ \frac{dy}{dx} + P(x)y = Q(x) \]
These can be solved using an integrating factor.

**Example: Population Growth**
A simple model of population growth is given by the ODE \(\frac{dP}{dt} = rP\), where \(P\) is the population size, \(t\) is time, and \(r\) is the growth rate. The solution is \(P(t) = P_0 e^{rt}\), representing exponential growth.

### Second-Order Linear ODEs
A second-order linear ODE has the form:
\[ a\frac{d^2y}{dx^2} + b\frac{dy}{dx} + cy = f(x) \]
These equations are fundamental in physics, describing phenomena like oscillations (e.g., pendulums, springs) and wave motion. The solution method depends on the roots of the characteristic equation \(ar^2 + br + c = 0\).

**Example: Simple Harmonic Motion**
The equation for a simple harmonic oscillator is \(m\frac{d^2x}{dt^2} + kx = 0\). The solution is of the form \(x(t) = A\cos(\omega t - \phi)\), where \(\omega = \sqrt{k/m}\).

## Partial Differential Equations (PDEs)

A partial differential equation is an equation which involves partial derivatives of a multi-variable function.

### Key Examples of PDEs

*   **Heat Equation**: Describes the distribution of heat in a given region over time.
    \[ \frac{\partial u}{\partial t} = \alpha \nabla^2 u = \alpha \left(\frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} + \frac{\partial^2 u}{\partial z^2}\right) \]
    Here, \(u(x,y,z,t)\) is the temperature and \(\alpha\) is the thermal diffusivity.

*   **Wave Equation**: Describes the propagation of waves (like sound, light, or water waves).
    \[ \frac{\partial^2 u}{\partial t^2} = c^2 \nabla^2 u \]
    Here, \(u\) is the amplitude of the wave and \(c\) is the wave speed.

*   **Laplace's Equation**: Describes the behavior of potentials (e.g., gravitational, electrostatic) in a steady state.
    \[ \nabla^2 u = \frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} + \frac{\partial^2 u}{\partial z^2} = 0 \]
    Functions that satisfy Laplace's equation are called harmonic functions.

Solving PDEs often involves techniques like separation of variables, Fourier series, and transforms. 