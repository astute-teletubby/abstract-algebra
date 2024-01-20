Let $f_n$ be the $n$ th fibbonacci number, with $f_1 = 1$ and $f_2 = 1$ Prove $f_n < 2^n$ for $n \in \mathbb{N}$

**Base Cases**

Let $n = 1$. then

&emsp; $f_1 < 2^1$

&emsp; $1 < 2$

Let $n = 2$. then

&emsp; $f_2 < 2^2$

&emsp; $1 < 4$

Suppose $f_k < 2^k$ for $k \ge 2$. We have

&emsp; $f_{k+1} = f_k + f_{k-1}$

Using the inductive hypothesis

&emsp; $f_{k+1} < 2^k + 2^{k-1}$

&emsp; $f_{k+1} < 2^k + 2^k$

&emsp; $f_{k+1} < 2 \cdot 2^{k}$

&emsp; $f_{k+1} < 2^{k + 1}$

