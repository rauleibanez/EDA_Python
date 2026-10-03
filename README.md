# 📊 Exploratory Data Analysis (EDA) with Python & Pandas

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/Status-Completed-success.svg" alt="Status">
  <img src="https://img.shields.io/badge/Bootcamp-2024-orange.svg" alt="Bootcamp 2024">  
</p>

**Developed as part of the Python & Data Analysis Bootcamp (2024)**

Welcome to the **Exploratory Data Analysis (EDA)** project repository! This project serves as a comprehensive practical demonstration of data wrangling, statistical analysis, and data visualization techniques using the Python data science stack.

---

## 🎯 Project Objectives

This project was built to master and apply foundational data science workflows, focusing on:

* **Advanced EDA Techniques:** Applying systematic exploratory data analysis on complex tabular datasets using Python.
* **Data Visualization:** Producing insightful, publication-ready statistical visualizations using **Seaborn** and **Matplotlib**.
* **Data Cleaning & Quality Control:** Effectively identifying, managing, and rectifying duplicate records and missing values to ensure data integrity.

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python
* **Environment:** Jupyter Notebooks
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib
* **Automated Profiling:** Pandas Profiler

---

## 📂 Project Structure & Workflow

The hands-on project is structured into **5 core phases** designed to simulate a real-world data analysis pipeline:

### Task 1: Initial Data Exploration

* **Environment Setup:** Initialized interactive computing workflows within **Jupyter Notebooks**.
* **Library Integration:** Imported essential data science libraries (`NumPy`, `Pandas`, `Seaborn`, `Matplotlib`).
* **Data Inspection:** Loaded datasets using Pandas, previewed structural integrity, and generated initial descriptive summary statistics for numeric features.

### Task 2: Univariate Analysis

* **Distribution Mapping:** Analyzed customer rating distributions using Seaborn, overlaying statistical markers such as the mean and 25th/75th percentile quantiles calculated via NumPy.
* **Numerical Overview:** Utilized Pandas' `.hist()` method to visualize frequency distributions across all numeric attributes.
* **Categorical Breakdown:** Applied Seaborn's `.countplot()` to examine frequency distributions for categorical variables like `Branch` and `Payment` methods.

### Task 3: Bivariate Analysis

* **Correlation & Trends:** Generated scatterplots and regression plots via Seaborn to uncover relationships between customer ratings and gross income.
* **Comparative Insights:** Implemented Seaborn boxplots to evaluate aggregate sales performance variations across three supermarket branches and contrasted purchasing patterns between demographics.
* **Time Series Analysis:** Plotted temporal trends to monitor gross income fluctuations over a 3-month period.

### Task 4: Dealing with Duplicate Rows and Missing Values

* **Data Hygiene:** Quantified and successfully removed duplicate rows to prevent bias.
* **Imputation Strategies:** Addressed missing data points by replacing null values with column-specific statistical means rather than dropping critical observations.
* **Automated Profiling:** Explored automated dataset auditing using Pandas Profiler to streamline rapid exploratory assessments.

### Task 5: Correlation Analysis

* **Statistical Correlation:** Calculated pairwise numerical correlations using NumPy.
* **Matrix Generation:** Built a comprehensive correlation matrix via Pandas to map relationships across all numeric variables.
* **Heatmap Visualization:** Rendered an easily interpretable correlation heatmap using Seaborn to highlight multicollinearity and key performance drivers.

---

## 🚀 Key Learnings & Takeaways

Completing this project during the **2024 Python & Data Analysis Bootcamp** solidified my ability to transform raw, unstructured tabular data into clean, actionable insights. It strengthened my core data manipulation skills in Pandas and honed my technical storytelling capabilities through advanced data visualization.

---

## 🎯 About the Bootcamp

The 2024 Bootcamp provided a rigorous curriculum focused on modern data science workflows, software engineering best practices in Python, and advanced analytical techniques. Throughout this program, I built end-to-end data pipelines, performed exploratory data analysis (EDA), and developed machine learning models to solve real-world problems.

---

## 🛠️ Tech Stack & Skills Acquired

- **Programming Languages:** Python 3.x
- **Data Manipulation & Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn, Plotly
- **Database & SQL:** Relational databases, SQL queries, SQLAlchemy
- **Machine Learning & Statistics:** Scikit-learn, statistical hypothesis testing, regression & classification models
- **Development Tools:** Git, GitHub, Jupyter Notebooks, VS Code
- **Automated Data Pipelines:** Built efficient ETL (Extract, Transform, Load) workflows using Pandas and SQL to streamline data ingestion.
- **Predictive Modeling:** Developed and evaluated machine learning classifiers to predict outcomes based on historical metrics.

---

## 🌟 Future Goals

As I continue my journey in data science, I plan to expand this repository with advanced deep learning projects, cloud-based data engineering pipelines (AWS/GCP), and interactive web dashboards using Streamlit.
documents.
- Next, we will import essential libraries such as NumPy, Pandas, Seaborn, Matplotlib and so on.
- We use Pandas to read in the data, get a brief glimpse of the first few rows, and calculate some quick summary statistics of the numeric columns.
    
