# Network Analysis of a BlueSky Account  

## Description  
This project involves analyzing a network from a specific BlueSky account to uncover insights about user interactions and the critical roles certain users play in the network. The analysis is performed using Gephi, a powerful network visualization and analysis tool, and adheres to the guidelines provided in the coursework.  

The primary goal is to understand the structure, dynamics, and important metrics of the network, such as centrality measures, clustering effects, and community structure, as well as to identify critical users and relationships within the network.  

---

## Files Included  
- **Analysis_Report.pdf**: A detailed report containing the analysis and results, including graphical representations, statistical summaries, and interpretations.  
- **Env_Net.gexf**: The Gephi project file containing the visualized network and all applied filters and rankings.  

---

## Analysis Overview  

### Methodology  
1. **Data Preparation**:  
   - Fetched and cleaned the data related to the BlueSky account network.  
   - Imported the data into Gephi for analysis and visualization.  

2. **Key Metrics and Properties**:  
   The analysis focused on the following aspects of the network:  
   - **Graphical Representation**: Visualized the network to explore its structure and relationships.  
   - **Basic Topological Properties**:  
     - Number of nodes and edges.  
     - Network diameter and average path length.  
   - **Component Analysis**:  
     - Number of connected components.  
     - Existence of a giant component and size distribution of components.  
   - **Degree Measures**:  
     - Maximum and average node degrees.  
     - Degree distribution.  
   - **Centrality Measures**:  
     - Degree centrality.  
     - Betweenness centrality.  
     - Closeness centrality.  
     - Eigenvector centrality.  
   - **Clustering Effects**:  
     - Average clustering coefficient.  
     - Number of triangles.  
     - Clustering coefficient distribution.  
     - Triadic closure phenomenon.  
   - **Bridges and Local Bridges**: Identification of critical edges that connect parts of the network.  
   - **Homophily and Gender Effects**: Explored patterns of connections based on gender and similarity.  
   - **Graph Density**: Density of connections in the network.  
   - **Community Structure**: Detected communities using modularity measures.  
   - **PageRank**: Calculated the influence of nodes in the network.  

---

## Tools and Libraries  
- **Gephi**: For network visualization and analysis.    

---

## Results  
The results of the analysis, along with graphical representations and detailed interpretations, can be found in the **Analysis_Report.pdf**. Key insights include:  
- Identification of users with high centrality measures (influential users).  
- Clustering effects and the presence of tightly connected communities.  
- Patterns of homophily and triadic closures within the network.  
- Community structures and their modularity scores.  

---

## Limitations  
- The analysis focuses on a single network and may not generalize to all BlueSky networks.  
