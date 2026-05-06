# Classification-and-Clustering-Analysis
This project analyzes a dataset with 20 features and a categorical target. It covers data cleaning, EDA, and modeling using Logistic Regression, Random Forest, and SVM. PCA and K-Means were applied for unsupervised learning. The pipeline highlights preprocessing and evaluation.

It involved analyzing a 3,000-observation dataset with 20 continuous features and a multi-class label using both supervised and unsupervised learning.

Multinomial Logistic Regression achieved 85% accuracy, effectively handling multi-class classification. However, it showed some class-level misclassification (notably between classes A and D), revealing areas for deeper feature engineering.

Principal Component Analysis (PCA) was used for dimensionality reduction and visualizing feature variance. It highlighted meaningful clusters and helped reduce feature redundancy.

K-Means Clustering (3 clusters) was applied post-PCA, successfully uncovering natural groupings in the data, validated visually with PCA plots.

Data preprocessing included imputation, outlier removal (IQR), and correlation analysis to reduce multicollinearity.

Additional models like Random Forest and SVM were tested, with Random Forest outperforming others (89.7% accuracy) and showing high model stability via bootstrap sampling.

The project showcases a full machine learning pipeline—data cleaning, EDA, modeling, dimensionality reduction, and clustering—highlighting how different algorithms reveal structure and improve prediction in complex datasets.
