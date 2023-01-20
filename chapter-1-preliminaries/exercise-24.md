Let $f: X \rightarrow Y$ be a map and let

&emsp; $A_1, \ A_2 \subset X$

&emsp; $B_1, \ B_2 \subset Y$

Prove $f(A_1 \cup A_2) = f(A_1) \cup f(A_2)$

*Proof*

Recall that $f(A) = \{\ f(a) : a \in A \ \} \subset Y$

Let $y \in f(A_1 \cup A_2)$

Then there exists some $x \in A_1 \cup A_2$ such that $y=f(x)$

So by the definition of a union, either $x \in A_1$ or $x \in A_2$

Suppose $x \in A_1$

Then $y \in f(A_1) \rightarrow y \in f(A_1) \cup f(A_2)$

Similarly if $y \in A_2$

Then $y \in f(A_2) \rightarrow y \in f(A_1) \cup f(A_2)$

Therefore $f(A_1 \cup A_2) \subset f(A_1) \cup f(A_2)$

Conversely, suppose that $y \in f(A_1) \cup f(A_2)$

Then there exists either $x \in A_1$ or $x \in A_2$ such that $f(x) = y$

Suppose that $x \in A_1$

Then $y \in f(A_1) \rightarrow y \in f(A_1 \cup A_2)$

Similarly if $x \in A_2$

Then $y \in f(A_1) \rightarrow y \in f(A_1 \cup A_2)$

Therefore $f(A_1) \cup f(A_2) \subset f(A_1 \cup A_2)$

and $f(A_1 \cup A_2) = f(A_1) \cup f(A_2)$