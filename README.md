# Customer Segmentation using K-Means Clustering

## Description

This project applies K-Means clustering to segment retail customers based on purchasing behavior and spending patterns. The goal is to identify meaningful customer groups that can support targeted marketing and business strategies.

## Objective

To group customers with similar characteristics using unsupervised learning techniques and derive actionable insights from the resulting clusters.

## Dataset

Source: Kaggle – Customer Segmentation Dataset
[https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

The dataset includes features such as annual income, spending score, and age.

## Workflow

* Data loading and initial exploration
* Feature scaling and outlier analysis
* Determination of optimal number of clusters using the elbow method
* K-Means model training
* Visualization of clusters using 2D and 3D plots

## How to Run

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install required dependencies:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
3. Download the dataset from Kaggle and place it in the project directory.
4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
5. Open the notebook and run all cells sequentially.

## Results

The model identified five optimal clusters representing distinct customer groups, including low-value, mid-value, and high-value customers.

## Tech Stack

* Python (NumPy, Pandas, Scikit-learn)
* Matplotlib, Seaborn
* Jupyter Notebook

## Future Enhancements

* Include demographic and transaction frequency data
* Experiment with alternative clustering algorithms such as DBSCAN and hierarchical clustering
