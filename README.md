# 🏡 California Housing Price Prediction with PySpark

This project is the final submission for **DSCI 632: Applied Cloud Computing** at Drexel University. It uses the California Housing Prices dataset and applies distributed data processing and machine learning with **Apache Spark** and **PySpark** to predict housing prices.

The entire pipeline is implemented in a **Jupyter Notebook using Google Colab**, which allows for easy replication and cloud-based execution.

[![Open in NBViewer](https://img.shields.io/badge/Open%20Notebook-NBViewer-orange?logo=jupyter)](https://github.com/vlees46/Applied-Cloud-Computing/blob/main/California%20Housing%20Prices.ipynb)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/vlees46/Applied-Cloud-Computing/blob/main/California%20Housing%20Prices.ipynb)


<hr>
<div class="markdown-heading" dir="auto">
  <h3 class="heading-element" dir="auto">🧰 Languages and Tools</h3>
  <a id="user-content--languages-and-tools" class="anchor" aria-label="Permalink: 🧰 Languages and Tools" href="#-languages-and-tools">
    <svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true">
      <path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path>
    </svg>
  </a>
</div>

<!-- Python -->
<p dir="auto">
  <a href="https://www.python.org/" target="_blank" rel="noreferrer">
    <img align="left" alt="Python" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
  </a>
</p>

<!-- Apache Spark -->
<p dir="auto">
  <a href="https://spark.apache.org/" target="_blank" rel="noreferrer">
    <img align="left" alt="Apache Spark" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apache/apache-original-wordmark.svg" />
  </a>
</p>

<!-- Google Colab -->
<p dir="auto">
  <a href="https://colab.research.google.com/" target="_blank" rel="noreferrer">
    <img align="left" alt="Google Colab" width="40px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/Google_Colaboratory_SVG_Logo.svg/960px-Google_Colaboratory_SVG_Logo.svg.png?20221103151432" />
  </a>
</p>

<!-- Jupyter -->
<p dir="auto">
  <a href="https://jupyter.org/" target="_blank" rel="noreferrer">
    <img align="left" alt="Jupyter" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" />
  </a>
</p>

<!-- Pandas -->
<p dir="auto">
  <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer">
    <img align="left" alt="Pandas" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" />
  </a>
</p>

<!-- Seaborn -->
<p dir="auto">
  <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer">
    <img align="left" alt="Seaborn" width="40px" src="https://img.icons8.com/ios-filled/50/ffffff/combo-chart--v1.png" />
  </a>
</p>

<!-- GitHub -->
<p dir="auto">
  <a href="https://github.com/" target="_blank" rel="noreferrer">
    <img align="left" alt="GitHub" width="40px" src="https://img.icons8.com/ios-filled/50/ffffff/github.png" />
  </a>
</p>

<br clear="all">
<hr>

## 📌 Project Overview

This notebook demonstrates how to build a predictive pipeline using cloud-native and distributed tools, focusing on scalability, feature engineering, and model evaluation. All code and analysis were performed in **Google Colab** using **PySpark**.


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
