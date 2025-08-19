# Clustering and Segmentation Analysis of Vehicles and Customers

## Project Summary

This project applies clustering techniques to analyze customers and vehicles, aiming to uncover natural groupings and meaningful insights. Methods such as normalization, distance matrix calculation, hierarchical clustering, and K-Means were applied, accompanied by visualizations for interpretation.  

---

## Customer Segmentation (K-Means)

The customer dataset was segmented into **3 groups based on Age, Education, and Income**.  
This segmentation allows companies to design **personalized marketing strategies** according to the demographic and financial characteristics of their clients.

### 2D Visualization of Customer Segmentation

![Customers by Age and Income](https://raw.githubusercontent.com/LuisBuruato/M-L-Principles-/main/images/clientes_edad_ingreso.png)

**Explanation:**  
This 2D scatter plot shows the segmentation of customers using **Age (X-axis)** and **Income (Y-axis)**. Each color represents a cluster obtained with K-Means.  

- One cluster groups **younger customers with lower income**, likely students or entry-level professionals.  
- Another cluster groups **middle-aged customers with moderate income**.  
- The last cluster identifies **older customers with higher income**, representing more established professionals.  

✅ Key Takeaways 
The segmentation reveals a clear differentiation in customer profiles, which can be used to design **targeted campaigns** such as student discounts, family-oriented promotions, or premium services.

---

### 3D Visualization of Customer Segmentation

![3D Segmentation](https://raw.githubusercontent.com/LuisBuruato/M-L-Principles-/main/images/3D_customer_segmentation.png)

**Explanation:**  
The 3D visualization adds **Education level** as the third dimension, providing a more complete view of customer clusters.  

- The plot shows that higher education levels correlate with higher income and age.  
- Customers with lower education levels tend to fall into lower-income clusters.  

✅ Key Takeaways 
The inclusion of education strengthens the segmentation strategy, as it highlights how **education and income jointly define customer groups**. This insight can guide strategies like offering **financial products** for professionals or **training-related offers** for younger groups.

---

## Vehicle Clustering Analysis

The vehicle dataset was analyzed to uncover patterns in technical and economic attributes.  
After normalization, a **Euclidean distance matrix** was computed, followed by hierarchical and agglomerative clustering.  

### Hierarchical Clustering Dendrogram

![Dendrogram](https://raw.githubusercontent.com/LuisBuruato/M-L-Principles-/main/images/dendrogram.png)

**Explanation:**  
The dendrogram illustrates how vehicles are progressively grouped based on their similarity. The shorter the vertical linkage, the more similar the vehicles.  

- Vehicles with **similar horsepower and efficiency** were grouped early.  
- Distinct clusters formed between **fuel-efficient compact cars** and **powerful, high-priced vehicles**.  

✅ Key Takeaways  
The dendrogram helps decide the **optimal number of clusters** and reveals natural hierarchies in the data, such as the distinction between **economical vs. luxury vehicles**.

---

### Scatter Plot of Vehicle Clusters

**X-axis:** Horsepower (`horsepow`)  
**Y-axis:** Fuel Efficiency (`mpg`)  
**Size:** Price (`price`)  
**Color:** Cluster  
Each point is labeled with the vehicle model.  

![Vehicle Clusters](https://raw.githubusercontent.com/LuisBuruato/M-L-Principles-/main/images/clusters_scatter.png)

**Explanation:**  
This scatter plot visually displays vehicle clusters:  

- **Cluster 1:** Vehicles with **low horsepower and high fuel efficiency**, typically compact and budget-friendly.  
- **Cluster 2:** Vehicles with **moderate horsepower and balanced fuel efficiency**, representing mid-range family cars.  
- **Cluster 3:** Vehicles with **high horsepower, low fuel efficiency, and high prices**, representing luxury or sports models.  

✅ Key Takeaways  
This segmentation allows manufacturers and dealerships to **differentiate product strategies**:  
- Compact cars can be marketed as **eco-friendly and affordable**.  
- Mid-range vehicles appeal to **families and everyday drivers**.  
- High-end cars target **luxury customers seeking performance**.

---

## Final Conclusion

The clustering analysis of customers and vehicles provides **actionable insights**:  

- For customers, segmentation based on **age, income, and education** supports **personalized marketing and product recommendations**.  
- For vehicles, clustering highlights **market positioning** opportunities, enabling manufacturers and dealers to adapt pricing, advertising, and inventory strategies.  

This combined approach demonstrates how clustering techniques can uncover **hidden patterns** and generate **data-driven strategies** for both marketing and product management.  

---

## How to Run

Run the notebook `machine_learning.ipynb` with the necessary libraries installed to reproduce the full analysis and generate the graphs.


