# Personalized-Music-Recommendations-ML
Unsupervised machine learning project clustering Rolling Stones songs from Spotify to uncover patterns in music features and support recommendation systems.

---

## Project Overview ??? 
This project applies **unsupervised machine learning** to cluster songs from Spotify's Rolling Stones albums. By combining **exploratory data analysis (EDA)**, **feature engineering**, and **clustering algorithms**, the goal is to uncover hidden patterns in song features and create **cohorts of similar songs**.  

Such cohorts can be used to improve **music recommendation systems**, helping streaming platforms deliver **personalized content** and enhance user engagement.  

---

## Objectives ????  
- Perform **data cleaning and preprocessing** on Spotify song dataset.  
- Conduct **exploratory data analysis (EDA)** to uncover patterns.  
- Engineer meaningful features for clustering.  
- Apply **dimensionality reduction techniques** (e.g., PCA, t-SNE) for visualization.  
- Build **clustering models** (K-Means, Hierarchical, DBSCAN).  
- Define **song cohorts** and analyze their characteristics.  
- Provide insights for **recommendation systems**.  

---

## Dataset  ????
- Source: Spotify API (Rolling Stones albums dataset).  
- Each track includes metadata and audio features such as:  
  - **Acousticness, Danceability, Energy, Instrumentalness, Liveness, Loudness**  
  - **Speechiness, Valence, Tempo**  
  - **Popularity, Duration, Release Date, Album Info**  
- Each song has a unique **Spotify ID** and **URI**.  

---

## Methodology  ???

1. **Data Inspection & Cleaning**  
   - Handle duplicates, missing values, validate unique song IDs
   - Visualize distribution of song features.
   - Check for outliers and handle them.
   - Remove significant outliers from the dataset and save the cleaned dataset

2. **Exploratory Data Analysis (EDA) and Feature Engineering**  
   - Recommend albums and songs based on popularity
   - Examine correlations between song features, especially popularity.    
   - Analyze popularity trends over time.

3. **Feature Engineering & Dimensionality Reduction**  
   - Scale features for clustering.  
   - Apply PCA and t-SNE for dimensionality reduction and cluster visualization, respectively. 

4. **Clustering Analysis**  
   - Determine optimal number of clusters uisng Elbow method
   - Apply clustering methods and compare their performance

5. **Insights & Recommendations**  
   - Define cohorts based on musical attributes.  
   - Identify which albums/songs belong to high-popularity clusters.  
   - Provide implications for recommendation systems.  

---

## Expected Results  ???
- Songs grouped into **cohorts with similar acoustic and popularity profiles**.  
- Identification of **albums with the highest density of popular songs**.  
- Visualization of clusters in reduced feature space.  
- Actionable insights to **enhance personalized music recommendations**.  

---

## Business Impact  ???
- Helps streaming services (e.g., Spotify, Apple Music) improve **user engagement**.  
- Enables **personalized playlist generation**.  
- Provides insights for **music marketing strategies**.  
- Framework applicable to **any artist’s catalog or broader music dataset**.  

---

## Tech Stack  ???
- **Python**: Pandas, NumPy, Scikit-learn  
- **Visualization**: Matplotlib, Seaborn, Plotly  
- **Clustering**: K-Means, Hierarchical, DBSCAN, Mean Shift, Gaussian Mixture Models (GMM)   
- **Dimensionality Reduction**: PCA, t-SNE(t-distributed Stochastic Neighbor Embedding), UMAP(Uniform Manifold Approximation and Projection), ICA(Independent Component Analysis)
- **Jupyter Notebook** for analysis  

---
 
## Repository Structure  ???

```
Marketing-Campaign-Analysis-with-EDA-and-Hypothesis-Testing/
├── Data/
│ ├── interim/
│ │   ├── data_outliers_cleared.parquet
│ │   └── df_reduced_dim.parquet
│ └── raw/
│     ├── Data Dictionary-Creating cohorts of songs.xlsx
│     └── rolling_stones_spotify.csv
├── Jupyter_notebook_Scripts/
│     ├── 01_Data_Inspection_Cleaning.ipynb
│     ├── 02_Exploratory_Data Analysis_(EDA)_Feature_Engineering.ipynb
│     ├── 03_Feature_Engineering_Dimensionality_Reduction.ipynb 
│     └── 04_Clustering_Analysis.ipynb
├── Output/
│     ├── 01_.docx
│     ├── 02_.docx
│     ├── 03_.docx 
│     └── 04_.docx
└── README.md

```


---

## Next Steps  ????
- Expand dataset to include more artists and genres.  
- Test deep learning–based clustering (autoencoders).  
- Integrate with a **recommendation system prototype**.  

---

## Author
**Abolfazl Zolfaghari**  
[Email](ab.zolfaghari.abbasghaleh) | [GitHub](https://github.com/abolfazl6678)

---













