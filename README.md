# DATA-MINING-MODELING-AND-ANALYTIC-ASSIGNMENT-2

## Project Overview

This repository contains two machine learning projects implemented using Python and Jupyter Notebooks. The projects apply unsupervised and supervised learning techniques to address customer segmentation and credit card fraud detection.

## Project 1: Wholesale Customer Segmentation

**Notebook:** `Assign_2_part1.ipynb`

### Description
This project applies unsupervised machine learning to segment wholesale customers based on their annual spending patterns across six product categories: Fresh, Milk, Grocery, Frozen, Detergents_Paper and Delicatessen.

The dataset contains 440 wholesale customers, together with information on sales channel and geographical region.

### Objectives
- Explore and prepare the wholesale customer dataset.
- Assess the tendency of the data to form clusters.
- Apply and compare K-Means, Hierarchical Clustering and DBSCAN.
- Evaluate and profile the resulting customer segments.
- Develop business recommendations for the identified customer groups.

### Analytical Methods
- Exploratory Data Analysis (EDA)
- Data preparation and feature scaling
- Cluster tendency assessment
- K-Means clustering
- Hierarchical clustering
- DBSCAN
- Cluster evaluation and profiling

## Project 2: Credit Card Fraud Detection

**Notebook:** `Assignment2_part2.ipynb`

### Description
This project develops and evaluates anomaly detection approaches for prioritising potentially fraudulent credit card transactions for investigation.

The dataset contains 284,807 European credit card transactions recorded over two days in September 2013, including 492 fraudulent transactions (approximately 0.172%).

### Objectives
- Explore and prepare the transaction dataset.
- Establish a statistical outlier detection baseline using the IQR method.
- Develop and compare cluster-based and classification-based approaches.
- Evaluate detection performance using Precision@K, Recall@K and Lift@K.
- Explain why unusual transactions are not necessarily fraudulent.

### Analytical Methods
- Exploratory Data Analysis (EDA)
- Data cleaning, stratified splitting and feature scaling
- Interquartile Range (IQR) outlier detection
- K-Means clustering and distance-based anomaly scoring
- Logistic Regression
- XGBoost classification
- SMOTE for addressing class imbalance
- Model evaluation using ROC-AUC, PR-AUC, Precision@K, Recall@K and Lift@K

## Technologies and Libraries

The projects use:

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- SciPy
- Imbalanced-learn
- XGBoost

## Repository Structure

```text
Assignment-2/
│
├── Assign_2_part1.ipynb
├── Assignment2_part2.ipynb
├── requirements.txt
├── README.md
│
├── wholesale-customers.csv
└── creditcard.csv
```

## Installation and Execution

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
cd Assignment-2
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebooks

Open the notebooks using Jupyter Notebook, JupyterLab or Google Colab.

Ensure that the required datasets are available in the working directory before executing the notebooks.

## Expected Outputs

**Project 1:** Customer clusters, cluster profiles and business recommendations for improving customer targeting and service delivery.

**Project 2:** Comparative evaluation of statistical, cluster-based and classification-based fraud detection approaches, including identification of the strongest approach for prioritising potentially fraudulent transactions.
