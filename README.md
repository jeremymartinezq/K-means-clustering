# K-Means Clustering Analysis

## Overview
This project implements K-Means clustering on two datasets: "Wholesale customers data" and "Clustering.csv." The goal is to segment data points into meaningful clusters for better analysis and decision-making.

## Features
- **Data Preprocessing**: Cleaning and standardizing data.
- **Elbow Method**: Determining the optimal number of clusters.
- **K-Means Clustering**: Applying K-Means to segment the data.
- **Visualization**: Graphical representation of clusters and cluster centers.
- **Insights & Discussion**: Interpreting the results for decision-making.

## Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Implementation Steps
1. **Load Datasets**: Reads the two CSV files into Pandas DataFrames.
2. **Preprocessing**:
   - Standardize numerical features.
   - Handle missing values.
3. **Elbow Method**:
   - Computes Within-Cluster Sum of Squares (WCSS) for different cluster sizes.
   - Helps determine the optimal number of clusters.
4. **K-Means Clustering**:
   - Applies K-Means with optimal clusters.
   - Assigns cluster labels to data points.
5. **Visualization**:
   - Uses scatter plots to display clusters.
   - Highlights cluster centers.
6. **Discussion**:
   - Wholesale Customers Data: Useful for marketing and inventory segmentation.
   - Clustering Data: Identifies patterns in income and loan distribution for financial insights.

## Usage
Run the Jupyter notebook or execute the script in Python:
```python
python kmeans_clustering.py
```

## Results
The clustering analysis helps identify patterns and segment data for strategic decision-making in marketing, finance, and business analytics.
- <img width="520" alt="image" src="https://github.com/user-attachments/assets/5faa3204-6ca2-4999-9c40-a22f2d662120" />
- <img width="456" alt="image" src="https://github.com/user-attachments/assets/0301ae81-93cd-4a59-9fd7-c0eb6270c715" />
- <img width="462" alt="image" src="https://github.com/user-attachments/assets/9ceb388f-3d06-421c-87ee-fd9fa3ec609e" />


## Author
Developed by Jeremy Martinez-Quinones.

## License
This project is licensed under the MIT License - see LICENSE file for details.


