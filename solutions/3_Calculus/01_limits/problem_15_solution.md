# Exercise 15. Observation Versus Proof

## Question

Choose one sequence and one function from this set. For the sequence, compute several values for increasingly large $n$. For the function, prepare a table of values with arguments approaching the limit point from the left and right. Sketch the behavior of both objects.

Compare the observation with the analytical result and explain why a finite number of calculations or a sketch does not constitute a proof that the limit exists.

> **Why this exercise:** teaches how to distinguish intuition and observation from mathematical argument.

## Solution

Choose $a_n=(4n^2-3n+1)/(2n^2+5n-7)$ from Exercise 1 and $g(x)=(x^2-4x+3)/(x-3)$ from Exercise 7.

For $n=10,100,1000$, the sequence values are approximately $371/243\approx1.52675$, $39701/20493\approx1.9373$, and $3997001/2004993\approx1.9935$. Its horizontal sketch approaches $y=2$ from below.

For $x=2.9,2.99,3.01,3.1$, $g(x)=x-1$ yields $1.9,1.99,2.01,2.1$. A sketch is the line $y=x-1$ with a hole at $(3,2)$.

Analytically, division by $n^2$ proves $a_n\to2$, while cancellation for $x\neq3$ proves $g(x)\to2$. Tables and sketches suggest these limits but cannot exclude unexpected behavior at unexamined arguments.
