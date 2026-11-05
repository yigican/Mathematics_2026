# Exercise 12. Formula for a Matrix Power

$$
A=\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}.
$$

Direct multiplication produces

$$
A^2=\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\quad
A^3=\begin{pmatrix}
1 & 3 \\
0 & 1 \\
\end{pmatrix},\quad
A^4=\begin{pmatrix}
1 & 4 \\
0 & 1 \\
\end{pmatrix}.
$$

The conjecture is

$$
A^n=\begin{pmatrix}
1 & n \\
0 & 1 \\
\end{pmatrix}\quad(n\ge0).
$$

**Proof by induction:** For $n=0$, $A^0=I$, so the formula holds. Assume that the proposed formula holds for some $n\ge0$. Then

$$
A^{n+1}=A^nA
=\begin{pmatrix}
1 & n \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
=\begin{pmatrix}
1 & n+1 \\
0 & 1 \\
\end{pmatrix}.
$$

This is exactly the same formula with $n$ replaced by $n+1$. By induction, the formula holds for all nonnegative integers $n$.
