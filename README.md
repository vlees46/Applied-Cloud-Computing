# 🏡 California Housing Price Prediction with PySpark

This project is the final submission for **DSCI 632: Applied Cloud Computing** at Drexel University. It uses the California Housing Prices dataset and applies distributed data processing and machine learning with **Apache Spark** and **PySpark** to predict housing prices.

The entire pipeline is implemented in a **Jupyter Notebook using Google Colab**, which allows for easy replication and cloud-based execution.

[![Open in NBViewer](https://img.shields.io/badge/Open%20Notebook-NBViewer-orange?logo=jupyter)](https://github.com/vlees46/Applied-Cloud-Computing/blob/main/California%20Housing%20Prices.ipynb)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/vlees46/Applied-Cloud-Computing/blob/main/California%20Housing%20Prices.ipynb)

---
<h3 align="left">🧰 Languages and Tools</h3>

<p align="left">
  <!-- Python -->
  <a href="https://www.python.org/" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
  </a>

  <!-- Apache Spark -->
  <a href="https://spark.apache.org/" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apache/apache-original-wordmark.svg" alt="Apache Spark" width="40" height="40"/>
  </a>

  <!-- PySpark (via Python + Spark icons) -->

  <!-- Google Colab -->
  <a href="https://colab.research.google.com/" target="_blank" rel="noreferrer">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/Google_Colaboratory_SVG_Logo.svg/960px-Google_Colaboratory_SVG_Logo.svg.png?20221103151432" alt="Google Colab" width="40" height="40"/>
  </a>

  <!-- Jupyter -->
  <a href="https://jupyter.org/" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" alt="Jupyter Notebook" width="40" height="40"/>
  </a>

  <!-- Pandas -->
  <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" alt="Pandas" width="40" height="40"/>
  </a>

  <!-- Seaborn (no official icon, using generic graph icon) -->
  <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer">
    <img src="https://img.icons8.com/ios-filled/50/000000/combo-chart--v1.png" alt="Seaborn" width="40" height="40"/>
  </a>

  <!-- GitHub -->
  <a href="https://github.com/" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" width="40" height="40"/>
  </a>
</p>



## 📌 Project Overview

This notebook demonstrates how to build a predictive pipeline using cloud-native and distributed tools, focusing on scalability, feature engineering, and model evaluation. All code and analysis were performed in **Google Colab** using **PySpark**.

---

## 🚀 Key Highlights

- Processed large datasets using **Apache Spark** on **Google Colab**
- Cleaned and transformed data, including imputation and encoding of categorical variables
- Applied **log transformation** to normalize skewed distributions
- Built a **Linear Regression** model to predict housing prices
- Evaluated model performance using **R² score** and **Mean Absolute Error**
- Used **Seaborn** and **Pandas** for visualization

---

## 📊 Key Skills Demonstrated

- `PySpark`
- `Apache Spark`
- `Google Colab`
- `Jupyter Notebook`
- `Linear Regression`
- `Feature Engineering`
- `Log Transformation`
- `VectorAssembler`
- `StringIndexer`
- `Data Cleaning`
- `Exploratory Data Analysis (EDA)`
- `Model Evaluation`
- `Big Data Processing`
- `Distributed Computing`
- `California Housing Dataset`

---

## 📂 Dataset

- [California Housing Prices Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

---

## 📈 Example Outputs

- **R² Score (Test Set):** ~0.57  
- **MAE (Test Set):** Output displayed in the notebook

---

## 🧠 Future Improvements

- Explore non-linear models such as Random Forest or Gradient Boosted Trees
- Add hyperparameter tuning with CrossValidator
- Deploy using a streaming architecture for real-time pricing analysis

---

## 🔗 Run It Yourself

- Clone this repo or open the notebook in **Google Colab**
- Ensure your dataset is accessible via Google Drive or public URL
- Follow step-by-step instructions in the notebook
