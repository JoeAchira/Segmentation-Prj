# Customer Segmentation-Project
Using customer segmentation for e-commerce marketing and customer retention optimisation

### Project Overview
This project applies unsupervised machine learning to segment customers based on transaction and demographic data.  
The objective was to uncover hidden behavioral patterns and group customers into actionable segments for personalised marketing and retention strategies.

This project formed part of my **Cambridge Data Science course** and focuses on **data preprocessing, dimensionality reduction, and clustering interpretation**.

---

### Objectives
- Segment customers using unsupervised learning techniques.
- Identify key behavioral and demographic traits of each segment.
- Visualise cluster separation and interpret business insights.

---

### Methods & Tools
- **Languages:** Python  
- **Libraries:** pandas, NumPy, scikit-learn, matplotlib, seaborn, plotly  
- **Techniques:**
  - Data cleaning and normalisation
  - Exploratory data analysis and correlation analysis
  - Principal Component Analysis (PCA)
  - K-Means and Hierarchical Clustering
  - Elbow method and Silhouette Score optimisation
  - Cluster profiling and visualisation

---

### Model Development Steps
1. **Data Preparation:**  
   Cleaned missing values and scaled numeric features using StandardScaler.
2. **Dimensionality Reduction:**  
   Applied PCA to visualise high-dimensional data and reduce noise.
3. **Model Training:**  
   Ran K-Means with varying `k` values to determine optimal clusters.
4. **Evaluation:**  
   Used Silhouette Score and Davies–Bouldin index to assess cluster validity.
5. **Profiling:**  
   Characterised each segment based on behavioral and demographic averages.

---

### Results
| Cluster | Characteristics | Potential Action |
|----------|----------------|------------------|
| 0 | High spenders, frequent transactions | Loyalty rewards & premium offers |
| 1 | Low engagement, low value | Targeted retention campaigns |
| 2 | Young, digital-savvy users | Cross-selling digital banking products |

**Optimal number of clusters:** 3 (based on Elbow and Silhouette analysis)

---

### Learning Outcomes
- Gained hands-on experience with clustering and dimensionality reduction.
- Improved interpretation of unsupervised learning results in a business context.
- Enhanced data visualisation and storytelling for segmentation insights.

---

### Next Steps
- Test additional clustering algorithms (DBSCAN, Gaussian Mixture Models).
- Integrate clustering output with customer churn and fraud prediction models.

---

### Acknowledgment
Completed as part of the **University of Cambridge Data Science Certificate** program.

---

### 📚 References
- [Scikit-learn Clustering Guide](https://scikit-learn.org/stable/modules/clustering.html)
- [K-Means Clustering in Practice](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
