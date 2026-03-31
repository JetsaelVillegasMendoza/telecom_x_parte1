 📊 Telecom X Part I — Customer Churn Analysis (ETL & EDA) 

[![Proyecto](https://i.postimg.cc/59rqW8v9/una-empresa-ficticia-llamada-telecom-x-que.jpg)](https://postimg.cc/8shrhJtx)
![Status](https://img.shields.io/badge/status-completed-green)

## 📑 Table of Contents
- [🚀 Project Overview](#-project-overview)
- [🎯 Business Problem](#-business-problem)
- [🧠 Workflow](#-workflow)
- [📊 Key Insights](#-key-insights)
- [💡 Recommendations](#-recommendations)
- [📂 Repository Contents](#-repository-contents)
- [⚙️ How to Run](#️-how-to-run)
- [🧰 Tech Stack](#-tech-stack)
- [👤 Author](#-author)
- [🏁 Final Note](#-final-note)

---

## 🚀 Project Overview
This project analyzes customer churn in a telecom company through an **ETL and Exploratory Data Analysis (EDA) workflow**.

Using customer data extracted from an API, the project focuses on cleaning, transforming, and exploring the dataset to identify patterns associated with service cancellation and support future retention strategies.

---

## 🎯 Business Problem
Customer churn affects both revenue and long-term growth.

The goal of this project is to:
- Explore the characteristics of customers who leave the service
- Detect patterns related to churn
- Prepare a clean and structured dataset for analysis and future modeling
- Generate actionable insights to support retention efforts

---

## 🧠 Workflow

### 1. Data Extraction
- Retrieved customer data from an external API in JSON format

### 2. Data Transformation and Cleaning
- Renamed and standardized variables
- Handled missing values, inconsistencies, and duplicates
- Flattened nested columns
- Created new variables, such as estimated daily charges
- Standardized categorical values for easier interpretation

### 3. Exploratory Data Analysis
- Compared churned vs active customers across demographic, contractual, and billing variables
- Built visualizations to detect trends and segment differences, including:
  - Bar charts
  - Pie charts
  - Histograms
  - Boxplots
  - Violin plots

---

## 📊 Key Insights
- Customers with **monthly contracts** tend to churn more frequently
- **Short-tenure customers** show a higher risk of cancellation
- Customers with **higher charges** are more likely to leave
- Some service and payment method combinations appear more strongly associated with churn

---

## 💡 Recommendations
- Strengthen retention strategies for customers in their first months
- Encourage migration from monthly plans to longer-term contracts
- Review pricing and perceived value in higher-charge segments
- Use these findings as a foundation for future churn prediction modeling

---

## 📂 Repository Contents
- Data extraction process from API
- Data cleaning and transformation steps
- Exploratory analysis notebooks
- Visualizations and findings

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/telecom_x_parte_1.git
   ```

2. Navigate to the project folder:
   ```bash
   cd telecom_x_parte_1
   ```

3. Open and run the notebook using:
   - Jupyter Notebook
   - Google Colab
  
4. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
   ```
---
## 🧰 Tech Stack

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab  
- JSON / API data extraction  
- ETL processes  
- Exploratory Data Analysis

---

## 👤 Author

<p align="center">
  <a href="https://github.com/JetsaelVillegasMendoza">
    <img src="https://avatars.githubusercontent.com/u/157757330?v=4" width="115">
  </a><br>
  <sub><b>Jetsael Villegas</b></sub>
</p>

---

## 🏁 Final Note

This project was developed as part of the **Oracle Next Education (ONE)** program, in collaboration with **Alura LATAM**. It focuses on **data extraction**, **cleaning**, **transformation**, and **exploratory analysis** as the foundation for **churn understanding** and future **predictive modeling**.
