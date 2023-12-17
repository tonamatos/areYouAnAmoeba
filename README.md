# Are you an Amoeba?

A simple amoeba detection tool. Works for local and global amoebas. For a more complete tool see Marcos Laffitte's repo at [2].

## Mathematical background

Let $G$ be a graph and $e$ an edge of $G$. We say $(e\to g)$ is a *feasible edge replacement* if $G-e+g$ is isomorphic to $G$. We say a graph is an *amoeba* is it can be transformed into any isomorphic copy of itself by means of a sequence of feasible edge replacements. For more details on amoebas and the difference between *local* and *global* amoebas, consult [1].

## Usage

The functions in the code take `networkX` graph objects as input. An example proving that the graph below is a *local amoeba* is provided in the code.

![My Image](amoeba.png)

## References

[1] <a href="https://www.combinatorics.org/ojs/index.php/eljc/article/download/v30i3p9/pdf/">Caro, Y., Hansberg, A., Montejano, A. (2023). *Graphs isomorphisms under edge-replacements and the family of amoebas*. **Electronic Journal of Combinatorics 30(3) P3.9**</a><br/>

[2] https://github.com/MarcosLaffitte/Amoebas
