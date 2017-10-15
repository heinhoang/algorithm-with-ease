## Idea To Solve The Problem:
![The shortest path problem](./imgs/shortest-path-problem.svg =480)
**How to find path from node 0 to node z with minimum cost?**
First, we go throgh the path a: 0 -> 1 -> ... -> n -> z with total cost: 4 + 120 + 12 = 136
Then, we go throgh the path b: 0 -> 2 -> ... -> m -> z with total cost: 5 + 126 - 8 = 123
123 < 136 so the path b is our answer.

## Bellman Ford's Algorithm:
--------
At the initial stage, set the distance to zero for the source node and to infinity for all other nodes.
Then at each node, select an adjacent node so that the summation of the distance of the adjacent node and the cost of the link from the adjacent node to its own node is minimized.
Set the selected adjacent node to be the previous hop node.
The shortest path can be found after repeating the process for N-1 times (N is the number of nodes in the network) .
--------
**Demo**
[bellman demo](./imgs/bellman.jpg)
