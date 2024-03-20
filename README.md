[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM7QGF1q)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Proof: Suppose $G_1$ consists of the vertices A, B, and C, and $G_2$
consists of the vertices 1, 2, and 3, where A shares an edge with B
and 1 shares an edge with 2. So, $G_1$ and $G_2$ are not completely
connected graphs as there is not a path from A to C and 1 to 3.
Now, suppose there is a function that maps the vertices of $G_1$ 
onto $G_2$ such that f(A) = 1, f(B) = 2, and f(C) = 3. The mapping of
$G_1$ to $G_2$ shows the bijection function required to show that
$G_1$ is isomorphic to $G_2$ as the vertices of $G_1$ can be renamed
to the vertices of $G_2$ and maintain the corresponding edges in both
graphs. Therefore, as shown above, two graphs do not have to be completely
connected to be isomorphic.

Sources: The Introduction to Algorithms textbook, page 1166.
