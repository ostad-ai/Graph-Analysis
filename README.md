# Graph-Analysis 
Programs related to the field of **Graph Analysis** are expessed here. More on Graph Analysis is at the following link:
https://www.pinterest.com/HamedShahHosseini/graph-analysis/
## History:
**Graph theory** is said to be originated by the work of **Leonard Euler** when dealing by the **Konigsberg bridges problem**. He abstracted the lands (four) by nodes and the bridges (seven) by edges. 
 - However, Islamic Scholars (9th–14th centuries) used tree diagrams for lineage and knowledge organization.

The **Konigsberg bridges problem** asks to start at any land areas of the city, walk over each of the seven bridges exactly once, and return to the starting point. Euler proved that there is no solution for this problem.  
## Topics:
1) **What is a graph?** A graph is a mathematical structure to represent *relationships* between *objects*. Objects are **nodes** (vertices), and relationships are **edges** (links). 
Here, we review the graph definition, and discuss **undirected** graphs versus **directed** graphs with examples in Python.
2) **Graph: Adjacency matrix** For a graph with *n* nodes, the **adjacency matrix** is of size *n*-by-*n*. For **simple graphs**, the entries of the adjacency matrix is composed of zeros and ones. For undirected graphs, this matrix is *symmetric*.
Here, we give the Python code for defining the adjacency matrix for different types of graphs.
3) **Graph: Node degree** The **degree** of a node in graph is a simple concept which is quite useful in analyzing and understanding the graph. The degree of a node is the number of edges connected to the node. The definition of node degree for directed graphs includes in-degrees and out-degrees. 
We have some interesting formulae regarding the node degrees. For example, the **degree sum formula** (handshaking lemma) states that the sum of degrees of nodes in a graph is twice the number of the edges of the graph. 
Here, we review the concept of degrees in graphs by examples in Python.
4) **Adjacency list:** The adjacency list is another way to represent graphs. It is a data structure holding a list of nodes of a graph such that each node in the list stores its neighbors. Adjacency lists are particularly efficient for **sparse graphs** such as social networks, web graphs, and biological networks.
Here, we implement a Python class for a graph which holds the adjacency list of the graph in a *defaultdict*. We build two graphs by our class and show their adjacency lists. As a bonus, a Python function has also been defined to convert our graph to that of *NetworkX*. 
5) **Walk, trail, path, cycle (circuit), and Eulerian trail/circuit:** The concepts that define the sequences of nodes and edges within a graph are reviewed here. The conditions for a graph to have an Eulerian trail or circuit (cycle) are also mentioned.
The **Python** code of this NoteBook contains a small **graph analyzer** implemented from scratch for walks, trails, paths, cycles, and Eulerian trail or circuit.
6) **Subgraph:** A **subgraph** is a graph formed from a subset of the nodes and edges of a larger graph. A subgraph preserves the connections from the original graph, but may contain fewer nodes and edges. 
Here, we review the concept of subgraph and some of its types. Also, we provide a *Python* function from scratch to check if a graph is a subgraph of another graph. We also use some functions available by *NetworkX* too, for subgraphs. 
7) **Clique:** A **clique** is subset of nodes in a graph, which for its every two distinct nodes, there is an edge in the graph. In other words, a clique forms a **complete** subgraph.
In this Notebook, we review and implement the **Bron-Kerbosch** algorithm from scratch to find all maximal cliques in a given undirected graph. Moreover, we use the function **find_cliques** in *NetworkX* to compare with our results.
8) **Trees:** A **tree** is an **undirected** graph which is **connected** and **acyclic**. Or you may say a tree is an undirected connected graph with n nodes which has n-1 edges. 
Here, we review trees in graph theory and express different kinds of them. Then, we bring some Python code to build trees and do some operations on them. As a bonus, we also create a simple decision tree for medical diagnosis.
9) **Depth-first search:** A **depth-first search** (**DFS**) is a search algorithm that is used to traverse graphs or trees. A DFS can be implemented in **recursive** way or **iterative** way. 
Here, we implement both the *recursive* and *iterative* versions, and test them by a given graph. We also implement a DFS that finds a path between two nodes, and extend it to find all paths between two nodes.