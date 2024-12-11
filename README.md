# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

For two graphs to be isomorphic, there must be a bijection function between them. For example, consider two graphs G1 and G2 for a bijection function to exist between them we must be able to prove that there exists a one-to-one and onto function between the graphs. For a one to one function exist between the graphs we must be able to map every vertex in G1 to a unique vertex in G2. For a onto function to exist between the graphs we must be able to map every vertex of G1 to G2. This does not have to be done uniquely. Now let's say that G1 has n number of vertices and G2 has m number of vertices where n > m. Now if we map the vertices from G1 to G2 we will eventually run out of unique vertices in G2 that we can map to. Now if we consider where n < m and start mapping the vertices we will eventually run out of unique vertices in G1 that can be mapped to vertices in G2. This type of mapping is only able to pass the onto function and not the one-to-one function because we were not able to map all the vertices in G1 to a unique vertex in G2 and vice versa. Therefore the bijection function does not exist. By this, we can say that if two graphs do not have the same number of nodes then they cannot be isomorphic. They must have the same number of nodes in order to be isomorphic.

Reference:

I looked at my previous repository to see if I had anything different.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice
