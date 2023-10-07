# ASP for Planning 

Wrote an ASP program to solve the following (toy) planning problem. This problem is about finding a way to deliver some packages from warehouses to specified delivery locations, using several (electric) trucks.

The problem works in time steps. At each time step, each truck can perform exactly one action—move to an adjacent node, wait, (un)load a package, and so on (more details below). The problem operates on a map that consists of a graph with nodes and edges. All nodes and edges are single capacity, meaning that only a single truck can be on a node or travel on an edge at each time step. The task is to find a plan (a sequence of actions, one per truck per time step) after which the goal state is achieved: all packages are delivered, the trucks are empty (i.e., without packages) and are located on a charging spot.
