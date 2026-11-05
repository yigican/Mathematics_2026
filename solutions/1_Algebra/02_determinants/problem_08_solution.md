# Exercise 8. Determinant of a Product

Given $\det A=3$ and $\det B=-5$, use

$$
\det(XY)=\det X\,\det Y.
$$

Then

$$
\det(AB)=3(-5)=-15
$$

and, with the factors reversed,

$$
\det(BA)=(-5)3=-15.
$$

Because $\det A=3\neq0$, $A^{-1}$ exists, with

$$
\det(A^{-1})=\frac{1}{\det A}=\frac13.
$$

Consequently,

$$
\det(A^{-1}B)=\frac13(-5)=-\frac53.
$$

**Explanation and check:** Matrix multiplication usually is not commutative, but scalar multiplication is. Hence $\det(AB)=\det A\det B=\det B\det A=\det(BA)$. The inverse property also checks out because $\det A\,\det(A^{-1})=3(1/3)=1=\det I$.
