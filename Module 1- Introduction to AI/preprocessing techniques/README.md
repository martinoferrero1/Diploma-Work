# 🧹 Data Preprocessing Projects

This folder contains two independent projects focused on preparing datasets for machine learning models.

## 📊 1. `penguins_dataset_preprocessing`

This project involves cleaning and transforming a dataset of penguins obtained from **OpenML**.

Originally, the dataset was not specifically designed for supervised learning, as it did not include a predefined target column. However, for the purposes of this project, the **species of the penguins** was selected and treated as the target variable for classification tasks.

The preprocessing steps include:

- Handling missing values  
- Encoding categorical variables  
- Normalizing numerical features  
- Performing exploratory data analysis (EDA)  

After preprocessing, the dataset is ready to be used in classification models predicting penguin species.

## ✉️ 2. `spam_dataset_preprocessing`

This project focuses on **text preprocessing** using a dataset of text messages, some of which are labeled as **spam** and others as **non-spam**. The preprocessing steps include:

- Lowercasing  
- Removing punctuation and stopwords  
- Tokenization  
- Vectorization (e.g., TF-IDF or Bag of Words)  

After these transformations, the dataset is ready for training a spam detection model.

> 📎 The dataset used for this project, named `spam.csv`, is included in this folder.

---

Both projects emphasize the importance of proper data preprocessing as a key step before applying machine learning techniques.
