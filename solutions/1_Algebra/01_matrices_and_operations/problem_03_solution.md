# Exercise 3. When Can Matrices Be Multiplied?

Given $A:2\times3$, $B:3\times4$, $C:4\times2$, and $D:2\times2$.

The rule is $(m\times n)(p\times q)$ is defined **if and only if** $n=p$, and the result then has size $m\times q$.

| Product | Inner dimensions | Defined? | Result size / reason |
|---|---|---|---|
| $AB$ | $3=3$ | Yes | $2\times4$ |
| $BA$ | $4\ne2$ | No | Incompatible inner dimensions |
| $BC$ | $4=4$ | Yes | $3\times2$ |
| $CB$ | $2\ne3$ | No | Incompatible inner dimensions |
| $AC$ | $3\ne4$ | No | Incompatible inner dimensions |
| $CA$ | $2=2$ | Yes | $4\times3$ |
| $AD$ | $3\ne2$ | No | Incompatible inner dimensions |
| $DA$ | $2=2$ | Yes | $2\times3$ |

**Check:** For example, $AB$ has the dimension chain $(2\times\mathbf3)(\mathbf3\times4)$; each resulting entry is a dot product of two vectors of length $3$. For $BA$, the corresponding vectors would have lengths $4$ and $2$, so a dot product is not defined.
