# Dimensionality Reduction and Classification on Wine Quality Dataset

## Project Overview

This project explores various dimensionality reduction techniques and their impact on classification accuracy across the **Wine Quality Dataset**. It involves preprocessing, feature extraction, dimensionality reduction, and classification using conventional and advanced machine learning methods.

---

## Datasets

### 1. **Wine Quality Dataset**
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality)
- **Description**: 
  - Features include physicochemical properties of wines (e.g., acidity, sugar levels) and a quality score.
  - An additional column indicates wine color (`0` for white, `1` for red).

---

## Objectives

### Wine Quality Dataset
1. **Normalization**:
   - Compare unnormalized data vs. z-score normalization using pair plots.
   - Evaluate the impact of normalization on classification accuracy.

2. **Classification**:
   - Implement **K-Nearest Neighbors (KNN)** with different distance metrics:
     - Uniform weighting
     - Distance-based weighting (Manhattan, Euclidean)
   - Investigate the impact of `k` values (from 1 to 50) on accuracy.

3. **Feature Extraction**:
   - Apply **Principal Component Analysis (PCA)** and **Linear Discriminant Analysis (LDA)**.
   - Evaluate classification accuracy using extracted features.

4. **Analysis**:
   - Compare classification accuracy across normalization, feature extraction, and distance metrics.
   - Analyze the relationship between features and classification results.

---

## Tools and Technologies

- **Programming Language**: Python
- **Libraries**:
  - **scikit-learn**: Dimensionality reduction, classification, and metrics
  - **matplotlib**, **seaborn**: Data visualization
  - **NumPy**, **Pandas**: Data manipulation and analysis

---

## Key Results

- Normalization significantly impacts classification accuracy for KNN on the Wine Quality Dataset.
- PCA and LDA enable dimensionality reduction with minimal loss in classification performance.

---

