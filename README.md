# DSC_Assignment_IMS2400
DSC212 – Modularity on the Karate Club Graph
Recursive Spectral Modularity Partitioning

Objectives

Recursive Spectral Modularity Partitioning

Construct the modularity matrix for each community.

Use the leading eigenvector to split communities based on sign.

Apply the eigenvalue > 0 rule to determine if a split is meaningful.

Record every split and maintain the full partition history.

Community Visualization
For each iteration of the splitting process:

Visualize the network using a fixed spring layout.

Assign different colors to different communities.

Save each figure in the figures/ directory.

Node Metric Computation
After every iteration, compute:

Degree centrality

Betweenness centrality

Closeness centrality

Clustering coefficient
All computed metric values are stored and saved as CSV files inside the figures/ directory.

Metric Evolution Plots
For each metric, a plot is generated showing how the values evolve across splitting iterations for every node. These plots are saved in the figures/ directory.

Outputs Saved
The notebook saves:

Figures of all community partitions

Metric evolution plots

CSV files with metric histories

A JSON file containing the full partition and modularity history

Files Included

DSC212_Karate_Modularity.ipynb (main notebook)

figures/ (contains all plots, CSVs, and JSON output)

How to Run
Open the notebook and run all cells from top to bottom.
All required files will be generated automatically inside the figures/ folder.
