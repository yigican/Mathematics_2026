# Exercise 15. Classifying Three Systems

**System 1**

$$
\begin{cases}
x+y=2,\\
x-y=0.
\end{cases}
$$

Subtract the first equation from the second:

$$
-2y=-2\quad\Longrightarrow\quad y=1,\qquad x=1.
$$

There is **exactly one solution**, $(1,1)$. Both equations check: $1+1=2$ and $1-1=0$.

**System 2**

$$
\begin{cases}
x+y=2,\\
2x+2y=4.
\end{cases}
$$

Apply $R_2\leftarrow R_2-2R_1$. The second equation becomes $0=0$, leaving only $x+y=2$. There are **infinitely many solutions**:

$$
(x,y)=(2-t,t),\qquad t\in\mathbb{R}.
$$

Substitution confirms both equations for every $t$.

**System 3**

$$
\begin{cases}
x+y=2,\\
2x+2y=5.
\end{cases}
$$

The same elimination, $R_2\leftarrow R_2-2R_1$, gives $0=1$. This is impossible, so there is **no solution**.

**Comparison:** A nonzero pivot in both variables gives a unique solution (System 1); a zero row with zero right-hand side leaves a free variable (System 2); a zero row with a nonzero right-hand side gives a contradiction (System 3).
