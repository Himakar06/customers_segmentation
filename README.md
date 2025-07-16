# Mall Customers Segmentation Project

— Unsupervised Learning Project
Customer segmentation is one of the most impactful applications of unsupervised learning in marketing and retail analytics. In this project, we analyze mall customer data using clustering techniques to uncover hidden patterns in consumer behavior — without using any labeled outcomes. By understanding how customers differ in their spending habits and income levels, businesses can personalize marketing strategies, design loyalty programs, and improve customer retention.

# Techniques Used
Applied unsupervised machine learning techniques to discover natural groupings in the data:
1.K-Means Clustering: The Elbow Method and WCSS were used to determine the optimal number of clusters. This approach revealed segments like Premium Customers, Budget Shoppers, and Low-Value Customers.
2.Hierarchical Clustering: A dendrogram was plotted using scipy's linkage method to visualize cluster formation and determine the natural cut-off for grouping.
3.DBSCAN: This density-based clustering algorithm identified outliers and captured non-spherical clusters that K-Means might miss.
4.Data was preprocessed via scaling (standardization), and outliers were handled using boxplots and visual analysis.

 # Insights Derived
1.Premium customers are typically young individuals with high income and high spending scores — ideal for loyalty programs.
2.Budget shoppers have lower income but high spending scores — responsive to offers and deals.
3.High-income, low-spending segments indicate untapped potential for up-selling or targeted engagement.
4.Gender distribution and age spread across clusters help tailor strategies more precisely.

# Tools & Libraries
-->Pandas, NumPy for data handling
-->Matplotlib, Seaborn for visualizations
-->Scikit-learn for K-Means, Agglomerative, and DBSCAN clustering
-->SciPy for hierarchical clustering and dendrograms

