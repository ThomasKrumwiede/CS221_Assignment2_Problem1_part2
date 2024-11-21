(b)	Modify function readGraph() to read from a file a modified representation of the adjacency lists that after each adjacent vertex number contain the cost of visiting this vertex from the vertex for which this is the adjacency list. The cost will be a number of type double. For example, am input file may contain:
5
0 2 1.5 4 2.5 -999
1 3 0.5 -999
2 3 0.9 4 0.8 -999
3 -999
4 2 0.8 3 2.2 4 0.2  -999

In this example, the vertices adjacent from vertex 0 are 2 and 4, the cost of visiting vertex 2 from vertex 0 is 1.5, the cost of visiting vertex 4 from vertex 0 is 2.5, and no other vertices can be visited from  vertex 0. 

For parts c) and d) consider only connected graphs.
(c)	Override all traversal functions, in addition to printing the visited vertices,  to return the total cost of a traversal.

(d)	Modify all traversal functions to select from the available non-visited adjacent vertices to visit first the vertex with the smallest cost of the edge to it.  
