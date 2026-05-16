# 📊 Principal Component Analysis (PCA) from Scratch

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![NumPy](https://img.shields.io/badge/NumPy-Matrix%20Ops-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blueviolet.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow.svg)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Graphs-lightgrey.svg)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen.svg)

---
## 📌 Overview
This project demonstrates the implementation of **Principal Component Analysis (PCA)** from scratch using **Python and NumPy**, without using any built-in PCA functions from machine learning libraries such as Scikit-learn.

The goal is to understand the **mathematical intuition behind PCA** by manually implementing every step of dimensionality reduction.

PCA is widely used for:
- Reducing high-dimensional data
- Removing multicollinearity
- Data visualization
- Feature extraction

---
## 🎯 Objectives
- 🧠 Understand the mathematical foundation of PCA  
- ⚙️ Implement PCA using only NumPy  
- 📉 Reduce high-dimensional data into lower dimensions  
- 📊 Visualize transformed data in 2D space  
- 📈 Analyze explained variance to choose optimal components  

---
## 🛠️ Technologies Used
- 🐍 Python  
- 🔢 NumPy  
- 🧾 Pandas  
- 📊 Matplotlib  
- 📈 Plotly  

---
## ⚙️ Implementation Steps
- 📥 Load and preprocess the dataset
- 📏 Standardize features (mean = 0, variance = 1)
- 🔗 Compute covariance matrix
- 🧮 Perform eigen decomposition
- 📊 Sort eigenvalues and eigenvectors
- 🎯 Select top principal components
- 🔄 Transform data into reduced space
- 📉 Visualize results in 2D

---
# 🚀 Installation & Setup

## Clone Repository

```bash
git clone https://github.com/Sharif-Abusad/PCA_Demo.git
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Jupyter Notebook

```bash
jupyter notebook
```

---
## 📁 Project Structure

```bash
PCA/
|
├── 📓 PCA.ipynb
├── 📓 PCA_Implementation.ipynb
├── 📄 README.md
└── 📓 PCA_Implementation.ipynb
``` 

## 🧠 Key Concepts Covered
- Mean Centering and Standardization
- Covariance Matrix
- Eigenvalues and Eigenvectors
- Principal Components
- Explained Variance Ratio
- Dimensionality Reduction


## 📊 Results
- ✔️ Successfully reduced 3D data to 2D representation
- ✔️ Preserved maximum variance using principal components
- ✔️ Visualized transformed feature space
- ✔️ Analyzed cumulative explained variance for optimal component selection

## 💡 Learning Outcomes

Through this project, I gained a deeper understanding of:

- ➗ Linear algebra behind PCA
- 📊 Variance maximization principle
- 🧮 Eigen decomposition process
- 📉 Dimensionality reduction techniques in machine learning

---

# 👨‍💻 Author

**Sharif Abusad**

If you found this project useful, feel free to ⭐ the repository.