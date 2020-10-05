
# Graphs

 - Nodes with an unlimited number of connections between them,
   It can also use already existing links to find relations between
   unlinked nodes.


## Graphs normally come in the types: Directed, Undirected, Weighted
 - Directed:
    - Has pointers that allow movement between the nodes, these pointers
      are unidirectional, and you must make a circuit to return to a 
      previous node. The order of movement is important. The is the possibity of
      adding a return pointer between nodes, having it be bidirectional.

 - Undirected:
    - The direction of flow doesn't really matter, going in circles is possible
       indefinitely.

 - Weighted:
    - The weight of the segments matter in terms of the distance to
      reach the objective / data / node.


## Graph Terminology
 - Vertex(vertices), a grouping or set ex. {A,B,C,D,E}
 - Edge Set, edges that connect ex. {(A,B), (A,C), (B,C), (C,D), (A,E)}

## Other Types of Graphs
 - Cyclic Graph: A directed graph which has a cycle in it.
    - There is the chance of an infinite loop being created.
 - Acyclic: A graph without a cycle in it.
    - It can never get back to itself on the same path.
 - Disconnected: Used to represent a dataset with a disconnected node
                 which had no edge connections.