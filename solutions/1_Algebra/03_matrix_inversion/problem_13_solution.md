# Exercise 13. Undoing a Composite Transformation

$$
S=\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad
H=\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}.
$$

**Method 1 — multiply first:** The composite transformation is

$$
T=HS=\begin{pmatrix}
2 & 1 \\
0 & 1 \\
\end{pmatrix}.
$$

Since $\det T=2$, the $2\times2$ inverse formula gives

$$
T^{-1}=\frac12\begin{pmatrix}
1 & -1 \\
0 & 2 \\
\end{pmatrix}
=\begin{pmatrix}
\frac12 & -\frac12 \\
0 & 1 \\
\end{pmatrix}.
$$

**Method 2 — reverse the factors:** Individually,

$$
S^{-1}=\begin{pmatrix}
\frac12 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad
H^{-1}=\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix}.
$$

Then

$$
(HS)^{-1}=S^{-1}H^{-1}
=\begin{pmatrix}
\frac12 & -\frac12 \\
0 & 1 \\
\end{pmatrix},
$$

in agreement with Method 1.

The **incorrect order** gives a different result:

$$
H^{-1}S^{-1}
=\begin{pmatrix}
\frac12 & -1 \\
0 & 1 \\
\end{pmatrix}\neq T^{-1}.
$$

**Check:** $TT^{-1}=I$, whereas

$$
T(H^{-1}S^{-1})=\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix}\neq I.
$$

**Explanation:** $T=HS$ applies $S$ first and then $H$. To undo the composite action, undo $H$ first and then $S$; hence the inverse product is $S^{-1}H^{-1}$.
