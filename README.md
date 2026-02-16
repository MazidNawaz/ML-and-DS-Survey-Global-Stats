# 📊 Kaggle Survey (2017–2021) – Evolution of Data Science

![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue)
![Python](https://img.shields.io/badge/Python-3.x-yellow)
![Pandas](https://img.shields.io/badge/Analysis-Data%20Science-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 🌍 Project Overview

This project analyzes the **evolution of the Data Science community** using the Kaggle Survey dataset from **2017 to 2021**.

The dataset was manually aggregated to allow easier comparison across years, enabling deeper insights into:

- 📈 Programming language trends  
- 🧠 Machine learning framework adoption  
- 💻 IDE usage evolution  
- 🎓 Career and education patterns  
- 📊 Industry growth over time  

Instead of analyzing surveys separately, this dataset introduces a **time dimension**, helping us understand how the data science landscape has evolved.

---

## 🗂 Dataset Information

### 📌 Data Sources

- 2017 Survey  
- 2018 Survey  
- 2019 Survey  
- 2020 Survey  
- 2021 Survey  

All surveys were originally hosted by Kaggle.

---

## 🛠 Methodology

The dataset was manually aggregated using the following approach:

1. **2021 survey** was used as the base reference (most updated structure).
2. Previous years (2017–2020) were analyzed one by one.
3. Matching questions and answers were manually aligned.
4. Differences in:
   - Question wording
   - Order
   - Answer types  
   were carefully handled.
5. Since older surveys have fewer questions, analysis is recommended using **percentages instead of absolute values**.

This manual aggregation ensures higher accuracy in cross-year comparisons.

---

## 📦 Dataset Contents

- `kaggle_survey_2017_2021.csv` → Aggregated dataset (2017–2021)
- `style.css` → Custom notebook styling
- `images/` → Visual assets used in analysis notebook

---

## 🔍 What I Did in This Project

### 🧹 Data Cleaning
- Removed extra spaces from categorical values
- Standardized inconsistent naming (e.g., TensorFlow vs tensorflow)
- Converted multi-select responses into numerical format
- Handled missing values
- Structured data for year-wise comparison

---

### 📊 Exploratory Data Analysis (EDA)

I performed complete visualization and trend analysis on:

#### 💻 Programming Languages
- Most used languages each year
- Growth of Python dominance
- Decline or stability of R, SQL, etc.

#### 🧠 Machine Learning Frameworks
- TensorFlow vs PyTorch growth
- Rise of LightGBM, XGBoost, CatBoost
- Industry shift toward deep learning

#### 🖥 IDE Usage
- Jupyter popularity
- VS Code growth over time
- Decline of traditional editors

#### 📈 Year-wise Trends
- Community expansion
- Industry evolution patterns
- Technology adoption curves

---

## 📊 Key Insights

- 🥇 Python dominates consistently across all years.
- 🚀 PyTorch shows rapid adoption after 2019.
- 📈 VS Code usage increases significantly over time.
- 📉 Some legacy tools show decreasing trends.
- 🌎 Data Science community has expanded massively year over year.

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🚀 How to Run This Project

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
jupyter notebook
