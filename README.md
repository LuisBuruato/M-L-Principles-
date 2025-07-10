# Clustering and Segmentation Analysis of Vehicles and Customers

## Project Summary

This project focuses on clustering analysis using data from vehicles and customers to identify groups with similar characteristics. Techniques such as normalization, distance matrix calculation, hierarchical and agglomerative clustering were applied, along with visualizations to interpret the results.

---

## Customer Segmentation (K-Means)

- Segmentation into 3 clusters based on Age, Education, and Income.
- 2D and 3D visualizations help to understand grouping behavior.

### 2D Visualization of Customer Segmentation

![Customers by Age and Income](https://raw.githubusercontent.com/LuisBuruato/M-L-Principles-/main/images/clientes_edad_ingreso.png)

### 3D Visualization of Customer Segmentation

![3D Segmentation](https://raw.githubusercontent.com/LuisBuruato/M-L-Principles-/main/images/3D_customer_segmentation.png)

---

## Vehicle Clustering Analysis

- Cleaned and normalized relevant variables.
- Computed Euclidean distance matrix.
- Applied hierarchical and agglomerative clustering to group vehicles.
- Cluster assignments were added to the dataset.

### Hierarchical Clustering Dendrogram

![Dendrogram](https://raw.githubusercontent.com/LuisBuruato/M-L-Principles-/main/images/dendrogram.png)

### Scatter Plot of Vehicle Clusters

**X-axis:** Horsepower (`horsepow`)  
**Y-axis:** Fuel Efficiency (`mpg`)  
**Size:** Price (`price`)  
**Color:** Cluster  
Each point is labeled with the vehicle model.

![Vehicle Clusters](https://raw.githubusercontent.com/LuisBuruato/M-L-Principles-/main/images/clusters_scatter.png)

---

## Conclusion

The analysis enabled the identification of homogeneous groups among customers and vehicles, providing valuable insights for segmentation strategies and personalized marketing.

---

## How to Run

Run the notebook `machine_learning.ipynb` with the necessary libraries installed to reproduce the full analysis and generate the graphs.



