PCA and t-SNE for Dimensionality Reduction

Overview

This project demonstrates Principal Component Analysis (PCA) and t-Distributed Stochastic Neighbor Embedding (t-SNE) for dimensionality reduction and visualization of high-dimensional data. The dataset used contains red and white wine quality metrics.

Dataset

The dataset consists of red and white wine quality data.

Features include various chemical properties of wine, such as acidity, alcohol content, and pH.

The target variable is wine quality.

Tasks Covered

1. Data Preprocessing

The dataset is loaded and combined (red and white wine).

Features are standardized using StandardScaler to ensure proper scaling.

2. Dimensionality Reduction & Visualization

PCA:

Applied to reduce the dataset to 2 or 3 principal components.

Explained variance is computed to analyze the trade-off between dimensionality reduction and information loss.

2D scatter plot is created to visualize the transformed data.

An explained variance plot is included to show how much variance each principal component captures.

t-SNE:

Applied to obtain a 2D representation.

A scatter plot is generated to visualize clusters.

3. PCA vs. t-SNE Comparison

Discusses the differences in how PCA and t-SNE handle high-dimensional data.

Covers strengths, weaknesses, and trade-offs between the two methods.

Installation

To run the project, install the required dependencies using:

pip install numpy pandas matplotlib seaborn scikit-learn

Usage

Run the following script to execute PCA and t-SNE on the dataset:

python main.py

Output

Scatter plots for PCA and t-SNE visualizations.

Explained variance ratios for PCA.

Comparison discussion on PCA vs. t-SNE.




