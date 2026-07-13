# 🛍️ Customer Segmentation using RFM, K-Means & Apriori

A Data Mining project that applies **RFM Analysis**, **K-Means Clustering**, and **Apriori Association Rule Mining** to analyze customer purchasing behavior using the Online Retail dataset.

---

## 👥 Team

| Member | Contribution |
|---------|--------------|
| **Ali Mostafa** | Project Lead, Data Preprocessing, RFM Feature Engineering, Integration, GitHub Repository Management |
| **Abdelrahman Hadedy** | Built the initial K-Means clustering model and generated the first customer segments. |
| **Nada Ahmed** | Performed Exploratory Data Analysis (EDA), data visualization, Elbow Method, and Silhouette Score analysis. |
| **Mahmoud Maher** | Built the final clustering model, validated the results, compared clustering performance before and after outlier handling, and finalized the technical evaluation. |
| **Katreen Maher** | Interpreted clusters, created customer personas, named customer segments, wrote business insights, recommendations, and project documentation. |
| **Mahmoud Ahmed** | Prepared and organized the final project report. |

---

# 📖 Project Overview

This project focuses on customer segmentation by transforming transactional retail data into customer behavioral features using the **RFM (Recency, Frequency, Monetary)** model. The processed data is clustered using **K-Means**, while **Apriori Association Rule Mining** is applied to discover products that are frequently purchased together.

---

# 📂 Dataset

**Online Retail Dataset**

The dataset contains one year of transactions from an online retail store.

Main Features:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

---

# ⚙️ Data Preprocessing

- Removed missing Customer IDs
- Removed cancelled transactions
- Removed invalid prices
- Converted InvoiceDate to datetime
- Created TotalPrice feature
- Generated RFM features
- Applied feature scaling using StandardScaler

---

# 📊 Exploratory Data Analysis

- Distribution Analysis
- Boxplots
- Correlation Heatmap
- Pairplot
- Log Transformation
- RFM Score Analysis

---

# 🤖 Customer Segmentation

The project applies **RFM Analysis** followed by **K-Means Clustering** to group customers according to their purchasing behavior.

The optimal number of clusters was selected using:

- Elbow Method
- Silhouette Score

---

# 🛒 Association Rule Mining

The Apriori Algorithm was applied to discover products frequently purchased together using:

- Support
- Confidence
- Lift

This helps businesses improve:

- Product Recommendation
- Cross-selling
- Marketing Campaigns

---

# 🛠️ Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- mlxtend
- Jupyter Notebook

---

# 🚀 Results

- Customer segmentation using RFM and K-Means.
- Cluster evaluation using Elbow Method and Silhouette Score.
- Customer behavior analysis.
- Product association discovery using Apriori.
- Business insights and recommendations.

---

# 👨‍💻 Author

**Ali Mostafa**

AI Engineer | AI Agent Developer

- LinkedIn: https://www.linkedin.com/in/ali-developments/
- GitHub: https://github.com/Ali-Developments
