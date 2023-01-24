Let $f: A \rightarrow B$ and $g: B \rightarrow C$ be invertible mappings; that is, mappings such that $f^{-1}$ and $g^{-1}$ exist. Show that $(g \circ f)^{-1} = f^{-1} \circ g^{-1}$.

*Proof*

Let $a \in A$. It follows that

&emsp; $f(a) = b$, where $b \in B$

&emsp; $g(b) = c$, where $c \in C$

Now since $f$ and $g$ are invertible, it follows from the definition of an inverse that

&emsp; $f^{-1}(b)=a$

&emsp; $g^{-1}(c)=b$

Combining the above expressions we find that

&emsp; ($g \circ f) (a) = g(f(a)) = g(b) = c$

And using the definition of an inverse

&emsp; $(g \circ f)^{-1} \circ (g \circ f)(a)=(g \circ f)(c)=a$

All that remains is to show that applying $(g \circ f)^{-1}$ to $c$ has the same effect as applying $(f^{-1} \circ g^{-1})$ to $c$.

&emsp; $(f^{-1} \circ g^{-1})(c) = f^{-1} (g^{-1}(c)) = f^{-1}(b) = a$

Therefore 

&emsp; $(g \circ f)^{-1} = f^{-1} \circ g^{-1}$