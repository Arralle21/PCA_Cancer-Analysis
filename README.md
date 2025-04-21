# PCA_Cancer-Analysis
# Sbumitted : Abdullahi Mohamed Jibril

### Breast Cancer PCA Analysis
________________________________
### Overview
This project analyzes the Wisconsin Breast Cancer dataset using Principal Component Analysis (PCA) to identify essential variables and reduce dimensionality for cancer classification. It also implements logistic regression as a bonus task.
Dataset
The project uses the breast cancer dataset from sklearn.datasets, which contains features computed from digitized images of fine needle aspirates of breast masses.
Implementation

Data preprocessing and standardization
PCA implementation to identify important variables
Dimensionality reduction to 2 principal components
Visualization of explained variance and PCA projection
Logistic regression classification using reduced features

### Files

pca_cancer_analysis.ipynb: Jupyter notebook with complete analysis
pca_cancer_analysis.py: Python script version of the analysis
Output visualizations:

Explained variance chart
PCA projection plot
Feature contribution heatmap
Decision boundary visualization



### Requirements

Python 3.6+
Libraries: numpy, pandas, matplotlib, scikit-learn, seaborn

### How to Run

Clone the repository
Run the notebook in Google Colab or Jupyter
OR
Execute the Python script: python pca_cancer_analysis.py

### Results
The analysis shows that PCA effectively reduces the high-dimensional cancer dataset to just 2 components while maintaining significant variance. The logistic regression model using these components demonstrates good predictive performance.

________________________________________________________________________________________________________________________________________________________________________________________________________________
