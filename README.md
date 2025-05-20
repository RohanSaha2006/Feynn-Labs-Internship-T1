# Customer Segmentation Analysis

This repository contains code for customer segmentation analysis using machine learning techniques. The analysis is performed on McDonald's customer survey data to identify distinct customer segments based on their preferences, behaviors, and demographics.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Requirements](#requirements)
- [Code Structure](#code-structure)
- [Key Visualizations](#key-visualizations)
- [Results and Insights](#results-and-insights)
- [How to Use](#how-to-use)
- [License](#license)

## Overview

This project demonstrates how small businesses can leverage machine learning for customer segmentation to better understand their customer base and develop targeted marketing strategies. The analysis explores patterns in customer preferences, demographics, and behaviors to identify natural groupings that can inform business decisions.

## Dataset

The analysis uses the McDonald's survey dataset (`mcdonalds.csv`) which contains:
- **11 attribute columns**: Customer perceptions of McDonald's (yummy, convenient, spicy, fattening, greasy, fast, cheap, tasty, expensive, healthy, disgusting) with Yes/No values
- **Demographic information**: Age and Gender
- **Behavioral data**: Visit frequency
- **Sentiment data**: Like score ranging from -5 (hate) to +5 (love)

## Methodology

The project employs two clustering approaches:

1. **K-Means Clustering**:
   - Principal Component Analysis (PCA) for dimensionality reduction
   - Elbow method to determine optimal number of clusters
   - Visualization of clusters in 2D space

2. **Hierarchical Clustering**:
   - Ward's method for linkage
   - Dendrogram visualization to determine optimal number of clusters
   - Feature importance analysis per cluster

Both methods are compared to provide robust segmentation insights.

## Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
scipy
bioinfokit
```

## Code Structure

### Part 1: Data Exploration and K-Means Clustering
- Data loading and inspection
- Exploratory data analysis with visualizations
- Label encoding of categorical variables
- Principal Component Analysis (PCA)
- K-Means clustering implementation
- Elbow method for optimal cluster determination
- Visualization of K-Means clusters

### Part 2: Advanced Analysis and Hierarchical Clustering
- Segment analysis by merging cluster information
- Target segment identification
- Hierarchical clustering implementation
- Dendrogram visualization
- Cluster characterization through feature analysis
- Comparison of clustering methods

## Key Visualizations

The code generates several key visualizations:

1. **Exploratory visualizations**:
   - Gender distribution
   - Age distribution
   - Correlation heatmap
   - Customer attributes histograms

2. **Clustering visualizations**:
   - Elbow plot for K-Means
   - Cluster scatter plots
   - Dendrogram for hierarchical clustering
   - Feature importance heatmap by cluster
   - Segment evaluation plot (VisitFrequency vs. Like)

## Results and Insights

The analysis identifies four distinct customer segments:

1. **Segment 0**: [Description based on actual results]
2. **Segment 1**: [Description based on actual results]
3. **Segment 2**: [Description based on actual results]
4. **Segment 3**: [Description based on actual results]

Key findings include:
- Which segments have the highest visit frequency
- Which segments have the highest like scores
- Key attributes that define each segment
- Demographic differences between segments

## How to Use

1. Clone this repository:
```
git clone https://github.com/yourusername/customer-segmentation.git
```

2. Install required dependencies:
```
pip install -r requirements.txt
```

3. Place the `mcdonalds.csv` file in the same directory as the code

4. Run the notebook or Python scripts:
```
jupyter notebook customer_segmentation.ipynb
```
or
```
python customer_segmentation.py
```

5. Review the generated visualizations and segment insights

## License

[Specify your license information here]

---

This project demonstrates how small and medium-sized businesses can implement advanced customer segmentation techniques to better understand their customers and create targeted marketing strategies.
