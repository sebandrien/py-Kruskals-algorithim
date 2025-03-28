# Python Kruskal's Alogrithim

This Python class, Graph, implements Kruskal's algorithm to find the Minimum Spanning Tree (MST) of an undirected graph. It represents a graph as a collection of vertices and weighted edges. Each edge is defined by its two endpoints and weight, and is added using the add_edge method. 

The kruskal_mst function performs the MST calculation by sorting the edges by weight and using union-find operations to ensure no cycles are created. This efficient approach keeps track of the parent and rank of each node to optimize union operations. Upon execution, the code outputs the edges included in the MST and the total minimum cost. This implementation is helpful for understanding and solving network connectivity problems in weighted graphs.

Output:
```py
Edges in the constructed MST
2 -- 3 == 4
0 -- 3 == 5
0 -- 1 == 10
Minimum Spanning Tree 19
```
