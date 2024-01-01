# Data-Mining-Comparative-Study
This repository explores the performance of different data mining algorithms applied to the same dataset.

### Goal:

- Analyze the effectiveness of various algorithms for data mining tasks.
- Compare and contrast the results obtained from different approaches.
- Gain insights into the strengths and weaknesses of each algorithm.

### Dataset:

[[Adult](https://archive.ics.uci.edu/dataset/2/adult)]

### Algorithms:

- **k-means clustering**

  The k-means algorithm is a popular method for partitioning a dataset into clusters. It aims to group similar data points together based on their feature similarity. The algorithm iteratively assigns data points to clusters and updates the cluster centers until convergence.

- **k-modes clustering**

  The k-modes algorithm is an extension of k-means specifically designed for categorical data. Unlike k-means, which uses the Euclidean distance, k-modes uses a dissimilarity measure tailored for categorical variables, making it suitable for datasets with mixed data types.

- **k-prototype clustering**

  The k-prototype algorithm combines k-means and k-modes to handle datasets with both numerical and categorical features. It aims to find clusters by minimizing the sum of squared distances for numerical variables and using a dissimilarity measure for categorical variables.

### Evaluation Metrics:

- **Silhouette Score**

  The Silhouette Score is a metric that quantifies how well-separated clusters are. It measures the cohesion within clusters and separation between clusters, providing a value between -1 and 1. A higher Silhouette Score indicates better-defined clusters.


### Repository Structure:

- `data`: Folder containing the dataset used in the study.
- `code`: File containing code implementations for each algorithm.
- `Report`: File containing overall reports of the implementations.
- `readme.md`: This file.

### Requirements:

- Python 3.11.1
- NumPy
- Pandas

### Instructions:

1. Clone the repository.
2. Install the required libraries.
3. Run the scripts in the `code` folder for each algorithm.
4. Analyze the results and generate reports in the `reports` folder.
5. Compare and contrast the results across different algorithms.


### Authors:

1. Mirza Abbas Uddin - mirzaabbasuddin2@gmail.com
2. Sanjana Hossain Sonali - sanjana.hossain62@gmail.com

### Contact:

For any questions or feedback, please contact the author(s) listed above.
