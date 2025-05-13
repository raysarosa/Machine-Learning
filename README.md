# 🏃‍♀️ Customer Segmentation for Sportify Using Clustering Techniques

This project was developed for the **Data Science and Machine Learning (DSML) 2023/2024** course. The goal was to apply unsupervised machine learning techniques to analyze and segment Sportify’s customer base using three datasets: **Digital Contact**, **Product Purchases**, and **Demographics**.

---

## 📁 Datasets Used

- `Digital_Contact.csv`: Engagement data (app, email, and social media interactions)
- `Products.xlsx`: Purchase history across product categories
- `Demographic.txt`: Customer attributes like name, birth year, city, education level

---

## 📌 Project Goals

- Clean and preprocess the datasets to prepare for analysis
- Apply clustering algorithms (K-Means, DBSCAN) to group customers
- Use dimensionality reduction (PCA, t-SNE) for visualization and improved clustering
- Describe clusters to identify customer profiles and recommend business actions

---

## 🧪 Methodology

### 🔍 Exploration
- Statistical and visual analysis of each dataset
- Key variables identified for clustering
- Creation of new variables (e.g., `Days_Since_Last_Purchase`, `age`, `gender`)

### 🧼 Preprocessing
- Normalization with `MinMaxScaler`
- Outlier detection and selective removal
- Missing value handling with `KNNImputer` and zero-fill

### 🤖 Modeling
- Clustering on **Digital Contact** and **Product** datasets:
  - K-Means (with and without PCA)
  - DBSCAN
  - t-SNE followed by K-Means or DBSCAN
- Cluster evaluation using:
  - Elbow method
  - Silhouette score
  - KL divergence (for t-SNE)

---

## 🔍 Cluster Profiles

### 💬 Digital Contact Segments
1. **Curious Viewers** – High email & SM clicks, low interactivity
2. **Influencers** – High SM likes, comments, shares
3. **App Users** – High app clicks, low SM engagement

### 🛍️ Product Purchase Segments
1. **Low Spenders**
2. **Sport Lovers**
3. **Outdoor Enthusiasts**
4. **Occasional Customers**

### 🧬 Combined Profiles (with Demographics)
- **Influencers & Sport Lovers** – Young, active, high spenders
- **App Users & Occasional Buyers** – Infrequent spenders
- **Curious Viewers & Low Spenders** – Older customers with minimal engagement
- … and more combinations based on cluster intersections

---

## 🎯 Business Recommendations

- **Target Influencers** via social media campaigns and loyalty rewards
- **Upsell Outdoor Enthusiasts** with bundled hiking gear
- **Re-engage Curious Viewers** via personalized email offers
- **Incentivize App Users** to become frequent buyers with app-only deals

---

## 📚 Tools & Libraries

- Python (Jupyter Notebook)
- `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- Algorithms: K-Means, DBSCAN, PCA, t-SNE
- Evaluation: Elbow method, Silhouette score, KL divergence

---

## 👥 Group Members

**Group 18 – DSML 2023/2024**

- Baran Can Çelik (20232067)  
- Carlos Lourenço (20232020)  
- Kida Aly (20231491)  
- Priyá Dessai (20232053)  
- Raysa Rocha (20232051)  

---

## 📄 Files

```bash
📁 Sportify-Clustering-Group18/
├── DSML202324_Cluster_Group18_Report.pdf
├── DSML202324_Cluster_Group18_Report.docx
├── DSML202324_Cluster_Group18_Notebook.ipynb
├── README.md
