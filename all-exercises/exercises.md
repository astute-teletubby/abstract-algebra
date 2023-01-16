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

