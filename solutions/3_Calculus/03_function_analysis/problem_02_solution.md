# Problem 2. A Parabola from the Perspective of the Derivative

## Question

For $f(x)=x^2-4x+1$, find the minimum using the derivative. Compare the result with the vertex form and explain why both approaches lead to the same point.

> **Why this problem:** it connects a new tool with the familiar geometry of a parabola.

## Solution

Differentiate the polynomial:

$$
f'(x)=2x-4=2(x-2).
$$

The derivative is negative for $x<2$ and positive for $x>2$. The function therefore has its unique global minimum at $x=2$, where $f(2)=4-8+1=-3$.

**Independent check by completing the square:**

$$
f(x)=(x-2)^2-3.
$$

Because a real square is nonnegative, the smallest value is $-3$, attained exactly at $x=2$. Both approaches identify the vertex $(2,-3)$: the derivative detects the change from decreasing to increasing, while the vertex form directly gives the smallest possible value.
