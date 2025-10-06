# 🤖 Module 2 – Traditional Machine Learning: Regression, Classification, Clustering & Anomaly Detection

This directory contains a collection of projects developed as part of **Module 2** of the Artificial Intelligence University Diploma (DUIA) at UNICEN.  
The projects explore **core machine learning paradigms** through practical, real-world problems, covering **regression**, **classification**, **clustering**, and **anomaly detection** techniques.

## 🔄 Project Structure & Learning Progression

The projects were developed **progressively**, each focusing on a key branch of traditional ML:

---

### 🏠 Regression – Property Price Estimation  
This project focuses on **predicting property prices** based on multiple features such as location, surface area, and amenities.  
Different regression algorithms were implemented and compared, including:

- **Linear Regression**
- **Lasso Regression**
- **Random Forest Regressor**
- **XGBoost Regressor**

Model performance was evaluated through metrics such as:

- Mean Squared Error (MSE)  
- Mean Absolute Error (MAE)  
- R² Score  

Feature importance analysis and hyperparameter tuning were used to balance **bias and variance**, ensuring strong generalization.

---

### 🍳 Classification – Predicting Subscriber Preferences for Recipe Videos  
In this project, the goal was to **classify viewer preferences** for recipe videos (like/dislike) based on engagement patterns and user profiles.  
The models explored include:

- **Support Vector Machines (SVM)**
- **Random Forest**
- **K-Nearest Neighbors (KNN)**
- **Logistic Regression**

To enhance performance and data balance, the workflow incorporated:

- **SMOTE** for synthetic oversampling  
- **Principal Component Analysis (PCA)** for dimensionality reduction  
- **ROC Curves** and **AUC** for model comparison  

Evaluation metrics included **Accuracy**, **Precision**, **Recall**, **F1-score**, and **Confusion Matrices**.

---

### 🧩 Clustering – Customer Segmentation for Targeted Marketing  
This project applied **unsupervised learning** techniques to group customers based on their spending habits and preferences, aiming to improve marketing strategies.  
Implemented algorithms:

- **K-Means Clustering**
- **Hierarchical Clustering**

The choice of the optimal number of clusters was guided by:

- **Elbow Method**  
- **Silhouette Score**

Each cluster was analyzed in terms of demographic and behavioral characteristics to extract actionable insights.

---

### 💳 Anomaly Detection – Credit Card Fraud Identification  
This project focused on **detecting anomalous transactions** in credit card data to identify potential fraud.  
Methods explored:

- **Isolation Forest**
- **Local Outlier Factor (LOF)**
- **One-Class SVM**

The models were evaluated using metrics such as:

- **Precision**, **Recall**, and **F1-score**
- **ROC-AUC**  
- **Confusion Matrix**, with special attention to **false negatives** due to their importance in fraud detection.

---

## 📏 Model Evaluation & Methodology

Across all tasks, consistent workflows were established including:

- **Train/test splits** and **cross-validation**
- **Hyperparameter tuning** with `GridSearchCV`
- **Feature scaling** (Standardization & Normalization)
- **Data visualization** for exploratory data analysis (EDA)

These ensured both interpretability and robustness in every model.

---

## 🛠️ Technologies Used

Key Python libraries and frameworks:

- [`scikit-learn`](https://scikit-learn.org/)  
- [`xgboost`](https://xgboost.readthedocs.io/)  
- [`pandas`](https://pandas.pydata.org/)  
- [`numpy`](https://numpy.org/)  
- [`matplotlib`](https://matplotlib.org/)  
- [`seaborn`](https://seaborn.pydata.org/)  
- [`imblearn`](https://imbalanced-learn.org/stable/) (for SMOTE)  

---

These projects collectively demonstrate a strong foundation in **traditional machine learning**, emphasizing rigorous preprocessing, thoughtful model selection, and careful evaluation—core skills that bridge data understanding and predictive insight.
