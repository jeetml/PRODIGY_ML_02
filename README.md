# KMeans Clustering and 3D Visualization

This project utilizes KMeans clustering to uncover hidden patterns in the dataset and visualizes these insights with a stunning 3D plot using Plotly.

## Elbow Method for Optimal Clusters

To determine the optimal number of clusters, the Elbow Method was applied. By plotting the within-cluster sum of squares (WCSS), the "elbow" point in the plot suggested that 5 clusters would be ideal.

## Key Elements of KMeans

- **Clusters (n_clusters)**: Specifies the number of clusters to form and the number of centroids to generate. Based on the Elbow Method, 5 clusters were selected, as the WCSS plot showed a significant drop and then leveled off, indicating the optimal cluster count.
- **Inertia**: Measures the sum of squared distances of samples to their closest cluster center. This metric was instrumental in identifying the optimal number of clusters.
- **fit_predict**: Fits the model and predicts the closest cluster for each sample.

## Results

Leveraging these techniques allowed for meaningful insights to be derived from the data, visualized in a compelling 3D plot.

## Dependencies

- scikit-learn
- Plotly
- pandas
- numpy
