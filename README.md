# Trade&Ahead: Stock Clustering Analysis

## Business Overview
Trade&Ahead is a financial consultancy firm that wants to conduct a cluster analysis on their stock data as it can help identify stocks that exhibit similar characteristics and ones that exhibit minimum correlation, and consequently, maximize earnings under any market condition. 

## Objective
The task at hand is to analyze the data, group the stocks based on the attributes provided, and share insights about the characteristics of each group. 

## Key Skills
Unsupervised, K-means Clustering, Hierarchical Clustering and PCA

## Python Libraries
- **Pandas** (`import pandas as pd`)
- **NumPy** (`import numpy as np`)
- **Matplotlib** (`import matplotlib.pyplot as plt`)
- **Seaborn** (`import seaborn as sns`)
- **Pandas Configuration**:
  - Display all columns (`pd.set_option("display.max_columns", None)`)
  - Display up to 200 rows (`pd.set_option("display.max_rows", 200)`)
- **Scikit-learn (sklearn)**
  - Data scaling: `StandardScaler` (`from sklearn.preprocessing import StandardScaler`)
  - Clustering:
    - K-Means: `KMeans` (`from sklearn.cluster import KMeans`)
    - Hierarchical clustering: `AgglomerativeClustering` (`from sklearn.cluster import AgglomerativeClustering`)
  - Model evaluation:
    - Silhouette score: `silhouette_score` (`from sklearn.metrics import silhouette_score`)
  - Principal Component Analysis (PCA): `PCA` (`from sklearn.decomposition import PCA`)
- **Scipy**
  - Distance computation: `pdist`, `cdist` (`from scipy.spatial.distance import pdist, cdist`)
  - Hierarchical clustering:
    - Dendrogram and linkage: `dendrogram`, `linkage` (`from scipy.cluster.hierarchy import dendrogram, linkage`)
    - Cophenetic correlation: `cophenet` (`from scipy.cluster.hierarchy import cophenet`)
- **Yellowbrick** (`from yellowbrick.cluster import KElbowVisualizer, SilhouetteVisualizer`)
  - Visualizing clustering metrics like elbow curves and silhouette scores

## Project Flowchart

<img width="1456" alt="image" src="https://github.com/user-attachments/assets/d1698d67-98e1-4e20-8077-18a75f8b1809">

## Charts

![image](https://github.com/user-attachments/assets/09f6e729-af82-4be6-a4ec-a50951eeee1d)

![image](https://github.com/user-attachments/assets/74e8f04d-742f-4dd3-879d-e7bbeaccd41e)

![image](https://github.com/user-attachments/assets/1e89b142-6399-4823-b5da-1033897c8151)

![image](https://github.com/user-attachments/assets/cd8c6f2b-8fe6-43a1-8d95-2c9afd532023)

![image](https://github.com/user-attachments/assets/40e8a7ed-65db-419e-a357-d0265563ebbd)

![image](https://github.com/user-attachments/assets/59d04af2-3e9a-4adb-a291-440299e48efe)

![image](https://github.com/user-attachments/assets/47b5a437-1cd5-4fa9-971e-cddf9b4d9793)

![image](https://github.com/user-attachments/assets/848df9b3-605f-41fc-a60d-f8c94adbd8aa)

![image](https://github.com/user-attachments/assets/94dc9172-74b5-45f2-ac1d-efa4623f361d)



