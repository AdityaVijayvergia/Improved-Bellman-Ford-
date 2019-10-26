# Improved-Bellman-Ford-
Bellman does extra computations by checking for change in weight for nodes that-
1. Are still to be reached from source
2. Did not change weight in last cycle.

These computations are removed in this implementation by using a queue to keeps track of only those nodes that can change the shortest path length.
