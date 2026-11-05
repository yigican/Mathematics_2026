# Exercise 13. A Recurrence Written in Matrix Form

## Question

Let

$$
F=
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix}.
$$

Compute $F^2$, $F^3$, $F^4$, and $F^5$. Compare the numbers obtained with the sequence

$$
0,1,1,2,3,5,8,\ldots
$$

and describe the relationship you observe. Then compute

$$
F
\begin{pmatrix}
a \\
b \\
\end{pmatrix}
$$

and explain how this multiplication performs one recurrence step: it creates the sum of two consecutive terms and keeps one of them for the next step.

> **Why this exercise:** shows the connection between matrix powers and a simple numerical recurrence.

## Solution

$$
F=\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix}.
$$

Repeated multiplication gives

$$
F^2=\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix},\qquad
F^3=\begin{pmatrix}
3 & 2 \\
2 & 1 \\
\end{pmatrix},
$$

$$
F^4=\begin{pmatrix}
5 & 3 \\
3 & 2 \\
\end{pmatrix},\qquad
F^5=\begin{pmatrix}
8 & 5 \\
5 & 3 \\
\end{pmatrix}.
$$

**Relationship:** The entries are Fibonacci numbers $0,1,1,2,3,5,8,\ldots$, where $f_0=0$, $f_1=1$, and $f_{n+1}=f_n+f_{n-1}$. Specifically,

$$
F^n=\begin{pmatrix}
f_{n+1} & f_n \\
f_n & f_{n-1} \\
\end{pmatrix}\quad(n\ge1).
$$

For any numbers $a,b$,

$$
F\begin{pmatrix}
a \\
b \\
\end{pmatrix}
=\begin{pmatrix}
a+b \\
a \\
\end{pmatrix}.
$$

**Explanation and check:** If $a$ and $b$ are two consecutive Fibonacci numbers with $a$ the more recent one, then $a+b$ is the next number and $a$ is retained for the next step. For example, $F(3,2)^T=(5,3)^T$, followed by $F(5,3)^T=(8,5)^T$.
