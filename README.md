# 📌 **Applied Data Science (ADS) Project**  
## **Market Basket Analysis using Association Rule Mining & Customer Segmentation**  

📊 **Understanding customer purchase behavior through data-driven insights.**  

## 📜 **Project Overview**  
This project implements **Market Basket Analysis (MBA)** and **Customer Segmentation** techniques to extract insights from transaction data.  
Using **Apriori, FP-Growth, and AClose algorithms**, we identify **frequent itemsets and association rules** that help businesses optimize **inventory and promotions**.  
Additionally, clustering models classify customers based on **purchasing behavior**.  

---

## 📂 **Repository Contents**  

| 📄 **File Name**            | 📝 **Description**  |
|----------------------------|--------------------|
| 📁 `ADS_PROJECT.ipynb`       | Jupyter Notebook with code for **data processing, analysis, and modeling**. |
| 📄 `ADS_PROJECT_Colab.pdf`  | PDF version of the notebook for easy reference. |
| 📑 `ADS_project.pdf`        | Full project report covering **methodology, results, and business insights**. |
| 📜 `README.md`              | This file, providing an **overview of the project**. |

---

## 📊 **Project Breakdown**  

### 🔹 **1. Data Preprocessing & Exploratory Data Analysis (EDA)**  
✔️ **Cleaning & structuring the dataset**  
✔️ **Handling missing values & data inconsistencies**  
✔️ **Visualizing purchase frequency, transaction patterns, and customer trends**  

### 🔹 **2. Market Basket Analysis (Association Rule Mining)**  
✔️ **Apriori Algorithm** – Identifies frequent itemsets based on **support threshold**  
✔️ **FP-Growth Algorithm** – Efficient alternative to **Apriori** for large datasets  
✔️ **AClose Algorithm** – Extracts **closed frequent itemsets**  
✔️ **Generating Association Rules** – Insights into **co-purchased items**  

📌 **Example Insight:**  
💡 Customers who buy **bread** have a **65% probability** of also purchasing **butter**.  

### 🔹 **3. Customer Segmentation & Behavioral Analysis**  
✔️ **Clustering Techniques Used:**  
   - **DBSCAN & HDBSCAN** – Detects **high-density customer groups**  
   - **AGNES (Agglomerative Clustering)** – **Hierarchical segmentation**  

✔️ **Classification Models:**  
   - **Decision Trees, Naïve Bayes, and SVM** – Predict **customer buying behavior**  

### 🔹 **4. Big Data Processing using PySpark**  
✔️ Implemented **Apriori & FP-Growth** on **large-scale datasets**  
✔️ Enhanced **computational efficiency**  

---

## 📈 **Key Findings & Business Impact**  

📌 **Top-Selling Products:** **Milk, Vegetables, Soft Drinks, Bread**  
📌 **Peak Sales Days:** **Thursdays have the highest transactions**  

📌 **Customer Segments Identified:**  
✔️ **Casual Shoppers (21%)** – Infrequent purchases  
✔️ **Regular Customers (70%)** – Weekly buyers  
✔️ **Loyal Customers (9%)** – Frequent high-value purchases  

📌 **Business Recommendations:**  
✅ **Product Bundling:** Offer discounts on frequently **co-purchased items** (e.g., coffee + sugar)  
✅ **Personalized Offers:** Suggest products based on **past purchases**  
✅ **Stock Optimization:** Ensure availability of **high-frequency items**  

---

## ⚙️ **Technologies Used**  
🔹 **Programming Languages:** `Python`  
🔹 **Libraries:** `Pandas`, `NumPy`, `Scikit-learn`, `Mlxtend (Apriori, FP-Growth)`  
🔹 **Visualization:** `Matplotlib`, `Seaborn`, `Plotly`  
🔹 **Big Data Tools:** `PySpark`  
🔹 **Notebook Execution:** `Google Colab`  

---

## 📌 **How to Use This Repository**  

🔹 **Clone the Repository**  
```bash
git clone https://github.com/your-username/ADS_Project.git
cd ADS_Project
