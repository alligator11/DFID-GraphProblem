# DFID
The algorithm Depth First Iterative Deepening (DFID) combines the best features of all the state space search algorithms. It does a series of depth first searches with increasing depth bounds. Since in every cycle it does a DFS with bound incremented by one, whenever it finds a solution it would have found the shortest solution. In this respect, it is like BFS. New nodes are explored one level at a time. On the other hand, within each cycle it does a DBDFS. Therefore, its memory requirements are those of DFS, that is, memory requirements grow linearly with depth.

## Graph problem
Here, the problem which is solved using DFID is given any 2 nodes - start and end node, finding a path between them in the graph.
