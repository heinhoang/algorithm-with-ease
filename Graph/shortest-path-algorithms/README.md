### The shortest path problem
Finding a path between 2 vertices in a graph such that the total sum of the edges weights is minimum.
![The shortest path problem](./imgs/shortest-path-problem.svg =480x)
**How to find path from node 0 to node z with minimum cost?**

**Note**
This problem could be solved easily using (BFS) if all edge weights were (1), but here weights can take any value. Three different algorithms are discussed below depending on the use-case.