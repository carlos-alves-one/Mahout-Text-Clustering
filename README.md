# Mahout-Text-Clustering

## Overview
Mahout-Text-Clustering is a Python project designed to perform cluster analysis on textual data using Apache Mahout. This project implements various distance measures and evaluates the clustering solution using the K-Means algorithm.

## Project Structure
- `data/`: Contains the raw text data file `Sterne_Sentimental.txt`.
- `scripts/`: Contains Python scripts for data processing and clustering.
- `results/`: Stores the output and evaluation results of the clustering process.
- `README.md`: Overview and instructions for the project.

## Requirements
- Python 3.x
- Apache Mahout
- NumPy
- Matplotlib

## Steps for Cluster Analysis
1. **Data Preparation**: Convert raw text data into sequence files.
2. **Vector Representation**: Create sparse feature vectors for text data.
3. **Centroid Initialization**: Initialize approximate centroids for K-Means.
4. **Clustering**: Run the K-Means algorithm with different distance measures.
5. **Evaluation**: Evaluate the clustering solution and determine the optimal number of clusters.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/TextClusterPro.git
