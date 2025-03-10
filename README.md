# 📌 Clustering Project

## 📖 Overview
This project focuses on applying **clustering algorithms** to group similar data points based on their characteristics. The goal is to uncover hidden patterns and meaningful insights from the dataset using unsupervised learning techniques.

## 📂 Dataset Information
The dataset consists of **1,500** records with the following features:
- **name**: Title of the game
- **releaseDate**: Date when the game was released
- **copiesSold**: Number of copies sold
- **price**: Game price in USD
- **revenue**: Total revenue generated
- **avgPlaytime**: Average playtime per user
- **reviewScore**: Game review score
- **publisherClass**: Type of publisher
- **publishers**: Publisher names
- **developers**: Developer names
- **steamId**: Unique game identifier

## 🏗️ Project Workflow
The project follows these key steps:
1. **Data Preprocessing:**
   - Handling missing values (publishers, developers)
   - Converting categorical variables into numerical form
   - Standardizing numerical features for better clustering performance
   
2. **Clustering Models Used:**
   - **K-Means Clustering**
   - **Agglomerative Hierarchical Clustering**
   - **Evaluation Metrics:**
     - **Silhouette Score**: Measures how well each point fits within its cluster
     - **Davies-Bouldin Score**: Evaluates cluster compactness and separation
   
3. **Cluster Visualization:**
   - Using PCA for dimensionality reduction
   - Visualizing clusters in 2D and 3D spaces
   - Analyzing cluster characteristics

## 📊 Results & Insights
- **Performance Metrics:**
  - **K-Means Clustering:**
    - Silhouette Score: **0.8931**
    - Davies-Bouldin Score: **0.5186**
  - **Agglomerative Clustering:**
    - Silhouette Score: **0.9376**
    - Davies-Bouldin Score: **0.3713**
- **Findings:**
  - Agglomerative Clustering outperformed K-Means based on evaluation metrics.
  - Revenue, copies sold, and playtime significantly influenced cluster formation.
  - Identified groups of games with high sales vs. niche games with high engagement.
