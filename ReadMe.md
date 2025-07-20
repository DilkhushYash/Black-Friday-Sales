# 🛍️ Black Friday Sales Data Analysis

> **Understand user purchasing behavior from the biggest shopping event of the year.**

## 📝 Table of Contents
- [📌 Overview](#-overview)  
- [🧠 Prerequisites](#-prerequisites)  
- [📂 Dataset Details](#-dataset-details)  
- [📊 Project Workflow](#-project-workflow)  
- [🔍 Key Analyses](#-key-analyses)  
- [✅ Conclusion](#-conclusion)  
- [📎 Dataset & Code Links](#-dataset--code-links)

---

## 📌 Overview

Black Friday is one of the most significant shopping events globally, marked by massive discounts and sales across various products. This project analyzes **Black Friday sales data** to uncover patterns based on **user demographics** such as gender, age, occupation, and marital status.

With over **537,000 entries**, the dataset allows us to:
- Explore user spending behavior
- Detect demographic influences on purchase decisions
- Derive actionable insights for marketing strategies

---

## 🧠 Prerequisites

Before diving in, make sure you're familiar with the following:

- 🐍 **Python (Basics)**
- 🧮 **Pandas** for data wrangling
- 📈 **Matplotlib** & **Seaborn** for visualizations
- 📓 **Jupyter Notebook**
- 🧹 **Data Cleaning** techniques (handling nulls, data types)
- 🔍 **Exploratory Data Analysis (EDA)**

---

## 📂 Dataset Details

| Attribute | Description |
|----------|-------------|
| **Name** | Black Friday Sales Dataset |
| **Size** | 23 MB |
| **Rows** | 537,000+ |
| **Columns** | 12 |
| **Features** | User ID, Product ID, Gender, Age, Occupation, City Category, Stay Duration, Marital Status, Product Categories, Purchase Amount |
| **Source** | [Download Dataset](https://datahack.analyticsvidhya.com/contest/black-friday/) |

---

## 📊 Project Workflow

### 1. 🗂️ Dataset Walkthrough
- Load dataset using `pandas`
- Identify missing values
- Overview via `df.info()`

### 2. 📈 Analyzing Individual Columns
- Focused analysis on `Gender`, `Age`, `Product_Category`, `Marital_Status`, and `Purchase`
- Dropped sparse columns like `Product_Category_2` and `3`

### 3. 👥 Gender Analysis
- Found male customers dominate purchase activity
- Used `groupby()` to quantify purchasing differences

### 4. 🎂 Age & 💍 Marital Status Analysis
- Compared spendings across age groups
- Observed spending habits based on marital status

### 5. 🧩 Multi-Column Analysis
- Combined columns like `Age`, `Gender`, `Marital_Status`
- Visualized complex relations via bar/pie plots

### 6. 🧑‍💼 Occupation & 🛒 Product Analysis
- Identified top occupations contributing to sales
- Explored product categories preferred by different occupations

### 7. ⚧️ Gender + Marital Status Analysis
- Used count plots to visualize combined effects
- Determined which combinations are high-converting

---

## 🔍 Key Analyses

| Analysis | Key Insights |
|---------|--------------|
| **Gender** | Males spent significantly more |
| **Age Group** | 26-35 age group made highest purchases |
| **Occupation** | Certain occupations preferred specific product categories |
| **Marital Status** | Singles tend to spend slightly more |
| **Combined Analysis** | Gender + Marital status combo reveals deeper buying trends |

---

## ✅ Conclusion

This project provided a deep dive into the behavior of shoppers during Black Friday. By analyzing individual and combined demographic features, we uncovered:

- Key purchasing patterns
- Demographics driving higher revenue
- Product category preferences based on user profiles

This analysis can help businesses **personalize marketing**, **optimize inventory**, and **target specific user segments**.

---

## 📎 Dataset & Code Links

- 📂 **Dataset**: [Black Friday Sales Dataset](https://datahack.analyticsvidhya.com/contest/black-friday/)
- 💻 **Code Repositories**:
  - 🔹 [Analyzing Columns](#)  
  - 🔹 [Gender Analysis](#)  
  - 🔹 [Age & Marital Status](#)  
  - 🔹 [Multi-Column Analysis](#)  
  - 🔹 [Occupation & Product](#)  
  - 🔹 [Gender & Marital Status](#)  

---

> ⭐ *Feel free to fork this repo, explore the dataset, and build on top of this analysis. Contributions are welcome!*
