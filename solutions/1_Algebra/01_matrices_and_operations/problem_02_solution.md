# Exercise 2. Addition and Scalar Multiplication

$$
A=\begin{pmatrix}
1 & 2 \\
-1 & 3 \\
\end{pmatrix},\qquad
B=\begin{pmatrix}
4 & -2 \\
0 & 5 \\
\end{pmatrix}.
$$

Addition and subtraction are performed entry by entry:

$$
A+B=\begin{pmatrix}
1+4 & 2+(-2) \\
-1+0 & 3+5 \\
\end{pmatrix}
=\begin{pmatrix}
5 & 0 \\
-1 & 8 \\
\end{pmatrix},
$$

$$
A-B=\begin{pmatrix}
1-4 & 2-(-2) \\
-1-0 & 3-5 \\
\end{pmatrix}
=\begin{pmatrix}
-3 & 4 \\
-1 & -2 \\
\end{pmatrix},
$$

$$
3A-2B=\begin{pmatrix}
3 & 6 \\
-3 & 9 \\
\end{pmatrix}
-\begin{pmatrix}
8 & -4 \\
0 & 10 \\
\end{pmatrix}
=\begin{pmatrix}
-5 & 10 \\
-3 & -1 \\
\end{pmatrix}.
$$

**Why sizes must match:** An entry of one matrix can be added to the corresponding entry of another matrix only if both matrices have the same number of rows and columns.

**Check:** $(A+B)-B=A$, since

$$
\begin{pmatrix}
5 & 0 \\
-1 & 8 \\
\end{pmatrix}-\begin{pmatrix}
4 & -2 \\
0 & 5 \\
\end{pmatrix}=\begin{pmatrix}
1 & 2 \\
-1 & 3 \\
\end{pmatrix}.
$$
