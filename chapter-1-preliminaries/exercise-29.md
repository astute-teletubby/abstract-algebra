**Projective Real Line.** Define a relation on $\mathbb{R}^2 \ \smallsetminus \ \{(0,\ 0)\}$ by letting $(x_1,\ y_1) \sim (x_2,\ y_2)$ if there exists a nonzero real number $\lambda$ such that $(x_1,\ y_1)=(\lambda \ x_2,\ \lambda \  y_2)$. Prove that $\sim$ defines an equivalence relation on $\mathbb{R}^2 \ \smallsetminus \ \{(0,\ 0)\}$. What are the coresponding equivalence classes? This equivalence relation defines the projective line, denoted by $\mathbb{P}(\mathbb{R})$.

*Proof*

**Reflexivity**

Let $(x,y) \in \mathbb{R}^2 \ \smallsetminus \ \{(0,0)\}$. We have $(x,y) \sim (x,y)$ when $\lambda = 1$ 

**Symmetry** 

Let $(x_1,\ y_1), \ (x_2,\ y_2) \in \mathbb{R}^2 \ \smallsetminus \ \{(0,\ 0)\}$ where 

&emsp; $(x_1,\ y_1)=(\lambda \ x_2,\ \lambda \ y_2) \rightarrow (x_1,\ y_1) \sim (x_2,\ y_2)$

Since every nonzero real number $\lambda$ has a real reciprocal $1/ \lambda$, we have,

&emsp; $(x_2,\ y_2) = (\frac{1}{\lambda} \ x_1, \frac{1}{\lambda} \ y_1) \rightarrow (x_2,\ y_2) \sim (x_1,\ y_1)$

**Transitivity**

Let $(x_1,\ y_1), \ (x_2,\ y_2), \ (x_3,\ y_3) \in \mathbb{R}^2 \ \smallsetminus \ \{(0,\ 0)\}$ where

&emsp; $(x_1,\ y_1)=(\theta \ x_2,\theta \ y_2) \rightarrow (x_1,\  y_1) \sim (x_2,\ y_2)$

&emsp; $(x_2,\ y_2)=(\phi \ x_3,\ \phi \ y_3) \rightarrow (x_2,\  y_2) \sim (x_3,\ y_3)$

For some nonzero $\theta, \phi \in \mathbb{R}$

Since the product of two real numbers is also real, we have

&emsp; $(x_1,\ y_1)=(\theta \ \phi \ x_3,\ \theta \ \phi \ y_3) \rightarrow (x_1, \ y_1) \sim (x_3, \ y_3)$