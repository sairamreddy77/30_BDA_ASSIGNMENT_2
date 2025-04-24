# 📁 Spark Model Implementations

This repository contains implementations of three machine learning models using Apache Spark and PySpark MLlib. Each notebook demonstrates a specific ML task: classification, clustering, and recommendation.

# Files Overview
### 1. Classification Model (classification_model.ipynb)
* Implements a classification model using Spark's MLlib.
* Dataset: Titanic dataset (from Kaggle or open source).
* Model: Random Forest.
* Key Steps:
  * Spark session initialization.
  * Load and explore the Titanic dataset.
* Data preprocessing:
  * Dropped unnecessary columns.
  * Converted categorical Sex column to numeric.
  * Used VectorAssembler to prepare feature vectors.
* Train/test split.
* Model training using Logistic Regression.
* Predictions and evaluation using accuracy metric.

### 2. Clustering Model (clustering_model.ipynb)
* Implements a clustering model using Spark's MLlib.
* Dataset: Wholesale customers dataset (UCI Machine Learning Repository).
* Model: KMeans clustering.
* Key Steps:
 * Spark session initialization.
 * Load the customer dataset.
 * Assembled numerical features using VectorAssembler.
 * Trained a KMeans model to cluster customer types.
 * Predicted clusters for each customer.
 * Evaluated using Silhouette Score.
 * Displayed cluster centers.
