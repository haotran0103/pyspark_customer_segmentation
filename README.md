
# Customer Segmentation using PySpark

## Project Overview
This project focuses on performing customer segmentation using **PySpark** to handle and process large datasets efficiently. By applying **KMeans clustering**, we aim to group customers based on their purchasing behaviors and characteristics, providing valuable insights for targeted marketing strategies.

## Key Objectives
- Preprocess and clean large-scale customer data using PySpark.
- Apply KMeans clustering to segment customers into distinct groups.
- Evaluate the clustering model using the **Silhouette Score** to ensure meaningful segmentation.

## Technologies Used
- **PySpark**: Distributed data processing
- **KMeans**: Clustering algorithm for unsupervised learning
- **VectorAssembler & StringIndexer**: Feature engineering for PySpark models
- **Silhouette Score**: Model evaluation

## Steps
1. **Data Preprocessing**: 
   - Data was cleaned, and categorical features were encoded using **StringIndexer**.
   - Features were assembled into a single vector using **VectorAssembler**.

2. **Model Training**:
   - KMeans clustering algorithm was applied to create customer segments.
   - Multiple cluster sizes were tested to find the optimal number of segments.

3. **Evaluation**:
   - The clustering model was evaluated using the **Silhouette Score** to assess how well the data points fit into the clusters.

4. **Insights**:
   - The model successfully segmented customers into meaningful groups, helping businesses tailor their marketing efforts based on customer behavior.
