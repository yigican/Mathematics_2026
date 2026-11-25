# Problem 7. A Trigonometric Function

## Question

On $[0,2\pi]$, find the intervals of monotonicity and the extrema of

$$
f(x)=\sin x+\cos x.
$$

Include the endpoints of the interval and compare the function values at the critical points and at the endpoints.

> **Why this problem:** it practices the analysis of a periodic function on a bounded interval.

## Solution

Differentiation gives

$$
f'(x)=\cos x-\sin x.
$$

The critical points in $[0,2\pi]$ satisfy $\tan x=1$, giving $x=\pi/4$ and $x=5\pi/4$. Testing the derivative at $0,\pi,3\pi/2$ gives signs $+,-,+$, respectively. Therefore the function increases on $[0,\pi/4]$, decreases on $[\pi/4,5\pi/4]$, and increases on $[5\pi/4,2\pi]$.

Compare the endpoint and critical values:

| Point | Function value |
|---|---|
| $0$ | $1$ |
| $\pi/4$ | $\sqrt2$ |
| $5\pi/4$ | $-\sqrt2$ |
| $2\pi$ | $1$ |

The absolute maximum is $\sqrt2$ at $\pi/4$ and the absolute minimum is $-\sqrt2$ at $5\pi/4$. Neither endpoint is an absolute extremum; relative to the closed domain, $0$ is a one-sided local minimum and $2\pi$ a one-sided local maximum.

**Check:** The identity $f(x)=\sqrt2\sin(x+\pi/4)$ bounds the function between $-\sqrt2$ and $\sqrt2$ and confirms both absolute extrema.
