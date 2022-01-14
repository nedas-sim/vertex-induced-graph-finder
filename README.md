# vertex-induced-graph-finder

Program takes 3 graphs:
G - main graph
G1, G2 - subgraphs

Program finds whether G1 and G2 are G's vertex induced graphs.

Graph is defined this way:

public int[] G2a = {1,1};
public int[] G2b = {2,3};

Meaning that the graph will have 3 vertices and two edges: 1-2 and 1-3.

Program visually shows the graphs:
In black - main graph
In red and green - two subgraphs if they are vertex induced
Blue - shared edges between both vertex induced subgraphs