# Customer Analysis and Sales Forecasting

## Description

This project focuses on customer analysis and sales forecasting using machine learning techniques. The goal is to segment customers into different clusters and predict future sales for an online store. Clustering methods, dimensionality reduction, and exploratory data analysis are used to extract useful insights and make informed decisions.

## Contents

1. **Exploratory Data Analysis (EDA)**
2. **Customer Segmentation**
3. **Cluster Analysis**
4. **Sales Forecasting**
5. **Segmentation Results**
6. **Forecast Results**

## Requirements

- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `arima`.

### Exploratory Data Analysis (EDA)

Exploratory data analysis includes data cleaning, visualization, and generation of descriptive statistics.

### Customer Segmentation

Customer segmentation is performed using clustering techniques such as K-means and DBSCAN to identify patterns in customer behavior.

### Cluster Analysis

The results of the segmentation are evaluated to determine the value and behavior of each cluster. This includes visualizing the clusters and evaluating them using metrics like the silhouette score.

### Sales Forecasting

Arima predictive model is used to forecast future sales.

## Segmentation Results

### Customer Summary

- **Cluster 0: Low-Value Customers**
  - Cluster Size: 172,423 customers (45% of total)
  - Average products per transaction: 2
  - Average cost per unit: $1.77
  - Contribution to Total Sales: $606,126.43 (18% of total)

- **Cluster 1: High-Value Customers**
  - Cluster Size: 110,609 customers (29% of total)
  - Average products per transaction: 10
  - Average cost per unit: $1.65
  - Contribution to Total Sales: $1,686,770.31 (50% of total)

- **Cluster 2: High-Value Customers with Lower Frequency**
  - Cluster Size: 98,430 customers (26% of total)
  - Average products per transaction: 3
  - Average cost per unit: $5.23
  - Contribution to Total Sales: $1,080,424.72 (32% of total)

## Forecast Results

| Date       | y     | yhat_lower | yhat_upper |
|------------|----------|------------|------------|
| 2011-12-31 | 149,265.86 | 48,462.27   | 250,069.44 |
| 2012-01-31 | 103,328.18 | -12,089.48  | 218,745.85 |
| 2012-02-29 | 130,740.51 | -11,318.00  | 272,799.01 |
| 2012-03-31 | 114,382.79 | -42,658.67  | 271,424.25 |
| 2012-04-30 | 124,143.91 | -50,503.62  | 298,791.44 |
| 2012-05-31 | 118,319.17 | -70,120.04  | 306,758.38 |
| 2012-06-30 | 121,794.96 | -80,703.92  | 324,293.83 |
| 2012-07-31 | 119,720.86 | -95,239.11  | 334,680.82 |
| 2012-08-31 | 120,958.53 | -106,163.72 | 348,080.78 |
| 2012-09-30 | 120,219.97 | -118,226.31 | 358,666.26 |
| 2012-10-31 | 120,660.69 | -128,720.64 | 370,042.02 |
| 2012-11-30 | 120,397.70 | -139,387.29 | 380,182.69 |

## Contributions

Contributions are welcome. Please follow these steps to contribute:

1. Fork the repository.
2. Create a branch for your changes (`git checkout -b my-branch`).
3. Make your changes and commit (`git commit -am 'Add new feature'`).
4. Push the branch (`git push origin my-branch`).
5. Create a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
