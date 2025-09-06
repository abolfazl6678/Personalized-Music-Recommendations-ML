# Personalized-Music-Recommendations-ML
Unsupervised machine learning project clustering Rolling Stones songs from Spotify to uncover patterns in music features and support recommendation systems.

---

## 📌 Project Overview  
This project applies **unsupervised machine learning** to cluster songs from Spotify's Rolling Stones albums. By combining **exploratory data analysis (EDA)**, **feature engineering**, and **clustering algorithms**, the goal is to uncover hidden patterns in song features and create **cohorts of similar songs**.  

Such cohorts can be used to improve **music recommendation systems**, helping streaming platforms deliver **personalized content** and enhance user engagement.  

---

## 🎯 Objectives  
- Perform **data cleaning and preprocessing** on Spotify song dataset.  
- Conduct **exploratory data analysis (EDA)** to uncover patterns.  
- Engineer meaningful features for clustering.  
- Apply **dimensionality reduction techniques** (e.g., PCA, t-SNE) for visualization.  
- Build **clustering models** (K-Means, Hierarchical, DBSCAN).  
- Define **song cohorts** and analyze their characteristics.  
- Provide insights for **recommendation systems**.  

---

## 📂 Dataset  
- Source: Spotify API (Rolling Stones albums dataset).  
- Each track includes metadata and audio features such as:  
  - 🎶 **Acousticness, Danceability, Energy, Instrumentalness, Liveness, Loudness**  
  - 🗣️ **Speechiness, Valence, Tempo**  
  - 📊 **Popularity, Duration, Release Date, Album Info**  
- Each song has a unique **Spotify ID** and **URI**.  

---

## 🛠️ Methodology  

1. **Data Inspection & Cleaning**  
   - Handle duplicates, missing values, and outliers.  
   - Validate unique song IDs.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize distribution of song features.  
   - Analyze popularity trends across albums and time.  
   - Examine correlations between popularity and features.  

3. **Feature Engineering & Dimensionality Reduction**  
   - Scale features for clustering.  
   - Apply PCA/t-SNE for visualization and dimensionality reduction.  

4. **Clustering Analysis**  
   - Determine optimal number of clusters (Elbow method, Silhouette score).  
   - Apply algorithms: **K-Means**, **Hierarchical Clustering**, **DBSCAN**.  
   - Interpret and label song clusters.  

5. **Insights & Recommendations**  
   - Define cohorts based on musical attributes.  
   - Identify which albums/songs belong to high-popularity clusters.  
   - Provide implications for recommendation systems.  

---

## 📊 Expected Results  
- Songs grouped into **cohorts with similar acoustic and popularity profiles**.  
- Identification of **albums with the highest density of popular songs**.  
- Visualization of clusters in reduced feature space.  
- Actionable insights to **enhance personalized music recommendations**.  

---

## 💼 Business Impact  
- Helps streaming services (e.g., Spotify, Apple Music) improve **user engagement**.  
- Enables **personalized playlist generation**.  
- Provides insights for **music marketing strategies**.  
- Framework applicable to **any artist’s catalog or broader music dataset**.  

---

## 🛠️ Tech Stack  
- **Python**: Pandas, NumPy, Scikit-learn  
- **Visualization**: Matplotlib, Seaborn, Plotly  
- **Clustering**: K-Means, Hierarchical, DBSCAN  
- **Dimensionality Reduction**: PCA, t-SNE  
- **Jupyter Notebook** for analysis  

---
 
## 📁 Repository Structure  

├── data/ # Dataset (Spotify songs)
├── notebooks/ # Jupyter notebooks for EDA and clustering
├── src/ # Python scripts for modular pipeline
├── results/ # Cluster visualizations and reports
└── README.md # Project documentation


---

## 🚀 Next Steps  
- Expand dataset to include more artists and genres.  
- Test deep learning–based clustering (autoencoders).  
- Integrate with a **recommendation system prototype**.  

---
---

## Author

**Abolfazl Zolfaghari**  
Data Science Graduate — Caltech  
[Email](ab.zolfaghari.abbasghaleh) | [GitHub](https://github.com/abolfazl6678)

---

---













