# 🛍️ Customer Segmentation using K-Means Clustering

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-KMeans-orange)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📌 Project Overview
This project uses **K-Means Clustering** to segment customers of a shopping mall based on their **Annual Income** and **Spending Score**.  
The segmentation helps businesses understand customer behavior and plan targeted marketing campaigns.  

> **Goal:** Group customers with similar shopping patterns to improve decision-making.

---

## 📂 Dataset
The dataset contains:
- 🆔 **CustomerID**
- 👤 **Gender**
- 🎂 **Age**
- 💰 **Annual Income (k$)**
- 🛒 **Spending Score (1–100)**

---

## 🛠️ Technologies Used
- **Python 3**
- **Pandas, NumPy** → Data handling
- **Matplotlib, Seaborn** → Data visualization
- **Scikit-learn** → Machine learning (K-Means)

---

## 🔍 Project Workflow
1. **📥 Import Dependencies** – Load required Python libraries.
2. **📊 Data Collection & EDA** – Explore dataset, visualize distributions.
3. **🎯 Feature Selection** – Select `Annual Income` & `Spending Score`.
4. **📈 Optimal Clusters** – Use **Elbow Method** (WCSS) to find `k`.
5. **🤖 Model Training** – Train **K-Means Clustering**.
6. **🎨 Visualization** – Plot distinct customer clusters.

---

## 📊 Results
✅ Customers are divided into **clear, meaningful segments**.  
✅ Helps identify **high-value, moderate, and low-spending groups**.  
✅ Ideal for **targeted marketing**.

---

## 🖼️ Sample Visualization
*(Add your output image here)*  
![Clusters](images/customer_clusters.png)

---

## 🚀 How to Run
```bash
# Clone the repository
git clone <repo_url>
cd Project_13_Customer_Segmentation_using_K_Means_Clustering

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Project_13_Customer_Segmentation_using_K_Means_Clustering.ipynb
