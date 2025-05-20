# Spotify Segmentation

This project applies unsupervised and supervised machine learning techniques to analyze a dataset of over 2,000 Spotify tracks. The goal is to understand the drivers of song popularity and develop models to predict future hits.

## 📁 Project Structure

Spotify-Segmentation/
├── data/
│ ├── data.csv
│ ├── segmented_genres.csv
│ └── Songs_2025.xlsx
├── Spotify Segmentation.ipynb
├── README.md
└── requirements.txt

## 📌 Objectives

This analysis was conducted for a fictional record label and focuses on:
- **Segmentation** of songs to identify clusters of similar musical characteristics.
- **Predictive modeling** of track popularity using linear regression.
- **Strategic recommendations** for playlist curation, marketing, and artist investment.

## 📊 Methodology

- **Exploratory Data Analysis (EDA):** Visualization of genre, tempo, speechiness, and other features influencing track popularity.
- **Segmentation Models:**
  - DBSCAN: Limited clustering, useful for outlier detection.
  - Gaussian Mixture Models (GMM): Flexible but unsuitable for regression.
  - K-Means: Final chosen method, producing 4–6 meaningful clusters.
- **Regression Analysis:**
  - Predicts track popularity based on song attributes and cluster labels.
  - Segmented models outperform global models in predictive accuracy.

## 🎯 Key Insights

- Artist popularity is the most powerful predictor of track success.
- Segmentation improves prediction accuracy and enables targeted marketing.
- Clusters with high danceability and speechiness perform better in pop/rap genres.
- External factors like branding and playlist placement are crucial for success.

## 📈 Recommendations

- Use the **5-cluster K-Means model** for strategic playlisting and marketing.
- Support niche segments like instrumental or spoken-word tracks with tailored playlists.
- Adopt hybrid recommendation systems to personalize listener experience.

## 🧠 Tools & Libraries

- Python, pandas, matplotlib, seaborn
- Scikit-learn (KMeans, DBSCAN, GMM, regression)
- PCA for dimensionality reduction

## 📄 References

- [Songs_2025.xlsx](./data/Songs_2025.xlsx) provided by IE University for the Machine Learning I course.
- Analysis performed as part of a group project for a fictional record label.

---

*Prepared by:*  
Emin Abrahamian
Abdulrahman Alabdulkarim 
Nicole M. Batinovich    
Miguel Rodríguez  
Ignacio Salceda
