# 🧪 Health Data Analysis Labs

This repository contains lab works focused on **clinical data analysis** using Python.  
The projects are based on real-world health datasets (COVID-19 and heart failure) and demonstrate the application of **exploratory analysis, clustering, PCA, and linear classification techniques**.  

All labs are implemented in **Jupyter Notebooks** with step-by-step analysis and visualizations.  

---

## Lab Work 1: Exploratory Data Analysis (COVID-19 Dataset)
Conducted exploratory data analysis on COVID-19 case statistics.  

- Data preprocessing and cleaning  
- Descriptive statistics and feature overview  
- Visualizations of correlations and distributions  

---

## Lab Work 2: Clustering (Heart Failure Dataset)
Applied clustering algorithms to group patients based on clinical records.  

- Standardization and scaling with `StandardScaler`  
- K-Means clustering (2 and 5 clusters)  
- Agglomerative hierarchical clustering (2 and 5 clusters)  
- Scatterplots visualizing clusters across different features  

---

## Lab Work 3: Principal Component Analysis (PCA) with Clustering
Dimensionality reduction and cluster analysis on the heart failure dataset.  

- PCA transformation (2 and 5 components)  
- Agglomerative clustering applied on PCA-transformed data  
- Evaluation with:  
  - **Silhouette Score**  
  - **Davies–Bouldin Index**  
- Comparison with clustering results from Lab 2  

---

## Lab Work 4: Linear Classifiers (Fisher’s Discriminant)
Implemented a linear classifier to separate patients into risk groups.  

- PCA for dimensionality reduction and visualization  
- Fisher’s Linear Discriminant analysis  
- Threshold calculation for classification  
- Visualization of decision boundary on patient data  

---

## ⚙️ Technologies Used
- **Python**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Machine Learning**: PCA, clustering, linear classifiers  
- **Jupyter Notebook**: reproducible workflows  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/2yazan/HealthDataAnalysis
   cd health-data-analysis-labs
