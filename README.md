# 🌍 Country Clustering — Hierarchical Analysis

A machine learning project that groups countries based on socio-economic indicators using **Hierarchical Clustering**.

---

## 📦 Dataset

- **Source**: [Kaggle — Country Data](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data)
- **File**: `Country-data.csv`
- **Rows**: 167 countries

---

## 🧪 Features Used

| Feature | Description |
|---|---|
| `child_mort` | Child mortality rate |
| `exports` | Exports as % of GDP |
| `imports` | Imports as % of GDP |
| `income` | Net income per person |
| `inflation` | Inflation rate |
| `life_expec` | Life expectancy |
| `total_fer` | Total fertility rate |
| `gdpp` | GDP per capita |

---

## ⚙️ How It Works

1. Load and clean the dataset
2. Select socio-economic features
3. Scale features using StandardScaler
4. Build linkage matrix using Ward Method
5. Plot Dendrogram to visualize clusters
6. Assign clusters using fcluster
7. Evaluate using Silhouette Score
8. Visualize with Scatter Plot and Heatmap

---

## 📊 Results

- **Clusters Found**: 3
- **Method**: Ward Linkage (Hierarchical)
- **Evaluation**: Silhouette Score

---

## 🛠️ Libraries Used

pandas, numpy, matplotlib, seaborn, scikit-learn, scipy

---

## 🚀 How to Run

pip install pandas numpy matplotlib seaborn scikit-learn scipy

python country-clustering.ipynb

---

## 👤 Author

**Umer Ameen**
