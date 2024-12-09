# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Answer: 

If two graphs A and B have the same number of vertices and are complete then they must be isomorphic. Since both graphs have the same number of vertices and edges then we can define a bijection between their vertex sets. This bijection will map each vertex in A to a vertex in B and because both graphs are complete every pair of adjacent vertices in A will be mapped to adjacent vertices in B. Since the adjacency relationship is preserved under this mapping the graphs are isomorphic.
