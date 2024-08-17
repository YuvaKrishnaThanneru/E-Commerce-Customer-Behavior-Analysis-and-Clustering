<div align="center">
  <h1 style="color:#8a2be2; margin-right: 20px;">E-Commerce-Customer-Behavior-Analysis-and-Clustering</h1>
  <img src="https://github.com/user-attachments/assets/50485221-a851-4da0-bcb9-648c3cbcd4d5" width="340">
  <img src="https://github.com/user-attachments/assets/4fbbf9e7-5583-48c4-8b6b-9d7a7b2570f5" width="360">
</div>

## Overview:

Understanding customer behavior is crucial for any e-commerce business to optimize its strategies, improve customer satisfaction, and increase sales. This project simulates an e-commerce environment to analyze purchasing patterns and behaviour:
- Generate Synthetic Transaction Data: Create realistic synthetic data for products, customers, and transactions.
- Association Rule Mining: Apply the Apriori algorithm to discover associations/relationship between products in customer baskets.
- Customer Segmentation: Use K-means clustering to segment customers based on their purchasing patterns.
- Visualize Results: Create interactive 3D visualizations for the association rules and customer clusters.

## Key Concepts
1. Synthetic Data Generation:
- Faker Library: Utilized to generate realistic product names and simulate transactions involving different customers.
- Pivoting and Encoding: Transaction data is transformed into a matrix format suitable for analysis.
2. Association Rule Mining (Apriori Algorithm):
- Support, Confidence, and Lift: Key metrics used to evaluate the strength and relevance of the rules.
- Simple Apriori Implementation: A custom implementation of the Apriori algorithm to identify frequent itemsets and generate association rules.
- Visualization: The top association rules are visualized in a 3D scatter plot to explore relationships between support, confidence, and lift.
3. Customer Segmentation (K-means Clustering):
- Standardization: Data is standardized to ensure equal weighting in clustering.
- K-means Clustering: Customers are grouped into clusters based on their purchasing habits, with real-time progress tracking.
- Principal Component Analysis (PCA): Dimensionality reduction technique used to visualize high-dimensional customer data in 3D.
4. Interactive Visualizations:
- Plotly: Used to create 3D scatter plots for both association rules and customer clusters, enabling deeper insights into the data.

## Tools & Libraries:

Data Generation & Manipulation
- numpy, pandas, faker

Machine Learning & Data Analysis:
- scikit-learn, KMeans clustering, StandardScaler, PCA (Principal Component Analysis)

Visualization:
- plotly, plotly.express, plotly.graph_objects
- The visualizations will be saved as HTML files in the project directory.

## Outputs:
- apriori_rules_3d.html: Visualization of the top association rules.
- customer_clusters_3d_final.html: Final visualization of customer clusters.
- Intermediate K-means cluster visualizations: Saved as customer_clusters_3d_step_{i}.html.

## Conclusion:
This project effectively demonstrates the power of data analysis techniques in uncovering valuable insights from synthetic e-commerce data. By utilizing the Apriori algorithm, we identified significant product associations that can inform targeted marketing campaigns and enhance customer experience. The application of K-means clustering, combined with PCA visualization, provided a clear segmentation of customers, enabling a deeper understanding of different customer groups and their purchasing behaviors. The interactive visualizations further enhance the interpretability of these insights, making it easier to translate data-driven findings into actionable business strategies. Overall, this project highlights the potential of machine learning and data mining techniques in driving informed decision-making in e-commerce.
