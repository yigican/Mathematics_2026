# Exercise 7. Identity Matrix, Zero Matrix, and Powers

$$
A=\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix},\qquad
I=\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad
0=\begin{pmatrix}
0 & 0 \\
0 & 0 \\
\end{pmatrix}.
$$

$$
AI=\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix},\quad
IA=\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix},\quad
A+0=\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix}.
$$

$$
A^2=A\cdot A=\begin{pmatrix}
4 & 2+2 \\
0 & 4 \\
\end{pmatrix}
=\begin{pmatrix}
4 & 4 \\
0 & 4 \\
\end{pmatrix}.
$$

$$
A^3=A^2A=\begin{pmatrix}
4 & 4 \\
0 & 4 \\
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix}
=\begin{pmatrix}
8 & 12 \\
0 & 8 \\
\end{pmatrix}.
$$

**Explanation:** $I$ is the multiplicative identity and $0$ is the additive identity. The diagonal entries double at each power; the upper-right entries follow $1,4,12,\ldots$. More generally,

$$
A^n=\begin{pmatrix}
2^n & n2^{n-1} \\
0 & 2^n \\
\end{pmatrix}\quad(n\ge1).
$$

**Check:** For $n=2$ and $n=3$, the upper-right formula gives $2\cdot2=4$ and $3\cdot4=12$, as calculated directly.
