# Classification of Digits using LDA, QDA, KNN with PCA

## Overview

This project aims to classify handwritten digits from the **Digits dataset** using three classification models: **Linear Discriminant Analysis (LDA)**, **Quadratic Discriminant Analysis (QDA)**, and **K-Nearest Neighbors (KNN)**, along with dimensionality reduction using **Principal Component Analysis (PCA)**.

## Dataset

The dataset consists of 1,797 grayscale images of handwritten digits (0-9), each represented as an 8x8 pixel grid, resulting in 64 features per sample.

## Objectives

- **Classify digits** using LDA, QDA, and KNN.
- **Apply PCA** to reduce dimensionality and improve model performance.
- **Compare** the performance of each model with and without dimensionality reduction.

## Methods

1. **Data Loading and Preprocessing**:
   - Load the digits dataset.
   - Convert images to 1D arrays.
   - Split data into training, validation, and testing sets.
   - Standardize features.

2. **Model Training and Evaluation**:
   - **KNN**: Tune and evaluate different values of \( k \).
   - **LDA**: Tune and evaluate different values of components.
   - **QDA**: Train and evaluate the model.

3. **Dimensionality Reduction with PCA**:
   - Apply PCA to reduce feature dimensions.
   - Evaluate the impact on model performance with KNN.

4. **Comparison of Methods**:
   - Compare accuracy and error rates of KNN with PCA and LDA dimensionality reduction.

## Results

- **KNN**: Optimal \( k \) values were identified, and accuracy and error rates were evaluated.
- **LDA**: Performance improved with appropriate number of components.
- **QDA**: Evaluated for overall accuracy and error rates.
- **PCA**: Reduced dimensionality to improve efficiency, with results compared for different \( k \) values and dimensionality reduction methods.

## Conclusion

- Increasing the number of PCA components generally improves accuracy and reduces error rates.
- LDA with dimensionality reduction tends to yield better performance.
- Optimal number of components for dimensionality reduction is around 8-9.

## Dependencies

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Usage

Clone the repository and run the notebook to explore classification models and dimensionality reduction techniques. Ensure all dependencies are installed.
