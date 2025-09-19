# Task 2: Customer Segmentation

## Overview
This project implements customer segmentation using unsupervised learning techniques, specifically K-Means and DBSCAN clustering algorithms.

## Dataset
- **Source**: Mall Customer Segmentation Data from Kaggle
- **Features**: Customer ID, Gender, Age, Annual Income, Spending Score
- **Target**: Segment customers based on Income and Spending Score

## Setup Instructions

1. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Download Dataset**:
   - Go to [Kaggle Mall Customer Dataset](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
   - Download `Mall_Customers.csv`
   - Place it in the `Task 2` folder

3. **Run the Analysis**:
   ```bash
   jupyter notebook customer_segmentation.ipynb
   ```

## Project Structure
```
Task 2/
├── customer_segmentation.ipynb    # Main analysis notebook
├── requirements.txt               # Python dependencies
├── README.md                     # This file
└── Mall_Customers.csv            # Dataset (download separately)
```

## Features Implemented

### Core Requirements ✅
- [x] Data loading and exploration
- [x] Feature scaling using StandardScaler
- [x] Visual exploration of data distribution
- [x] K-Means clustering implementation
- [x] Optimal cluster number determination (Elbow Method + Silhouette Score)
- [x] 2D cluster visualization

### Bonus Features ✅
- [x] DBSCAN clustering algorithm implementation
- [x] Average spending analysis per cluster
- [x] Comprehensive cluster comparison
- [x] Business insights and recommendations

## Key Results
- Identifies 5 distinct customer segments
- Provides actionable business insights for targeted marketing
- Compares multiple clustering approaches
- Handles outlier detection through DBSCAN

## Technologies Used
- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **Matplotlib/Seaborn**: Data visualization
- **Scikit-learn**: Machine learning algorithms
- **Jupyter**: Interactive development environment

## Business Value
The segmentation helps businesses:
1. Target marketing campaigns effectively
2. Identify high-value customer groups
3. Develop personalized customer strategies
4. Optimize resource allocation
5. Detect unusual customer behavior patterns