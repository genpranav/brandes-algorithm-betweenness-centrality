# Effecient Edge and Vertex Betweenness Centrality computational algorithms: Brandes

A graph is a mathematical structure that is used to represent interactions or connections among objects. Graphs can be used to mimic a wide range of real-world situations, such as interpersonal ties in a social network, node connections in a computer network, or the movement of items in a supply chain.

Graphs are defined by their vertices and edges. Assessing the significance of vertices and edges in a graph is highly insightful in a number of situations. One of the methods used to quantify this **importance of edges and vertices is Betweenness Centrality**. The main goal is to identify the number of times the Vertice/Edge is a part of the shortest paths present between Vertices present in the graph.

This is an example computation for a simple graph,

![BC example](./Images/BC%20example.jpg)

Obviously when scaling graphs to practical situations will lead to computational strain. 

The notion of this problem has been clearly established for quite some time and along with it come multiple possible approaches to computing it. **One of the more efficient algorithms that solve for Betweenness Centrality is the Brandes algorithm**.


## Documentation

The documentation of this project can be found [here](https://iq.opengenus.org/p/dc5de000-9cce-48b5-9805-0a81c2fdb56a/)

> The experiment to compute Betweenness Centrality for weighted graphs by extending it with the use of Dijkstra's algorithm only works for graphs with vertices/edges with unique shortest paths and does not generalize.

## References

- Ulrik Brandes, **"A Faster Algorithm for Betweenness Centrality"**, *Journal of Mathematical Sociology*, 25(2):163–177, 2001. [[PDF]](https://www.uni-konstanz.de/algo/publications/b-fabc-01.pdf) [[DOI]](https://doi.org/10.1080/0022250X.2001.9990249)
- Ulrik Brandes, **"On Variants of Shortest-Path Betweenness Centrality and their Generic Computation"**, *Social Networks*, 30(2):136–145, 2008. [[PDF]](https://www.uni-konstanz.de/algo/publications/b-vspbc-08.pdf) [[DOI]](https://doi.org/10.1016/j.socnet.2007.11.001)