## There are many different types of link-level features used in network analysis. Here are some common ones:
1. Weight or strength of a link
2. Distance between two nodes in the network
3. Common neighbors between two nodes
4. Local clustering coefficient of a link
5. Number of triangles a link participates in
6. Betweenness centrality of a link
7. Degree of the nodes that a link connects
8. Average path length of the nodes that a link connects
9. Edge diversity, which measures the diversity of the neighbors of the nodes connected by the link
10. Mutual information between the nodes connected by a link
11. PageRank of the nodes connected by a link

### Note that this is not an exhaustive list and different link-level features may be more appropriate for different types of networks or analysis tasks.

## Distance-based features
#### Distance-based features are a type of feature used in network analysis that capture the distance between nodes in a network. 
#### Distance-based features can be used to measure the similarity between nodes, the connectivity of a network, and the centrality of nodes in a network.

**Examples of distance-based features include:**
1. Shortest path length: The shortest distance between two nodes in a network.
2. Average path length: The average distance between all pairs of nodes in a network.
3. Eccentricity: The maximum distance between a node and all other nodes in the network.
4. Closeness centrality: The inverse of the sum of the shortest path lengths between a node and all other nodes in the network.
5. Betweenness centrality: The number of shortest paths that pass through a node.
6. Diameter: The maximum distance between any pair of nodes in the network.
7. Radius: The minimum eccentricity of any node in the network.
8. Central point dominance: The proportion of nodes that have a lower eccentricity than a given node.
Distance-based features can be useful in many network analysis tasks, such as identifying important nodes in a network, detecting communities, and measuring the robustness of a network to node or link failures.

## Local neighborhood overlap
* Local neighborhood overlap is a type of feature used in network analysis that captures the degree of overlap between the immediate neighbors of two nodes in a network.
* To calculate local neighborhood overlap, one first identifies the set of immediate neighbors of each node (i.e., the nodes that are directly connected to a given node). 
* The overlap between the local neighborhoods of two nodes is then calculated as the number of common neighbors between the two nodes divided by the total number of unique neighbors of the two nodes.
* Local neighborhood overlap can be used as a feature in tasks such as link prediction and community detection. 
* High overlap between the local neighborhoods of two nodes suggests that the two nodes are more likely to be connected, while low overlap suggests that the two nodes are less likely to be connected. 
* In community detection, nodes that have high overlap with each other are more likely to belong to the same community.
