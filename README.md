# 🎧 Music Recommendation Engine with Clustering | Nowa Analytics

This project was developed by the Nowa Analytics consultancy as part of a machine learning pipeline focused on improving a music recommendation system using **PySpark** and **unsupervised learning techniques**.

## 🚀 Project Overview

Our client, the platform **Amantes da Música**, currently uses a basic music recommendation system based only on genre. However, the recommendations have not been satisfactory for users.

To enhance this experience, the Nowa Analytics team proposed the use of **clustering techniques** and **dimensionality reduction** to identify deeper patterns in the music dataset and deliver smarter, more personalized playlists.

The final deliverable is a function that, given a reference song, returns a playlist of similar tracks — presented with album covers and track names.

---

## 🔧 Technologies Used

* **Python 3**
* **Apache Spark (PySpark)**

  * Spark SQL
  * Spark MLlib (for Machine Learning)
* **Plotly** (for data visualization)

---

## 📊 Pipeline Steps

1. **Data Ingestion & Manipulation**

   * Reading and cleaning data using **PySpark SQL**
   * Exploring musical attributes beyond just genre

2. **Feature Engineering**

   * Vectorizing features
   * Applying **Principal Component Analysis (PCA)** for dimensionality reduction

3. **Clustering**

   * Building clusters using the **K-means** algorithm in PySpark MLlib
   * Grouping songs based on similarity of multiple attributes

4. **Playlist Generation Function**

   * Input: A selected song
   * Output: A personalized playlist of similar songs with metadata and cover art

5. **Data Visualization**

   * Using **Plotly** to visually explore the clusters and music distribution

---

## 📁 Folder Structure

```
📂 music-recommendation
├── 📁 data                # Dataset used for clustering
├── 📁 notebooks           # Jupyter/Colab notebooks with exploratory analysis
├── 📁 src                 # PySpark scripts and ML pipeline code
├── 📁 images              # Visualizations and cluster plots
├── playlist_generator.py # Playlist generation function
└── README.md
```

---

## 📌 Key Concepts Learned

* Building ML pipelines in PySpark
* Using **K-means clustering** for recommendations
* Applying **PCA** for dimensionality reduction
* Data visualization with **Plotly**
* Delivering real-world solutions for music-based user engagement

---

## 🤝 Contribution

This project is part of the Nowa Analytics lab. Contributions and suggestions are welcome via pull request or issue.

---

## 📬 Contact

**Nowa Analytics**
Data solutions for the real world.
🌍 Offices in London | Madrid | São Paulo
📧 [contact@nowaanalytics.com](mailto:contact@nowaanalytics.com)


