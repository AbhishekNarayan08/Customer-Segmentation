# 🛍️ Customer Segmentation

This repository contains a Jupyter notebook that performs customer segmentation using clustering techniques on transactional data. The goal is to identify distinct customer groups to support targeted marketing and product recommendations.

---

## 📁 Repository Structure

```
.
├── CUSTOMER_SEGMENTATION.ipynb   # Jupyter notebook with end-to-end analysis
└── README.md                     # This file
```

---

## 🎯 Objective

Perform unsupervised customer segmentation to:
- Discover patterns in customer purchasing behavior.
- Cluster customers into homogeneous groups based on features like purchase frequency, monetary value, and recency.
- Provide actionable insights for personalized marketing strategies.

---

## 🔧 Requirements

Install the necessary Python packages:

```bash
pip install -r requirements.txt
```

_If `requirements.txt` is not present, install manually:_

```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly
```

---

## 🧩 Notebook Workflow

1. **Data Loading**  
   - Load transactional/customer dataset (e.g., CSV format) into a DataFrame.
2. **Data Preprocessing**  
   - Handle missing values.  
   - Feature engineering: compute RFM metrics (Recency, Frequency, Monetary).  
   - Normalize features for clustering.
3. **Exploratory Data Analysis (EDA)**  
   - Plot distributions and correlations of RFM features.  
   - Visualize customer profiles using pairwise plots or heatmaps.
4. **Clustering**  
   - **K-Means**: Determine optimal `k` using the elbow method and silhouette scores.  
   - **DBSCAN**: Explore density-based clustering to identify non-globular clusters/outliers.
5. **Cluster Evaluation**  
   - Compute silhouette score, Davies-Bouldin index for each algorithm.  
   - Analyze cluster centroids and sizes.
6. **Results & Insights**  
   - Interpret the characteristics of each cluster (e.g., high-value loyal customers, one-time buyers).  
   - Provide recommendations for marketing actions per segment.

---

## 🚀 How to Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/AbhishekNarayan08/Customer-Segmentation.git
   cd Customer-Segmentation
   ```
2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```
3. **Launch Jupyter Notebook**  
   ```bash
   jupyter notebook CUSTOMER_SEGMENTATION.ipynb
   ```
4. **Run all cells** to reproduce the analysis and visualizations.

---

## 👤 Author

**Abhishek Narayan**  
IIT Delhi  
