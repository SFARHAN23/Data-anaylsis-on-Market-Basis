📌 Applied Data Science (ADS) Project
Market Basket Analysis & Customer Segmentation

🚀 Analyzing customer purchase behavior using Association Rule Mining and Machine Learning techniques.

📜 Project Overview
This project applies Market Basket Analysis (MBA) and Customer Segmentation techniques to understand shopping patterns in a grocery store dataset. Using Apriori, FP-Growth, and AClose algorithms, we identify frequent itemsets and association rules to improve business insights. Additionally, we use clustering and classification models to categorize customer purchasing behaviors.

📂 Repository Contents
File Name	Description
ADS_PROJECT.ipynb	Jupyter Notebook with data analysis, association rule mining, and clustering.
ADS PROJECT.ipynb - Colab.pdf	PDF version of the Jupyter Notebook for easy reference.
ADS_project.pdf	Complete project report detailing methodology, results, and business impact.
README.md	This file, providing an overview of the project.
📊 Project Breakdown
🔹 1. Exploratory Data Analysis (EDA) & Preprocessing
✔️ Cleaning & formatting the dataset
✔️ Identifying missing values and handling inconsistencies
✔️ Visualizing product frequency, customer trends, and purchase patterns

🔹 2. Market Basket Analysis (Association Rule Mining)
✔️ Apriori Algorithm → Extracts frequent itemsets based on minimum support threshold
✔️ FP-Growth Algorithm → Faster alternative to Apriori for large datasets
✔️ AClose Algorithm → Finds closed frequent itemsets efficiently
✔️ Extracting Association Rules → Helps understand co-purchased items

📌 Example Insight:
💡 If a customer buys milk, they have a 70% probability of also buying bread.

🔹 3. Customer Segmentation & Predictive Modeling
✔️ Clustering Methods:

DBSCAN (Density-Based Clustering)
HDBSCAN (Hierarchical Clustering)
AGNES (Agglomerative Clustering)
✔️ Classification Models:

Decision Trees, Naïve Bayes, Support Vector Machines (SVM)
Used to predict customer buying behavior
🔹 4. Big Data Processing with PySpark
✔️ Optimized Apriori & FP-Growth for large-scale transaction data
✔️ Improved performance over traditional Python implementations

📈 Key Findings & Business Impact
📌 Top-Selling Items: Milk, Vegetables, Soda, Bread
📌 Peak Sales Days: Thursdays have the highest transactions
📌 Customer Segments Identified:
✔️ Casual Shoppers (21%) – Infrequent purchases
✔️ Regular Customers (70%) – Weekly buyers
✔️ Loyal Customers (9%) – Frequent high-value transactions

📌 Business Recommendations:
✅ Bundle Promotions: Offer discounts on frequently co-purchased items (e.g., milk + cereal)
✅ Personalized Marketing: Suggest relevant products based on past purchases
✅ Stock Optimization: Maintain higher inventory for high-frequency items

⚙️ Technologies Used
🔹 Programming Languages: Python
🔹 Libraries: Pandas, NumPy, Scikit-learn, Mlxtend (Apriori, FP-Growth)
🔹 Visualization: Matplotlib, Seaborn, Plotly
🔹 Big Data Tools: PySpark
🔹 Notebook Execution: Google Colab

📌 How to Use This Repository
🔹 Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/ADS_Project.git
cd ADS_Project
🔹 Run the Jupyter Notebook
You can open ADS_PROJECT.ipynb in Jupyter Notebook or Google Colab to execute the analysis.

👨‍💻 Contributors
📌 Syed Farhan (CS23B2039)
📌 Mohamed Amjad (CS23B2013)
📌 Raviteja B (CS23B2011)

📝 Future Scope:
🔹 Deploy a recommender system for personalized shopping
🔹 Integrate with a real-time analytics dashboard (Streamlit/Tableau)
🔹 Improve model accuracy using deep learning

⭐ If you found this project useful, don’t forget to star ⭐ the repository!
This README.md follows a structured format with clear sections and detailed explanations. Let me know if you want any modifications! 🚀







