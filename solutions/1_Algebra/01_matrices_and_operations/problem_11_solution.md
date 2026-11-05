# Exercise 11. When Do Matrices Commute?

## Question

Given

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
a & b \\
c & d \\
\end{pmatrix}.
$$

Find the conditions on $a,b,c,d$ under which $AB=BA$. Describe the general form of all such matrices $B$.

> **Why this exercise:** deepens the idea of noncommutativity by finding the conditions under which commutativity does hold.

## Solution

$$
A=\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad
B=\begin{pmatrix}
a & b \\
c & d \\
\end{pmatrix}.
$$

$$
AB=\begin{pmatrix}
a+c & b+d \\
c & d \\
\end{pmatrix},\qquad
BA=\begin{pmatrix}
a & a+b \\
c & c+d \\
\end{pmatrix}.
$$

Equating corresponding entries gives $a+c=a$, $b+d=a+b$, and $d=c+d$. Thus $c=0$ and $d=a$; $a$ and $b$ are arbitrary.

$$
B=\begin{pmatrix}
a & b \\
0 & a \\
\end{pmatrix}\qquad(a,b\in\mathbb{R}).
$$

**Check (sufficiency):** For every matrix of that form,

$$
AB=BA=\begin{pmatrix}
a & a+b \\
0 & a \\
\end{pmatrix}.
$$

So the derived conditions are both necessary and sufficient for commutativity in this example.
