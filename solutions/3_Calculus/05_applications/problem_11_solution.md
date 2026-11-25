# Problem 11. Volume of a Solid of Revolution

## Question

The region under the graph

$$
y=\sqrt{x},\qquad x\in[0,4],
$$

is rotated about the $x$-axis.

1. Construct the integral describing the volume using the disk method.
2. Compute the volume.
3. Explain where the factor $\pi y^2$ in the integral comes from.

> **Why this problem:** it teaches how to construct an integral from the geometry of cross-sections instead of applying a volume formula without understanding its origin.

## Solution

Rotation about the $x$-axis creates circular disks perpendicular to that axis. Their radius at position $x$ is $\sqrt{x}$, so their cross-sectional area is $\pi y^2=\pi x$. A thin disk of thickness $dx$ contributes volume $\pi x\,dx$.

Using the disk method,

$$
V=\pi\int_0^4(\sqrt{x})^2\,dx
=\pi\int_0^4x\,dx
=\pi\left[\frac{x^2}{2}\right]_0^4=8\pi.
$$

The volume is $8\pi$ cubic units.

**Check:** The disk areas increase linearly from $0$ to $4\pi$. Their average is $2\pi$, and multiplying by the length $4$ gives $8\pi$.
