# Enhancing-Forensic-Analysis-Machine-Learning-for-Glass-Type-Classification

## Project Overview

This project, "Enhancing Forensic Analysis: Machine Learning for Glass Type Classification," aims to classify different types of glass based on their chemical properties using machine learning models. The Glass Identification dataset from the UCI Machine Learning Repository is used for this purpose.

## Dataset

The dataset contains 214 samples of glass with 9 chemical properties each, classified into 7 types of glass. The objective is to develop and compare K-Nearest Neighbors (KNN) and Decision Tree models to accurately classify these glass types.

## Methodology

1. **Data Pre-Processing**: Cleaning the dataset, handling outliers, and ensuring data completeness.
2. **Data Exploration**: Analyzing the distribution and correlation of chemical properties.
3. **Model Building**:
   - **K-Nearest Neighbors (KNN)**: Optimized with k=1, using inverse distance weighting and Manhattan distance.
   - **Decision Tree**: Tuned with the 'gini' criterion and a maximum depth of 6.

## Results

- **KNN Model**: Achieved an accuracy of 74%.
- **Decision Tree Model**: Achieved an accuracy of 70%.

## Conclusion

The KNN model outperformed the Decision Tree model, making it a more reliable choice for glass type classification in forensic analysis.

## Files in the Repository

- Jupyter notebook containing the code and analysis.



