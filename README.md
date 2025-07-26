# 🛍️ Mall Customers Segmentation Project

### — An Unsupervised Learning Case Study

Customer segmentation is one of the most powerful and widely used applications of unsupervised learning in the domains of marketing and retail analytics. In this project, we explore mall customer data to uncover patterns in consumer behavior using clustering algorithms — **without relying on labeled outcomes**.

By identifying customer groups based on their demographics and spending habits, businesses can enhance personalized marketing, build targeted loyalty programs, and improve overall customer engagement and retention.

-----

## 🧠 Techniques Used

This project implements multiple **Unsupervised Machine Learning** techniques to discover natural groupings in customer data:

1. **K-Means Clustering**
   - Optimal number of clusters determined using the **Elbow Method** and **Within-Cluster Sum of Squares (WCSS)**
   - Identified clusters such as:
     - **Premium Customers** (High Income, High Spending)
     - **Budget Shoppers** (Low Income, High Spending)
     - **Low-Value Customers** (Low Income, Low Spending)

2. **Hierarchical Clustering**
   - Leveraged **SciPy’s linkage** method to create a **dendrogram**
   - Helped visualize nested clusters and determine natural cut-off points

3. **DBSCAN (Density-Based Spatial Clustering)**
   - Captured **non-spherical clusters** and identified **outliers**
   - Useful for noise-resistant customer grouping

4. **Preprocessing & Outlier Detection**
   - Standardization used for scaling features
   - Outliers handled through **boxplots** and visual inspection

-----
## 🔍 Key Insights

- **Premium Customers**: Young, high-income, and high-spending individuals — ideal targets for **loyalty and premium services**.
- **Budget Shoppers**: Lower income but high spending — highly responsive to **discounts and promotional campaigns**.
- **High-Income Low-Spenders**: Underutilized customers who may benefit from **upselling strategies**.
- **Demographics by Cluster**: Gender and age distribution across clusters supports **micro-targeting strategies**.

-----
## 🛠️ Tools & Libraries

- **Pandas, NumPy** — Data cleaning, manipulation, and transformation  
- **Matplotlib, Seaborn** — Data visualization and cluster plotting  
- **Scikit-learn** — K-Means, Agglomerative Clustering, DBSCAN  
- **SciPy** — Dendrograms and hierarchical clustering linkage methods

-----
## 📦 Installation & Running the Project

Clone the repository and install the dependencies:

```bash
git clone https://github.com/Himakar06/customers_segmentation.git
cd customers_segmentation
pip install -r requirements.txt

