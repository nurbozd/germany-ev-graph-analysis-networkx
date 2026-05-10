# Graph-Based Insights for EV Charging Station Planning in Germany

This project analyzes a geographic proximity graph of German cities to support EV charging station planning.

The network contains 126 major German cities.  
Nodes represent cities, and edges connect cities that are less than 150 km apart.

The project explores:

- Graph properties
- Centrality analysis
- Community detection
- Network rewiring experiments
- EV infrastructure planning insights

## Project Structure

- `dataset_assembly.ipynb`  
  Data cleaning, preprocessing, graph construction, and geographic visualization.

- `ev_network_analysis.ipynb`  
  Main graph analysis, centrality analysis, rewiring experiments, and community detection.

## Data Sources

- SimpleMaps Germany Cities Dataset
- GADM Administrative Boundaries

## Main Methods

- Degree, betweenness, closeness, and eigenvector centrality
- Louvain community detection
- Girvan–Newman community detection
- Graph rewiring using double-edge swaps

## Main Findings

- Cities such as Kassel, Koblenz, and Hannover play important roles in network connectivity.
- Louvain clustering showed more stable and robust community structure under rewiring.
- The analysis highlights strategic cities for improving EV charging accessibility and long-distance connectivity in Germany.