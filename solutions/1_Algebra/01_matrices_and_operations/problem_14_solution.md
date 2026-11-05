# Exercise 14. Rotation Matrices

## Question

The matrix for a rotation through an angle $\theta$ is

$$
R(\theta)=
\begin{pmatrix}
\cos\theta & -\sin\theta \\
\sin\theta & \cos\theta \\
\end{pmatrix}.
$$

Compute $R(\alpha)R(\beta)$ and, using the angle-sum formulas for sine and cosine, show that

$$
R(\alpha)R(\beta)=R(\alpha+\beta).
$$

Explain the result geometrically.

> **Why this exercise:** shows the consistency between matrix algebra and the geometry of composing rotations.

## Solution

$$
R(\theta)=\begin{pmatrix}
\cos\theta & -\sin\theta \\
\sin\theta & \cos\theta \\
\end{pmatrix}.
$$

Multiplying $R(\alpha)$ by $R(\beta)$ gives

$$
R(\alpha)R(\beta)=\begin{pmatrix}
\cos\alpha\cos\beta-\sin\alpha\sin\beta & -\cos\alpha\sin\beta-\sin\alpha\cos\beta \\
\sin\alpha\cos\beta+\cos\alpha\sin\beta & -\sin\alpha\sin\beta+\cos\alpha\cos\beta \\
\end{pmatrix}.
$$

Use the angle-sum identities

$$
\cos(\alpha+\beta)=\cos\alpha\cos\beta-\sin\alpha\sin\beta,
$$

$$
\sin(\alpha+\beta)=\sin\alpha\cos\beta+\cos\alpha\sin\beta.
$$

Therefore,

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos(\alpha+\beta) & -\sin(\alpha+\beta) \\
\sin(\alpha+\beta) & \cos(\alpha+\beta) \\
\end{pmatrix}
=R(\alpha+\beta).
$$

**Geometric explanation and check:** Rotating by $\beta$ and then by $\alpha$ about the same origin is equivalent to rotating once by their sum. For instance, two $90^\circ$ rotations produce $R(180^\circ)=-I$, consistent with the formula.
