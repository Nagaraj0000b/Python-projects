# ML Lab Assignment 13: Mall Customer Segmentation

## Overview
This assignment focuses on customer segmentation using K-Means clustering algorithm. The goal is to analyze mall customer data and identify distinct customer segments based on their annual income and spending behavior.

## Files
- `Mall_Customers.csv` - Dataset containing 200 mall customer records with the following features:
  - CustomerID: Unique identifier for each customer
  - Gender: Customer's gender (Male/Female)
  - Age: Customer's age
  - Annual Income (k$): Annual income in thousands of dollars
  - Spending Score (1-100): Score assigned by mall based on customer behavior

- `ML_Lab_Assignment_13.ipynb` - Jupyter notebook with complete implementation including:
  - Data loading and exploration
  - Exploratory data analysis with visualizations
  - Correlation analysis
  - Elbow method for determining optimal number of clusters
  - K-Means clustering implementation
  - Cluster visualization and interpretation
  - Business recommendations

## Prerequisites
Install the required Python libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## How to Run
1. Ensure all prerequisites are installed
2. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Navigate to `ML_Lab_Assignment_13.ipynb`
4. Run all cells sequentially (Cell > Run All)

## Expected Output
The notebook will generate:
- Data visualizations (distributions, scatter plots, heatmaps)
- Elbow curve for optimal K selection
- Customer segment visualizations (2D and 3D)
- Cluster analysis and statistics
- Business insights and recommendations
- Segmented customer data saved to `Mall_Customers_Segmented.csv`

## Learning Objectives
- Understand unsupervised learning and clustering algorithms
- Apply K-Means clustering to real-world data
- Determine optimal number of clusters using elbow method
- Interpret and analyze customer segments
- Generate business insights from clustering results
- Visualize multi-dimensional data

## Assignment Tasks
The notebook is organized into 11 main tasks:
1. Import required libraries
2. Load and explore the dataset
3. Perform exploratory data analysis (EDA)
4. Determine optimal number of clusters using elbow method
5. Apply K-Means clustering
6. Visualize the clusters
7. Analyze each cluster
8. Interpret customer segments
9. Create 3D visualizations
10. Provide conclusions and business recommendations
11. Save results

## Customer Segments Identified
Typically, the analysis identifies 5 customer segments:
- **Target Customers**: High income, high spending (priority for marketing)
- **Careful Customers**: High income, low spending (potential for conversion)
- **Careless Customers**: Low income, high spending (need budget options)
- **Sensible Customers**: Low income, low spending (value-seekers)
- **Standard Customers**: Average income and spending

## Notes
- The dataset contains synthetic data representative of typical mall customer demographics
- Results may vary slightly due to random initialization in K-Means
- The `random_state=42` parameter ensures reproducibility
- Feel free to experiment with different features and number of clusters

## Resources
- K-Means Clustering: https://scikit-learn.org/stable/modules/clustering.html#k-means
- Customer Segmentation: https://en.wikipedia.org/wiki/Market_segmentation
- Elbow Method: https://en.wikipedia.org/wiki/Elbow_method_(clustering)
