# Problem 13. A Multi-Layer Composition

## Question

For

$$
f(x)=e^{\sin(x^2)}
$$

compute the derivative. First write the layers

$$
x\longrightarrow x^2\longrightarrow \sin(x^2)\longrightarrow e^{\sin(x^2)}
$$

and explain why differentiation moves through them in the reverse order.

> **Why this problem:** it develops the chain rule as a method for working with multiple layers.

## Solution

The layers are

$$
x\longrightarrow x^2\longrightarrow\sin(x^2)\longrightarrow e^{\sin(x^2)}.
$$

Differentiate the outer exponential, then multiply by the derivative of the sine layer, and finally by the derivative of the square. This reverse order follows the nested chain rule, since each outer rate is multiplied by the rate of its input.

$$
f'(x)=e^{\sin(x^2)}\cos(x^2)\,2x.
$$

**Check:** At $x=0$ the expression gives zero, which agrees with the fact that the differentiable original function is even.
