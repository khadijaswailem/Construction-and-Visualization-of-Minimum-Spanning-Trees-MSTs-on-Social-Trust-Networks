# Minimum-Spanning-Trees-on-Social-Trust-Networks
## What are Social Trust Networks ?
Social Trust Networks are a type of graph that shows trust relationships between individuals or parties in a social platform. Each node represents a user, and each edge represents a trust relationship associated with trust score (weight).
Trust in online social networks is defined as the confidence users place in one another and the platform, influenced by the perceived reliability, integrity, and authenticity of the communities involved (Kridera & Kanavos, 2024)

## Algorithms used:
### 1. Kruskal's Algorithm
Kruskal's algorithm is a greedy algorithm that builds the MST by iteratively adding the cheapest edge that does not form a cycle.

### 2. Prim's Algorithm
Prim's algorithm is also a greedy algorithm that grows an MST from a starting vertex, iteratively adding the cheapest edge that connects a vertex in the growing MST to a vertex outside of it.

### 3. Borůvka's Algorithm
Borůvka's algorithm is less popular but it operates in "phases." In each phase, it finds the cheapest edge leaving each connected component and adds it to the MST, merging components.

### 4. Reverse-Delete Algorithm
It starts with all edges and iteratively removes the most expensive edge that does not disconnect the graph.

### 5. Karger's Algorithm (Interpreted for MST Visualization)
Karger's algorithm is for finding a minimum cut in a graph, not directly an MST. It uses a randomized contraction process to reduce the graph until only two vertices remain, and the edges between them form a cut.


## Real applications of the Social Trust Networks selected
### 1.Reputation Systems
•	Purpose: Computes scores to calculate a user's reputation.
In Bitcoin OTC dataset:
o	users rate each other, creating a wide reputation system which helps prevent fraud and increases safety in anonymous systems.
________________________________________
### 2.Expert Recommendation & Community Detection
•	Purpose: To pinpoint trust-worthy or influential participants of a community.
In Advogato dataset:
o	devlopers evaluate each other's skills which allows expert identification and trust-based groups to be formed more easily.
________________________________________
### 3.Trust-Based Link Prediction
•	Purpose: Predict future connections based on trust paths.
Epinions dataset:
o	For increasing user engagement and suggesting new connections as well as potential friends, tutors, or partners.
________________________________________
### 4. Education & Language Learning Platforms
•	Purpose: Enable peer assessment and trusted learning partners.
LiveMocha dataset:
o	users who teach each other mainly relies on trust ratings to choose whom to learn from or choose for help.
________________________________________
### 5. Research in Human Trust Evolvement
•	Purpose: Analyze how trust evolves in social systems and how communities start or breakdown.
Bitcoin Alpha:
o	Trust decay, forgiveness, and interchange can be modeled using timestamped interactions as seen in Bitcoin Alpha and Bitcoin OTC.



