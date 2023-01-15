# Chapter 1 - Preliminaries

6\. Prove $A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$

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
  
