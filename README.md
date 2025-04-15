# 🧭 TripAdvisor Resort Review Clustering

This project explores unsupervised machine learning techniques to segment user reviews of resorts in Asia from TripAdvisor. Using clustering algorithms like **K-Means**, the goal is to group similar resorts based on user ratings across various categories such as restaurants, juice bars, religious institutions, and more.

By identifying meaningful clusters, we can better understand traveler preferences and uncover hidden patterns in customer feedback—insights that are valuable for tourism marketing, personalized recommendations, and business strategy.

---

## 🧠 Project Highlights

- Data standardization using `StandardScaler`  
- K-Means clustering with `n_clusters=3`  
- Visualizations using pair plots to explore cluster boundaries  
- Cluster evaluation using the **Silhouette Score**

---

## 📁 Dataset

The dataset consists of average ratings per resort across various service and experience categories. All resorts are located in Asia and were reviewed by users on TripAdvisor.

---

## 🚀 Objective

To segment resorts based on review patterns and evaluate the quality of clustering without labeled data, using both visualization and silhouette metrics.