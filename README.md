# Customer Clustering Project

This project focuses on segmenting customers into homogeneous groups using clustering techniques. The main goal is to analyze customer behavior based on features such as Gender, Age, Annual Income, and Spending Score, enabling businesses to design targeted marketing strategies.

## Key Steps:

1. **Data Loading and Exploration**  
   - Dataset includes CustomerID, Gender, Age, Annual Income (k$), and Spending Score (1-100).  
   - Checked for missing or invalid data.

2. **Data Preprocessing**  
   - Converted categorical data (Gender) to numeric.  
   - Dropped unnecessary columns (CustomerID).  
   - Normalized features using `StandardScaler` and `MinMaxScaler`.

3. **K-Means Clustering**  
   - Applied K-Means algorithm with 4 clusters.  
   - Assigned each customer to a cluster and analyzed mean values per cluster.  
   - Visualized clusters based on Annual Income and Spending Score.

4. **Hierarchical Clustering**  
   - Built a distance matrix for customers.  
   - Plotted dendrogram to visualize hierarchical relationships.  
   - Applied Agglomerative Clustering for comparison with K-Means.

5. **Visualization**  
   - Scatter plots display clusters with color coding.  
   - Customer age represented by point size, enhancing interpretability.

## Outcome
- Identified meaningful customer segments for strategic marketing.
- Provided insights into customer spending patterns and demographics.
