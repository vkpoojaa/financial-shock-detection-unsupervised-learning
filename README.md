# Detecting Financial Shocks & Segmenting Behavioral Risk Profiles using Unsupervised Learning

## Overview

This project implements an unsupervised learning framework to detect financial shocks and segment transaction behavior into risk profiles. It combines anomaly detection, clustering, and a composite Financial Stress Index (FSI) for risk assessment.

## Files Included

* `Financial_Shock_Detection.ipynb` — Complete implementation (EDA, feature engineering, modeling, evaluation)
* `paysim_sample.csv` — Dataset used for analysis
* `Report.pdf` — Detailed project report (methodology, results, discussion)

## Methodology (Summary)

* Feature Engineering: Created transaction-level behavioral features (balance changes, ratios, anomaly indicators)
* Anomaly Detection:

  * Isolation Forest
  * DBSCAN
* Clustering:

  * K-Means (final model, K = 4)
  * Evaluated using Silhouette Score and Davies-Bouldin Index
* Dimensionality Reduction:

  * PCA and t-SNE for visualization
* Risk Scoring:

  * Financial Stress Index (FSI) for transaction-level risk

## Key Results

* High-risk cluster shows near-total anomaly concentration
* FSI strongly correlates with key risk indicators
* Isolation Forest and DBSCAN capture complementary anomalies
* Clustering effectively segments behavioral patterns

## How to Run

1. Open the notebook:
   Financial_Shock_Detection.ipynb

2. Ensure dataset is in the same directory:
   paysim_sample.csv

3. Run all cells sequentially


## Author

Poojaa V K
