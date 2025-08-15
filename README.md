# k-means-clustering
K-Means clustering with Elbow Method, PCA visualization, and Silhouette analysis.
# K-Means Clustering — Step-by-Step (Mini Guide)

This repository contains implementation of **K-Means Clustering**

## 📋 Steps
1. **Load and visualize dataset** (optional PCA for 2D view)  
2. **Fit K-Means** and assign cluster labels  
3. **Use the Elbow Method** to find optimal number of clusters  
4. **Visualize clusters** with color-coding  
5. **Evaluate clustering** using Silhouette Score  

---

## 🚀 Features
- Works with **your dataset** (CSV path configurable)
- **PCA visualization** for 2D plotting
- **Elbow Method** & **Silhouette Score** for finding the best `k`
- Inline plots for Google Colab
- Handles both all-numeric and manually-selected features

---

## 📂 Dataset
You can use any dataset with numeric features.  
Example: `Mall_Customers.csv` with features:
- `Annual Income (k$)`
- `Spending Score (1-100)`


## 📊 Output Files / Visuals
The notebook will produce:
- PCA scatter plot (before clustering)
- Clustered PCA plot (initial k)
- Elbow plot (Inertia vs k)
- Silhouette Score vs k plot
- Final cluster visualization (best k)
- Silhouette diagram (best k)
