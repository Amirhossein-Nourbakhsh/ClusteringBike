# Quantum Clustering for Bike Sharing Stations

This repository contains code and results for clustering bike-sharing stations using both classical and quantum computing techniques. The primary goal is to optimize the management and placement of bike-sharing stations by identifying meaningful clusters.

## Notebooks

### 1. Clustring_QC.ipynb

This notebook demonstrates the implementation of clustering algorithms using quantum computing techniques. The key sections are:

- **Introduction to Quantum Clustering**: Overview of the quantum clustering approach.
- **Data Preparation**: Preprocessing steps for bike-sharing station data.
- **Classical Clustering**: Implementation of K-means clustering as a baseline.
- **Quantum Clustering**: Utilization of D-Wave's quantum annealing hardware for clustering.
- **Results Visualization**: Comparison of classical and quantum clustering results.
- **Performance Evaluation**: Analysis of runtime and performance for both methods.

### 2. QC_Clustering_Results.ipynb

This notebook focuses on presenting and analyzing the results of the clustering experiments. The key sections are:

- **Data Retrieval and Preparation**: Fetching and cleaning bike-sharing station data.
- **Classical Clustering Analysis**: Applying K-means clustering and evaluating performance.
- **Visualization of Clustering Results**: Scatter plots and silhouette plots of the clusters.
- **Silhouette Analysis**: Detailed analysis of cluster cohesion and separation.
- **Conclusion and Insights**: Observations on the clustering effectiveness.

## Setup and Requirements

To run the notebooks, you need to install the required packages. You can install them using:

```bash
pip install -r requirements.txt
```

## Usage

1. **Clustring_QC.ipynb**: Run this notebook to see the implementation of quantum clustering and compare it with classical methods.
2. **QC_Clustering_Results.ipynb**: Run this notebook to view the results and detailed analysis of the clustering experiments.

## Results

The results indicate that quantum clustering, although computationally intensive, can provide meaningful insights into the structure of bike-sharing stations. Classical methods like K-means serve as a good baseline for comparison.

## Conclusion

This project demonstrates the potential of quantum computing in solving complex clustering problems. Further improvements and optimizations can be explored to enhance the performance and scalability of quantum clustering algorithms.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
