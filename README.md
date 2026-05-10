# Graph-Based Insights for EV Charging Station Planning in Germany

This project analyzes a geographic proximity graph of German cities to support EV charging station planning.

The network contains 126 major German cities. Nodes represent cities, and edges connect cities that are less than 150 km apart.

The project explores:

- graph properties
- centrality analysis
- community detection
- network rewiring experiments
- EV infrastructure planning insights

---

## Project Structure

### `dataset_assembly.ipynb`
Data cleaning, preprocessing, graph construction, and geographic visualization.

### `ev_network_analysis.ipynb`
Main graph analysis, centrality analysis, rewiring experiments, and community detection.

---

## Data Sources

### German Cities Dataset

The city dataset was obtained from the SimpleMaps Germany Cities Database.

Source:  
https://simplemaps.com/data/de-cities

The dataset contains German cities with latitude, longitude, state, and population information.

License: MIT License

### Germany Administrative Boundaries

Germany’s federal state boundaries were obtained from GADM (Global Administrative Areas).

Source:  
https://gadm.org/download_country.html

The boundary data was used for geographic map visualization.

---

## Main Methods

### Graph Construction
- proximity-based graph generation
- weighted undirected graph modeling
- geodesic distance calculation

### Network Analysis
- degree centrality
- betweenness centrality
- closeness centrality
- eigenvector centrality

### Community Detection
- Louvain community detection
- Girvan–Newman community detection

### Network Robustness
- graph rewiring using double-edge swaps

---

## Main Findings

- Cities such as Kassel, Koblenz, and Hannover play important roles in network connectivity.
- Louvain clustering showed more stable and robust community structure under rewiring.
- The analysis highlights strategic cities for improving EV charging accessibility and long-distance connectivity in Germany.