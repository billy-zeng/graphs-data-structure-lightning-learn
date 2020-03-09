# Graphs  

### What is a graph?  
A graph is a powerful data structure composed of nodes and edges. Nodes store data (e.g., locations on a map) and edges represent relationships between the nodes (e.g., the distance/routes from location to another). Graphs differ from trees in that trees represent data that is heirarchal in nature with parent/children relationships, while graphs represent relationships more generally; a node can have many edges to other nodes and there is no parent/child relationship. Graphs may be undirected or directed. Undirected graphs represent relationships that are always reciprocal; the edges do not point from one node to another. Directed graphs represent relationships that do not have to be reciprocal; the edges do point from one node to another. 

### Implementation
There are two ways to implement graphs in code that differ in Big-O efficiency: an adjacency list and an adjacency matrix. An adjacency list uses a collection of arrays and is the more commonly used graph representation. Each node has its own array, which lists all other nodes it is connected to. An adjacency matrix is represented by a two-dimensional array; each subarray is a node and the values in the subarrays represent edges to other nodes. 
