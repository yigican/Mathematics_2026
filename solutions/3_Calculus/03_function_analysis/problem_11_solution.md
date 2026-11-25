# Problem 11. A Parameter and the Number of Extrema

## Question

For

$$
f_a(x)=x^3-3ax
$$

depending on $a$, determine the number of critical points and their character. Separate the parameter cases and justify why the structure of the graph changes.

> **Why this problem:** it teaches how to analyze an entire family of functions instead of a single example.

## Solution

For each real parameter $a$,

$$
f_a'(x)=3(x^2-a),\qquad f_a''(x)=6x.
$$

**If $a<0$:** the derivative is strictly positive for all $x$, so the graph is strictly increasing with no critical points and no extrema.

**If $a=0$:** the only critical point is $x=0$. The derivative $3x^2$ is positive on both sides of zero, so there is no extremum. The stationary point $(0,0)$ is an inflection point because $f_0''=6x$ changes sign there.

**If $a>0$:** the two critical points are $x=\pm\sqrt a$. The derivative is positive outside these roots and negative between them. Therefore $(-\sqrt a,2a^{3/2})$ is a local maximum and $(\sqrt a,-2a^{3/2})$ a local minimum.

**Check:** For $a>0$, the second derivative is negative at $-\sqrt a$ and positive at $\sqrt a$. As $a$ passes through zero the two real roots of $x^2=a$ merge and disappear, explaining the change in graph structure.
