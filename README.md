# 🏡 California Housing Price Prediction with PySpark

This project is the final submission for **DSCI 632: Applied Cloud Computing** at Drexel University. It uses the California Housing Prices dataset and applies distributed data processing and machine learning with **Apache Spark** and **PySpark** to predict housing prices.

The entire pipeline is implemented in a **Jupyter Notebook using Google Colab**, which allows for easy replication and cloud-based execution.

[![Open in NBViewer](https://img.shields.io/badge/Open%20Notebook-NBViewer-orange?logo=jupyter)](https://github.com/vlees46/Applied-Cloud-Computing/blob/main/California%20Housing%20Prices.ipynb)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/vlees46/Applied-Cloud-Computing/blob/main/California%20Housing%20Prices.ipynb)

---
<div class="markdown-heading" dir="auto"><h3 class="heading-element" dir="auto">🧰 Languages and Tools</h3><a id="user-content--languages-and-tools" class="anchor" aria-label="Permalink: 🧰 Languages and Tools" href="#-languages-and-tools"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/0d4b500c99671bf83bcb747e4f25f3da28765f2bbb4cdd9733c09f9a46381aaa/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6a6176612f6a6176612d6f726967696e616c2e737667"><img align="left" alt="Java" width="30px" src="https://camo.githubusercontent.com/0d4b500c99671bf83bcb747e4f25f3da28765f2bbb4cdd9733c09f9a46381aaa/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6a6176612f6a6176612d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/6d836114e08a9f246b20f8b589a26010ddf99f37b90a157e1df38e19705a5ea5/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f737072696e672f737072696e672d6f726967696e616c2e737667"><img align="left" alt="Spring" width="30px" src="https://camo.githubusercontent.com/6d836114e08a9f246b20f8b589a26010ddf99f37b90a157e1df38e19705a5ea5/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f737072696e672f737072696e672d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/05467270e4f52b90b6d7ae9735be74ab62700fb799f0d16941f61e5f7c13c05e/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f747970657363726970742f747970657363726970742d706c61696e2e737667"><img align="left" alt="TypeScript" width="30px" src="https://camo.githubusercontent.com/05467270e4f52b90b6d7ae9735be74ab62700fb799f0d16941f61e5f7c13c05e/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f747970657363726970742f747970657363726970742d706c61696e2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-plain.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/f4482ba65310f8a3ec5ec1c49714decca11fa5665fd648bac9f90d5a9dbc53cc/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f616e67756c61726a732f616e67756c61726a732d706c61696e2e737667"><img align="left" alt="Angular" width="30px" src="https://camo.githubusercontent.com/f4482ba65310f8a3ec5ec1c49714decca11fa5665fd648bac9f90d5a9dbc53cc/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f616e67756c61726a732f616e67756c61726a732d706c61696e2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-plain.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/15166a15835f145259844be455ab5945594a70c48a3090aa83d193bd5e3e9bc5/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6769742f6769742d6f726967696e616c2e737667"><img align="left" alt="Git" width="30px" src="https://camo.githubusercontent.com/15166a15835f145259844be455ab5945594a70c48a3090aa83d193bd5e3e9bc5/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6769742f6769742d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/f91287c9aac55623bc37ceb651ac35b7efb56e422019a3bb59328328a09edf9f/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6c696e75782f6c696e75782d6f726967696e616c2e737667"><img align="left" alt="Linux" width="30px" src="https://camo.githubusercontent.com/f91287c9aac55623bc37ceb651ac35b7efb56e422019a3bb59328328a09edf9f/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6c696e75782f6c696e75782d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/d91a719ff03fb705982d4462a546806028623ddf5c558c7cf969c41afa7310e0/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f68746d6c352f68746d6c352d706c61696e2e737667"><img align="left" alt="HTML" width="30px" src="https://camo.githubusercontent.com/d91a719ff03fb705982d4462a546806028623ddf5c558c7cf969c41afa7310e0/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f68746d6c352f68746d6c352d706c61696e2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/aca95aa2f447d7f13f23a47b88e6eb655f5e5ea279b2a37da6eae2d2197aefe0/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f637373332f637373332d706c61696e2e737667"><img align="left" alt="CSS" width="30px" src="https://camo.githubusercontent.com/aca95aa2f447d7f13f23a47b88e6eb655f5e5ea279b2a37da6eae2d2197aefe0/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f637373332f637373332d706c61696e2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/34c801e15a80d0d62f3da09bc6ca4f46a243457939381ae67f5003bdac51d432/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6a6176617363726970742f6a6176617363726970742d706c61696e2e737667"><img align="left" alt="JavaScript" width="30px" src="https://camo.githubusercontent.com/34c801e15a80d0d62f3da09bc6ca4f46a243457939381ae67f5003bdac51d432/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6a6176617363726970742f6a6176617363726970742d706c61696e2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/34b891c76d258e4b0ee593443e5cbc2506cdbb7d3cd6bc0e4beffa87a9c1611b/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f72656163742f72656163742d6f726967696e616c2e737667"><img align="left" alt="React" width="30px" src="https://camo.githubusercontent.com/34b891c76d258e4b0ee593443e5cbc2506cdbb7d3cd6bc0e4beffa87a9c1611b/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f72656163742f72656163742d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/d21012299f2ccd4a7d73b13f896b0be91c9e71bb7f0b51f1cbfb783ed6b9f9b1/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6e6f64656a732f6e6f64656a732d6f726967696e616c2e737667"><img align="left" alt="NodeJS" width="30px" src="https://camo.githubusercontent.com/d21012299f2ccd4a7d73b13f896b0be91c9e71bb7f0b51f1cbfb783ed6b9f9b1/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6e6f64656a732f6e6f64656a732d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/6094c387099a9a467f1338a85dafab3d06cab803e29aeff968bf7babd58d5249/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f707974686f6e2f707974686f6e2d706c61696e2e737667"><img align="left" alt="Python" width="30px" src="https://camo.githubusercontent.com/6094c387099a9a467f1338a85dafab3d06cab803e29aeff968bf7babd58d5249/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f707974686f6e2f707974686f6e2d706c61696e2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/ca92f93ae51fcbf2bb7a57dfeb4f499d4b3c5545332edc44ae632ff56107f815/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f63706c7573706c75732f63706c7573706c75732d6c696e652e737667"><img align="left" alt="C++" width="30px" src="https://camo.githubusercontent.com/ca92f93ae51fcbf2bb7a57dfeb4f499d4b3c5545332edc44ae632ff56107f815/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f63706c7573706c75732f63706c7573706c75732d6c696e652e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-line.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/2e3402a95bea6acba7dd5d26566d797607b63a6bdec43942c8286fbf7db4a177/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6769746875622f6769746875622d6f726967696e616c2e737667"><img align="left" alt="GitHub" width="30px" src="https://camo.githubusercontent.com/2e3402a95bea6acba7dd5d26566d797607b63a6bdec43942c8286fbf7db4a177/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f6769746875622f6769746875622d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/26e44b2fdc869c8fa8c3899b253bca6a11bc666e17ec1065b431376885891383/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f626173682f626173682d6f726967696e616c2e737667"><img align="left" alt="Bash" width="30px" src="https://camo.githubusercontent.com/26e44b2fdc869c8fa8c3899b253bca6a11bc666e17ec1065b431376885891383/68747470733a2f2f63646e2e6a7364656c6976722e6e65742f67682f64657669636f6e732f64657669636f6e2f69636f6e732f626173682f626173682d6f726967696e616c2e737667" data-canonical-src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" style="max-width: 100%;"></a></p>
<br>
<h1 dir="auto"></h1>

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
