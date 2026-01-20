# 🧠 Understanding Customer Patterns Through Hierarchical Clustering and Dendrogram Analysis

## 📌 Project Overview
This project focuses on customer segmentation using **Hierarchical Clustering**, an unsupervised machine learning technique that identifies natural groupings in data. The analysis uses **Age, Annual Income, and Spending Score** to understand customer behavior without assuming the number of clusters in advance. A **dendrogram** is used to visualize and interpret cluster relationships.

---

## 📊 Dataset Description
The dataset contains:
- Customer ID  
- Age  
- Annual Income (k$)  
- Spending Score (1–100)  

**Features used for clustering:**
- Age  
- Annual Income (k$)  
- Spending Score  

---

## ⚙️ Methodology
1. Loaded and explored the dataset  
2. Performed data preprocessing and feature selection  
3. Computed distance metrics  
4. Applied Agglomerative Hierarchical Clustering  
5. Visualized clusters using dendrogram analysis  
6. Interpreted customer segments  

---

## 🌳 Dendrogram Analysis
The dendrogram illustrates how customers merge into clusters at different similarity levels. By analyzing vertical distances, meaningful cut points are selected to determine optimal customer segments, enabling flexible and interpretable clustering.

---

## 🧠 Algorithm Used
**Hierarchical Clustering (Agglomerative)**
- Bottom-up clustering approach  
- No predefined cluster count  
- Interpretable cluster structure  
- Effective for exploratory analysis  

---

## 📈 Results and Insights
- Identified distinct customer groups  
- Discovered sub-groups within major segments  
- Enabled multi-level customer segmentation  
- Provided actionable business insights  

---

## 📌 Use Cases
- Customer behavior analysis  
- Targeted marketing strategies  
- Identification of niche customer segments  
- Exploratory business analytics  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- SciPy  
- Matplotlib  

---

## 🚀 How to Run the Project
```bash
git clone https://github.com/your-username/your-repo-name.git
pip install pandas numpy scikit-learn scipy matplotlib
