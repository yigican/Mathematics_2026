# Exercise 13. Undoing a Composite Transformation

## Question

The matrices

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad H=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
$$

describe nonuniform scaling and shear. For $T=HS$, find $T^{-1}$ in two ways:

1. first compute $T$, then its inverse,
2. use $(HS)^{-1}=S^{-1}H^{-1}$.

Compare the results. Additionally compute $H^{-1}S^{-1}$ and verify that the incorrect order gives a different matrix. Explain the rule: “when undoing a composition of operations, we undo them from the end.”

> **Why this exercise:** reinforces the inverse of a product in a less direct configuration.

## Solution

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
