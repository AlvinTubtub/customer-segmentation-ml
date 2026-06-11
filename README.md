# Customer Segmentation using Machine Learning

Customer segmentation project using Machine Learning, K-Means clustering, and data visualization techniques in Python to analyze customer behavior and identify distinct market segments.

---

## Overview

This project applies **unsupervised machine learning** techniques to perform customer segmentation on mall customer data. The goal is to identify groups of customers based on purchasing behavior, annual income, spending score, and demographic information.

Using **K-Means Clustering**, the project uncovers patterns that can help businesses improve:

* Marketing strategies
* Customer targeting
* Product recommendations
* Business decision-making

---

## Features

* Exploratory Data Analysis (EDA)
* Data Cleaning and Preprocessing
* Customer Behavior Analysis
* K-Means Clustering
* Elbow Method for Optimal Clusters
* Cluster Visualization using 2D and 3D plots
* Customer Segment Identification
* Statistical Insights and Visualization

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Dataset

The dataset used in this project is the **Mall Customers Dataset** from Kaggle.

Dataset Source:
[Kaggle - Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python?utm_source=chatgpt.com)

### Dataset Attributes

| Column                 | Description                                  |
| ---------------------- | -------------------------------------------- |
| CustomerID             | Unique customer identifier                   |
| Gender                 | Customer gender                              |
| Age                    | Customer age                                 |
| Annual Income (k$)     | Annual income in thousand dollars            |
| Spending Score (1-100) | Customer spending score assigned by the mall |

---

## Machine Learning Approach

This project uses the **K-Means Clustering Algorithm**, an unsupervised learning technique used to group similar data points into clusters.

### Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Selection
5. Elbow Method Analysis
6. K-Means Model Training
7. Cluster Visualization
8. Customer Segment Interpretation

---

## Project Structure

```text id="4i0cij"
customer-segmentation-ml/
│
├── Customer_Behavior_Analysis_and_Segmentation.ipynb
├── Mall_Customers.csv
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash id="s7u57v"
git clone https://github.com/your-username/customer-segmentation-ml.git
```

Navigate to the project directory:

```bash id="s6yb7v"
cd customer-segmentation-ml
```

Install dependencies:

```bash id="pg5j59"
pip install -r requirements.txt
```

---

## Usage

Run the Jupyter Notebook:

```bash id="g9w8rf"
jupyter notebook
```

Open:

```text id="jlwmba"
Customer_Behavior_Analysis_and_Segmentation.ipynb
```

---

## Sample Analysis Performed

### Exploratory Data Analysis

* Distribution of customer age
* Annual income analysis
* Spending score analysis
* Gender distribution
* Correlation analysis

### Clustering Analysis

* Customer grouping based on:

  * Income vs Spending Score
  * Age vs Spending Score
* Cluster centroid visualization
* Optimal cluster detection using Elbow Method

---

## Example Customer Segments

| Cluster Type               | Description                |
| -------------------------- | -------------------------- |
| High Income, High Spending | Premium customers          |
| High Income, Low Spending  | Conservative customers     |
| Low Income, High Spending  | Impulsive buyers           |
| Low Income, Low Spending   | Budget-conscious customers |

---

## Future Improvements

* Feature Scaling using StandardScaler
* Silhouette Score Evaluation
* PCA Dimensionality Reduction
* Interactive Dashboard
* Deployment using Streamlit or Flask
* Real-time Customer Prediction
* Advanced Clustering Algorithms (DBSCAN, Hierarchical Clustering)

---

## Results

The project successfully identifies distinct customer groups that can assist businesses in:

* Personalized marketing
* Customer retention strategies
* Targeted promotions
* Product recommendation systems

---

## Learning Outcomes

Through this project, the following concepts were applied:

* Data preprocessing
* Exploratory Data Analysis
* Unsupervised Machine Learning
* Customer segmentation
* Data visualization
* Cluster analysis

---

## Author

AlvinTubtub

GitHub:
[AlvinTubtub GitHub Profile]

---

## License

This project is open-source and available under the MIT License.
