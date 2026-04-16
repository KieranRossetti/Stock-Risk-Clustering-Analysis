# Stock Risk Clustering Analysis

## Overview
This project analyses S&P 500 stocks by clustering them based on risk and return characteristics. The aim is to identify distinct groups of stocks that can support portfolio diversification and investment decision making.

## Dataset
- Over 500 S&P 500 stocks
- Historical data from 2022 to 2025
- Data sourced using yfinance

## Methods
- Data cleaning and preprocessing
- Feature engineering:
  - Average daily return
  - Beta (market sensitivity)
  - Annual volatility
- Clustering techniques:
  - K-means clustering
  - Hierarchical (agglomerative) clustering

## Results
- Identified 2 main clusters:
  - Low risk stocks (defensive)
  - High risk stocks (aggressive)
- Both clustering methods produced consistent segmentation

## Key Visualisations

### Beta vs Volatility
![Beta vs Volatility](Graphs/Beta%20vs%20Volatility.png)

### Risk Return Trade Off
![Risk Return](Graphs/Average%20Return%20vs%20Volatility.png)

### Dendrogram
![Dendrogram](Graphs/Dendrogram%20for%20Agglomerative%20Clustering.png)

### K means Cluster Profiles
![KMeans](Graphs/K-Means%20Cluster%20Profiles.png)

## Business Insight
- Supports portfolio diversification strategies
- Highlights the trade off between risk and return
- Helps investors align portfolios with different risk tolerances

## Tools Used
- Python
- pandas, NumPy
- scikit-learn
- yfinance
- matplotlib

**The full implementation can be found in the notebook included in this repository.**

## Author
Kieran Rossetti
Data Analytics & Business Intelligence Portfolio Project
