# Customer Segmentation Using Data Mining Techniques

## Overview

This project applies data mining techniques to identify meaningful customer segments using the Mall Customers Dataset from Kaggle. 

The objective is to compare K-Means Clustering and Hierarchical Clustering to determine how effectively each algorithm groups customers based on their characteristics.

The project was completed as part of the DSC4740 - Data Mining course. 

---

## Objectives

- Perform customer segmentation using custering techniques.
- Compare K-Means and Hierarchical Clustering.
- Evaluate clustering quality using the Elbow Method and Silhouette Score.
- Analyze customer segments based on demographic and spending behavior.
- Improve interpretability of results through simple Explainable AI (XAI) techniques. 

---

## Dataset

Mall Customers Dataset
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

---


## Repository Structure

```
Customer-Segmentation/
|
|- preprocessing.ipynb
|- kmeans_exp1.ipynb
|- kmeans_exp2.ipynb
|- hierarchical_exp1.ipynb
|- hierarchical_exp2.ipynb
|- kmeans_exp1_result.csv
|- kmeans_exp2_result.csv
|- hierarchical_exp1_result.csv
|- hierarchical_exp2_result.csv
|- Mall_Customers.csv
|- README.md
|- cluster_explainability.ipynb
```

---

## Technologies Used

- Python 3.11
- Jupyter Notebook (VS Code)
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- SciPy

---

## How to Run

### Installation
Clone the repository: 

```bash
https://github.com/krishnacharitha02/Customer-Segmentation.git
```
Go to project folder:

```bash
cd Customer-Segmentation
```
Install the necessary libraries: 

```bash
pip install pandas numpy matplotlib scikit-learn scipy jupyter
```

### Running the Project
1. Open the project folder
2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Run the notebooks in the following order: 
preprocessing.ipynb, kmeans_exp1.ipynb, hierarchical_exp1.ipynb, kmeans_exp2.ipynb, hierarchical_exp2.ipynb

---

## Evaluation Metrics

The clustering algorithms were evaluated using Elbow Method, Silhouette score, cluster analysis, scatter plot visualization, and dendrogram visualization. 

---

## Results

Both clustering algorithms had successfully identified meaningful customer segments based on age, income, and spending score. 

The project compares the clustering quality of both methods and analyzes how the addition of Age affects customer segmentation. 

---

## Authors

- FNU Nimarta
- Krishna Charitha Kidambi
