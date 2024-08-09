# Customer Analysis and Sales Forecasting

## Description

This project focuses on customer analysis and sales forecasting using machine learning techniques. The goal is to segment customers into different clusters and predict future sales for an online store. Clustering methods, dimensionality reduction, and exploratory data analysis are used to extract useful insights and make informed decisions.

## Contents

1. **Exploratory Data Analysis (EDA)**
2. **Customer Segmentation**
3. **Cluster Analysis**
4. **Sales Forecasting**
5. **Result Visualization**

## Requirements

- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `xgboost`, `fbprophet`

### Exploratory Data Analysis (EDA)

Exploratory data analysis includes data cleaning, visualization, and generation of descriptive statistics.

### Customer Segmentation

Customer segmentation is performed using clustering techniques such as K-means and DBSCAN to identify patterns in customer behavior.

### Cluster Analysis

The results of the segmentation are evaluated to determine the value and behavior of each cluster. This includes visualizing the clusters and evaluating them using metrics like the silhouette score.

### Sales Forecasting

Predictive models are used to forecast future sales. Techniques such as ARIMA and Prophet are employed to make these predictions.

### Result Visualization

Results are visualized using graphs and interactive dashboards for better interpretation and communication of findings.

## Results

### Customer Summary

- **Cluster 0: Low-Value Customers**
  - Cluster Size: 172,423 customers (45% of total)
  - Average products per transaction: 2
  - Average cost per unit: $1.77
  - Contribution to Total Sales: $606,126.43 (18% of total)

- **Cluster 1: High-Value Customers**
  - Cluster Size: 110,609 customers (29% of total)
  - Average products per transaction: 9.70
  - Average cost per unit: $1.65
  - Contribution to Total Sales: $1,686,770.31 (50% of total)

- **Cluster 2: High-Value Customers with Lower Frequency**
  - Cluster Size: 98,430 customers (26% of total)
  - Average products per transaction: 3
  - Average cost per unit: $5.23
  - Contribution to Total Sales: $1,080,424.72 (32% of total)

## Contributions

Contributions are welcome. Please follow these steps to contribute:

1. Fork the repository.
2. Create a branch for your changes (`git checkout -b my-branch`).
3. Make your changes and commit (`git commit -am 'Add new feature'`).
4. Push the branch (`git push origin my-branch`).
5. Create a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.