# Problem 15. The Difference Quotient as a Check of the Derivative

## Question

Choose one function from the problem set and a point $x_0$ at which the derivative exists. Compute $f'(x_0)$ exactly, and then calculate

$$
\frac{f(x_0+h)-f(x_0)}h
$$

for $h=1$, $0.1$, and $0.01$. Compare the values with $f'(x_0)$ and explain why the difference quotient approaching a single number is consistent with the definition of the derivative, while a few computations do not replace a limit argument.

> **Why this problem:** it connects the definition of the derivative with concrete calculations and teaches the distinction between observation and proof.

## Solution

Choose the polynomial $f(x)=x^2-3x+1$ from Problem 10 and the point $x_0=2$. The exact derivative is $f'(x)=2x-3$, so $f'(2)=1$.

Since $f(2)=-1$ and $f(2+h)=-1+h+h^2$, the difference quotient for $h\neq0$ is

$$
\frac{f(2+h)-f(2)}{h}=1+h.
$$

| $h$ | Difference quotient |
|---:|---:|
| 1 | 2 |
| 0.1 | 1.1 |
| 0.01 | 1.01 |

The values approach the exact derivative $1$ as the increment decreases.

**Verification:** The exact expression $1+h$ tends to $1$ as $h\to0$ from either side. The three numerical values illustrate this behavior but cannot alone prove the limit.
