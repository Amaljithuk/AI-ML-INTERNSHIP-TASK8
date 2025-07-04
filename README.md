Mall Customer Segmentation with K-Means Clustering
Task Overview
This repository contains the solution for Task 8 of the Elevate AI & ML Internship. The objective is to implement K-Means clustering on the Mall Customer Segmentation Dataset to identify customer segments based on Age, Annual Income, and Spending Score.
Steps Performed

Data Preprocessing:
Loaded Mall_Customers.csv, dropped CustomerID, and renamed columns.
Encoded Gender (Male=1, Female=0) and standardized Age, AnnualIncome, and SpendingScore.
Saved cleaned dataset as Mall_Customers_Cleaned.csv.


Exploratory Data Analysis:
Generated summary statistics and visualized feature distributions.
Created a pairplot for Gender, Age, AnnualIncome, and SpendingScore.


K-Means Clustering:
Applied K-Means clustering, using the Elbow Method to select optimal K (K=5).
Evaluated clustering with the Silhouette Score.


Cluster Visualization:
Used PCA to project data into 2D for visualization of clusters.



Files

mall_customer_clustering.ipynb: Jupyter Notebook with preprocessing, EDA, and K-Means implementation.
Mall_Customers.csv: Original Mall Customer Segmentation Dataset.
Mall_Customers_Cleaned.csv: Preprocessed dataset.
pairplot.png: Pairplot of features by Gender.
distributions.png: Histograms of Annual Income and Spending Score.
elbow_curve.png: Elbow Method plot for optimal K.
cluster_visualization.png: 2D PCA cluster visualization.
interview_questions.md: Answers to provided interview questions.
README.md: This documentation file.

Tools Used

Python 3
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
scikit-learn

How to Run

Clone this repository:git clone https://github.com/Amaljithuk/AI-ML-INTERNSHIP-TASK8.git


Install required dependencies:pip install pandas numpy matplotlib seaborn scikit-learn jupyter


Launch Jupyter Notebook:jupyter notebook


Open mall_customer_clustering.ipynb and run all cells to:
Generate the cleaned dataset (Mall_Customers_Cleaned.csv).
Save visualizations (pairplot.png, distributions.png, elbow_curve.png, cluster_visualization.png).
Display clustering metrics (Silhouette Score).



Observations

EDA: Annual Income and Spending Score show varied distributions, suggesting potential customer segments. Gender was not used for clustering but visualized for context.
Clustering: K=5 was selected based on the Elbow Method, with a reasonable Silhouette Score indicating cohesive clusters.
PCA Visualization: 2D projection shows distinct clusters, though some overlap exists, reflecting data complexity.
Normalization: Essential for K-Means to ensure equal feature contributions in distance calculations.

Submission
This repository is submitted for Task 8 of the Elevate AI & ML Internship, completed on July 4, 2025, within the 10:00 AM to 10:00 PM submission window.
