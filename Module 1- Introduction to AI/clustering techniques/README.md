# 🔍 Clustering Project

This folder contains a project focused on applying **unsupervised learning techniques**, specifically clustering, to a dataset composed of numerical features.

Although clustering is typically performed on data without labels, in this case the dataset includes a **known target variable** (class labels). This provided a unique opportunity to perform both:

- **External evaluation**, using the real classes as reference  
- **Internal evaluation**, simulating a real-world scenario where such labels are not available

## 🧪 Project Overview

The workflow involved:

- Analyzing the dataset using visualization and statistical tools  
- Selecting appropriate preprocessing techniques based on the data’s characteristics  
- Applying various clustering algorithms  
- Comparing clustering performance through:

  - **External metrics** (e.g., Adjusted Rand Index, Homogeneity, Completeness)  
  - **Internal metrics** using:
    - **Silhouette Score**  
    - **Elbow Method**  

This dual approach allowed for a deeper understanding of how different preprocessing strategies and models behave, both in a controlled (labeled) and an unlabeled context.

---

This project highlights the importance of critical preprocessing and model selection decisions in unsupervised learning tasks, and how evaluation strategies must adapt when ground truth is or isn’t available.
