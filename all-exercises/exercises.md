# Chapter 1 - Preliminaries

**6\.** Prove $A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$

*Proof*

Let $x \in A \cup (B \cap C)$. Then either $x \in A$ or $x \in B \cap C$

Suppose $x \in A$. If an element exists in $A$ it also exists in any union containing $A$. Thus,
$x \in A \cup B$ and $x \in A \cup C$

Now suppose $x \in B \cap C$. If an element exists in $B \cap C$ it also exists in any union containing $B$ or $C$. Thus, $x \in A \cup B$ and $x \in A \cup C$.

In both instances, we can use the definition of an intersection to conclude that $x \in (A \cup B) \cap (A \cup C)$. Therefore $A \cup (B \cap C) \subset (A \cup B) \cap (A \cup C)$.

Conversely, suppose that $x \in (A \cup B) \cap (A \cup C)$. Since $x$ is in both unions, $x$ must be in $A$ or $x$ must be in both $B$ and $C$. In other words 

&emsp; $x \in A$ or $x \in B \cap C$

&emsp; $x \in A \cup (B \cap C)$
  
Therefore, $(A \cup B) \cap (A \cup C) \subset A \cup (B \cap C)$.

Hence, $(A \cup B) \cap (A \cup C) = A \cup (B \cap C)$.

&nbsp;

&nbsp;

&nbsp;


**22(a)\.** Let $f : A \rightarrow B$ and $g : B \rightarrow C$. If $f$ and $g$ are both one-to-one functions, show that $g \circ f$ is one-to-one

*Proof*

Let $f : A \rightarrow B$, f is one-to-one
&nbsp;

and $g : B \rightarrow C$, g is one to one

Suppose we have to elements $a_1, a_2 \in A$ and that $(g \circ f)(a_1) = (g \circ f)(a_2)$. We have

&emsp; $g(f(a_1)) = g(f(a_2))$

&emsp; $f(a_1) = f(a_2)$

&emsp; $a_1 = a_2$

Hence, $(g \circ f)(a_1) = (g \circ f)(a_2)$ implies $a_1 = a_2$ and $g \circ f$ is one-to-one


&nbsp;

&nbsp;

&nbsp;


**29\.** **Projective Real Line.** Define a relation on $\mathbb{R}^2 \ \smallsetminus \ \{(0,\ 0)\}$ by letting $(x_1,\ y_1) \sim (x_2,\ y_2)$ if there exists a nonzero real number $\lambda$ such that $(x_1,\ y_1)=(\lambda \ x_2,\ \lambda \  y_2)$. Prove that $\sim$ defines an equivalence relation on $\mathbb{R}^2 \ \smallsetminus \ \{(0,\ 0)\}$. What are the coresponding equivalence classes? This equivalence relation defines the projective line, denoted by $\mathbb{P}(\mathbb{R})$, which is very important in geometry.

*Proof*

**Reflexivity**

Let $(x,y) \in \mathbb{R}^2 \ \smallsetminus \ \{(0,0)\}$. We have $(x,y) \sim (x,y)$ when $\lambda = 1$ 

**Symmetry** 

Let $(x_1,\ y_1), \ (x_2,\ y_2) \in \mathbb{R}^2 \ \smallsetminus \ \{(0,\ 0)\}$ where 

&emsp; $(x_1,\ y_1)=(\lambda \ x_2,\ \lambda \ y_2) \rightarrow (x_1,\ y_1) \sim (x_2,\ y_2)$

Since every nonzero real number $\lambda$ has a real reciprocal $1/ \lambda$, we have,

&emsp; $(x_2,\ y_2) = (\frac{1}{\lambda} \ x_1, \frac{1}{\lambda} \ y_1) \rightarrow (x_2,\ y_2) \sim (x_1,\ y_1)$



**Transitivity**

Let $ (x_1,\ y_1), \ (x_2,\ y_2), \ (x_3,\ y_3) \in \mathbb{R}^2 \ \smallsetminus \ \{(0,\ 0)\}$ where

&emsp; $(x_1,\ y_1)=(\theta \ x_2,\theta \ y_2) \rightarrow (x_1,\  y_1) \sim (x_2,\ y_2)$

&emsp; $(x_2,\ y_2)=(\phi \ x_3,\ \phi \ y_3) \rightarrow (x_2,\  y_2) \sim (x_3,\ y_3)$

For some nonzero $\theta, \phi \in \mathbb{R}$

Since the product of two real numbers is also real, we have

&emsp; $(x_1,\ y_1)=(\theta \ \phi \ x_3,\ \theta \ \phi \ y_3) \rightarrow (x_1, \ y_1) \sim (x_3, \ y_3)$