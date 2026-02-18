# Hierarchical Clustering (Agglomerative)

This project demonstrates Hierarchical Clustering using Python. It focuses on Agglomerative clustering, dendrogram visualization, and comparison of different linkage methods.

Hierarchical clustering is an unsupervised machine learning technique that builds a tree-like structure of clusters called a dendrogram.

Unlike K-Means, it does not require specifying the number of clusters initially.

---

## 🔍 What is Hierarchical Clustering?

Hierarchical clustering builds nested clusters either:

Agglomerative (Bottom-Up)
Each data point starts as its own cluster and clusters merge step by step.

Divisive (Top-Down)
All points start in one cluster and are split recursively.

This project mainly implements Agglomerative clustering.

---

## 📊 Dendrogram

A dendrogram is a tree diagram used to visualize hierarchical clustering.

It shows:

Distance between clusters
Order of merging
Optimal number of clusters

The vertical height represents the distance (similarity measure).

---

## 🧠 Linkage Methods Used

Single Linkage – Minimum distance between clusters
Complete Linkage – Maximum distance
Average Linkage – Mean distance
Ward Linkage – Minimizes variance within clusters

Ward generally gives better compact clusters.

---

## 🛠 Technologies Used

Python
NumPy
Matplotlib
SciPy
Scikit-learn

---

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/hierarchical-clustering-ml.git
cd hierarchical-clustering-ml
```

Install dependencies:

```bash
pip install -r requirements.txt
```
## 📈 Output

Dendrogram visualization
Cluster labels
Comparison of linkage methods

---

## 📌 Mathematical Insight

Distance between two clusters (Ward method):

Minimizes increase in total within-cluster variance.

Euclidean distance:

d(x, y) = √Σ(xi − yi)²

Hierarchical clustering repeatedly merges clusters based on minimum linkage distance.

---

## 🎯 Learning Outcome

Understand hierarchical clustering algorithm
Visualize cluster formation
Interpret dendrogram
Compare linkage techniques
Apply clustering on real-world datasets

