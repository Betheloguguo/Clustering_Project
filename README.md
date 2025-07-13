## Customer Segmentation with K-Means Clustering

### **Overview**
This project applies K-Means clustering to the [Online Retail II dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II) to segment customers based on their purchasing behavior. The goal is to identify distinct customer groups for targeted marketing and business strategies.

---

### **Dataset**
- **Source:** UK-based online retail transactions from 01/12/2009 to 09/12/2011.
- **Features:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country.

---

### **Objectives**
- **Exploratory Data Analysis:** Understand data structure, spot anomalies, and visualize distributions.
- **Data Cleaning & Transformation:** Handle missing values, duplicates, and outliers.
- **Feature Engineering:** Create Recency, Frequency, and Monetary (RFM) features for each customer.
- **Data Preprocessing:** Scale features and remove outliers for effective clustering.
- **Customer Segmentation:** Use K-Means to segment customers into actionable groups.
- **Cluster Analysis:** Profile each cluster and provide business recommendations.

---

### **Methodology**
1. **Data Cleaning:**  
   - Remove duplicates, handle missing values, and filter out irrelevant transactions.
2. **Feature Engineering:**  
   - Calculate RFM metrics for each customer.
3. **Outlier Handling:**  
   - Identify and separate outliers in Frequency and Monetary features.
4. **Scaling:**  
   - Standardize features for clustering.
5. **Clustering:**  
   - Apply K-Means and determine optimal cluster count using Elbow and Silhouette methods.
6. **Cluster Profiling:**  
   - Assign descriptive labels to clusters (e.g., VIPs, Nurture, Re-engage).
   - Visualize cluster distributions and feature means.

---

### **Key Results**
- Customers are segmented into groups such as VIPs, Nurture, Maintain, Re-engage, Upsell, and Encourage.
- Each segment is profiled by average recency, frequency, and monetary value.
- Visualizations include bar plots and line plots for cluster sizes and feature means.

---

### **Business Implications**
- **VIPs:** Retain with exclusive offers and personalized service.
- **Nurture:** Engage with loyalty programs and incentives to increase value.
- **Maintain:** Prevent churn with regular communication and offers.
- **Re-engage:** Target lapsed customers with win-back campaigns.
- **Upsell:** Identify customers with potential to spend more.
- **Encourage:** Test activation strategies for least engaged customers.

---

### **Dependencies**
- Python 3.x
- pandas, numpy, matplotlib, seaborn, scikit-learn, missingno

---

This project demonstrates practical customer segmentation for data-driven marketing and business decision-making.
