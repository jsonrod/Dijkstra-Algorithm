# Dijkstra's Algorithm
README FILE

AUTHORS
=======
Jason Rodriguez,
Yaniel Gonzalez Velez,
Carlos Caraballo

DESCRIPTION
===========
This project consists of files that constructs a Graph data structure using an adjacency list implementation from C++ libraries to integrate Dijkstra's Algorithm that computes the shortest path between two points. 
The program consists of a Vertex class, Edge class, and Graph class. Dijkstra's Algorithm, with the assistance of a priority queue and map, enables efficient traversal of the graph to determine the shortest path.

FEATURES
========
- Dijkstra's Algorithm: Implements Dijkstra's algorithm to find the shortest path in a weighted undirected graph.
- Adjacency List: Utilizes an adjacency list representation for efficient graph storage.
- Graph Operations: Provides methods for adding and removing vertices, adding and removing edges, finding the shortest path between two vertices, and printing the existing vertices and edges as an adjacency list order.

DEPENDENCIES
============
This project relies on a C++ compiler that supports the C++11 standard or later.

COMPILATION
===========
To compile the program, use the following command: ```g++ -Wall -std=c++17 main.cpp Graph.cpp```

INPUT
=====
The program includes a simple user interface to execute the following functions:
- Enter 'h' to read the list of commands to that the program includes
- Enter 'v' for adding a vertex
- Enter 'e' for adding an edge
- Enter 'd' for removing a vertex
- Enter 'r' for removing an edge
- Enter 's' for finding the shortest path between two vertices
- Enter 'l' for listing the current graph
- Enter 'q' to quit

CODE STRUCTURE
==============
- 'main.cpp': Contains the user interface for interacting with the program.
- 'Graph.hpp' and 'Graph.cpp': Implement the graph class, which includes methods for graph operations and Dijkstra's algorithm.
- 'GraphBase.hpp': Contains the abstract base class prototypes with pure virtual functions for the graph, to be inherited the defined Graph class in 'Graph.hpp'.

ACKNOLEDGEMENTS
===============
The project was inspired by Dijkstra's algorithm, a key algorithm in graph theory for finding the shortest paths between nodes.
