K-Means Clustering from Scratch

This repository contains an implementation and exploration of the K-Means clustering algorithm using Python. The project demonstrates how K-Means works, how clusters are formed, and how the algorithm converges over iterations.

📌 Project Overview

K-Means is an unsupervised machine learning algorithm used to group data points into K distinct clusters based on similarity.
In this project, we:

Implement K-Means step by step

Visualize cluster assignments

Analyze convergence behavior

Experiment with different values of K

All work is contained in an interactive Jupyter Notebook for clarity and learning purposes.

📂 Repository Structure
.
├── kmeans.ipynb        # Main notebook containing the implementation
├── README.md           # Project documentation

🧠 Algorithm Explanation

The K-Means algorithm follows these steps:

Choose the number of clusters (K)

Initialize cluster centroids

Assign each data point to the nearest centroid

Update centroids based on cluster means

Repeat steps 3–4 until convergence

🛠️ Technologies Used

Python 3

Jupyter Notebook

NumPy

Matplotlib (for visualization)

(Optional) Pandas

▶️ How to Run

Clone the repository:

git clone https://github.com/your-username/kmeans-clustering.git


Navigate to the project directory:

cd kmeans-clustering


Open the notebook:

jupyter notebook kmeans.ipynb

📊 Results & Visualizations

The notebook includes visualizations showing:

Initial centroid placement

Cluster updates over iterations

Final clustering results

These visuals help build intuition about how K-Means works internally.

🚀 Future Improvements

Add Elbow Method for optimal K selection

Compare with sklearn’s KMeans

Support higher-dimensional datasets

Add animation for centroid movement
