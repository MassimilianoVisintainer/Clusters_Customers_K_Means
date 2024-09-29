# Clusters_Customers_K_Means


This project applies the K-Means clustering algorithm to segment customers into different groups based on their purchasing behavior. The goal is to provide insights into customer patterns, which can help in targeted marketing and improving customer retention strategies.


## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [License](#license)


## Introduction


K-Means clustering is a popular unsupervised machine learning algorithm that groups data points into `K` clusters. In this project, we analyze customer purchasing data and classify them into distinct clusters. This can be useful for businesses looking to personalize marketing strategies or better understand their customer base.


## Requirements


- Python 3.x
- Pandas
- Numpy
- Matplotlib
- Scikit-learn
- Jupyter Notebook (optional, for interactive exploration)


You can install the required Python packages using the following command:


```bash
pip install -r requirements.txt
```


## Installation


1. Clone this repository:


```bash
git clone https://github.com/MassimilianoVisintainer/Clusters_Customers_K_Means.git
```


2. Navigate to the project directory:


```bash
cd Clusters_Customers_K_Means
```


3. Install the required dependencies:


```bash
pip install -r requirements.txt
```


## Usage


1. Prepare your dataset in CSV format with customer features.
2. Run the `KMeans_Clustering.py` script or open the provided Jupyter Notebook to see the analysis in an interactive format.
   
```bash
python KMeans_Clustering.py
```


Alternatively, open `KMeans_Clustering.ipynb` in a Jupyter environment.


## Dataset


The dataset used for this project should include various customer attributes like:


- Annual income
- Spending score
- Age
- Gender (optional)


Make sure the dataset is cleaned and prepared before applying K-Means clustering.


## Results


The output will be:


- Visualizations of clusters formed from the customer data.
- Insights into different customer segments and their purchasing patterns.
  
You can modify the number of clusters `K` to experiment with different segmentations of the customer base.


