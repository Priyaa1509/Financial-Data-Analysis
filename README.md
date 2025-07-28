
# Company Financial Performance Analysis & Classification

This project analyzes financial data of tech companies and builds a machine learning pipeline to study patterns and cluster companies based on financial performance. Later, a supervised learning pipeline is built using a manually engineered target.

## Features

* Exploratory Data Analysis (EDA) with multi-subplots and visualizations
* Data normalization using StandardScaler
* Dimensionality Reduction using Principal Component Analysis (PCA)
* Unsupervised Learning: K-Means and DBSCAN on PCA-reduced data
* Engineered a target variable to build a classification model
* Supervised Learning: Logistic Regression (93%) and Random Forest (96%)
* SMOTE applied to handle class imbalance
* Model evaluation using accuracy, precision, recall, and confusion matrix

## Dataset

* **Source**: Kaggle dataset


## ML Techniques

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 93%      |
| Random Forest       | 96%      |

* SMOTE used for class imbalance correction
* Evaluation includes precision, recall, and confusion matrix

## Technologies Used

* Python (Pandas, NumPy)
* Visualization: Matplotlib, Seaborn
* Machine Learning: scikit-learn
* Imbalanced Data Handling: imbalanced-learn

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook notebook/Company_Finance.ipynb
```
