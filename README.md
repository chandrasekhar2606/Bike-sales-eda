# Bike-sales-eda
Bike Sales EDA | Customer Segmentation &amp; Purchase Behavior Analysis using Python, Pandas, Seaborn &amp; Matplotlib
# 🚲 Bike Sales EDA – Customer Purchase Behavior Analysis

## 📌 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on a bike sales customer dataset to understand the demographic and behavioral factors that influence customers' decisions to purchase a bike.

The analysis examines customer characteristics such as **income, age, education, occupation, marital status, commute distance, number of children, car ownership, home ownership, and region** to identify patterns associated with bike purchases.

The goal is to transform raw customer data into **actionable business insights** that can support marketing, customer targeting, and sales strategies.

---

## 🎯 Business Problem

An international bike retailer wants to improve its marketing and sales performance by understanding:

* Which customer groups are more likely to purchase bikes?
* Does income influence bike purchases?
* Does education or occupation affect purchasing behavior?
* How does commute distance impact bike purchases?
* Which regions have higher purchase rates?
* Does age, marital status, or number of children influence purchasing decisions?
* Are homeowners more likely to purchase bikes?

---

## 🛠️ Technologies & Tools

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Development and analysis environment
* **Excel** – Source dataset

---

## 📊 Dataset

The project uses a customer dataset containing information about bike buyers.

### Key Features

| Feature            | Description                           |
| ------------------ | ------------------------------------- |
| `ID`               | Customer identifier                   |
| `Marital_Status`   | Customer's marital status             |
| `Gender`           | Customer gender                       |
| `Income`           | Customer income                       |
| `Children`         | Number of children                    |
| `Education`        | Education level                       |
| `Occupation`       | Customer occupation                   |
| `Home_Owner`       | Home ownership status                 |
| `Cars`             | Number of cars owned                  |
| `Commute_Distance` | Distance travelled for commuting      |
| `Region`           | Customer region                       |
| `Age`              | Customer age                          |
| `Purchased_Bike`   | Whether the customer purchased a bike |

---

## 🔄 Data Preparation

The following preprocessing steps were performed:

1. Loaded the dataset from Excel using Pandas.
2. Inspected the dataset structure and descriptive statistics.
3. Checked for missing values.
4. Renamed columns for consistency and readability.
5. Removed the `Age_Bracket` column.
6. Converted the `Purchased_Bike` variable from:

   * `Yes` → `1`
   * `No` → `0`

This prepared the dataset for statistical analysis and visualization.

---

## 🔍 Exploratory Data Analysis

The project investigates several business questions.

### 1. Overall Bike Purchase Rate

Calculated the percentage of customers who purchased a bike.

### 2. Marital Status

Analyzed whether marital status is associated with different bike purchase rates.

### 3. Income

Compared the average income of customers who purchased bikes with those who did not.

### 4. Education

Examined whether education level influences the likelihood of purchasing a bike.

### 5. Occupation

Compared bike purchase rates across different occupational groups.

### 6. Age & Income

Analyzed the relationship between age and income among bike buyers, including gender as a visual grouping variable.

### 7. Commute Distance

Investigated how commute distance affects bike purchasing behavior.

### 8. Regional Distribution

Analyzed the distribution of customers across different regions.

### 9. Correlation Analysis

Created a correlation heatmap to examine relationships between numeric variables such as:

* Age
* Income
* Children
* Cars
* Bike Purchase

### 10. Regional Purchase Rates

Compared bike purchase rates across different geographical regions.

### 11. Number of Children

Investigated whether the number of children is associated with bike purchasing behavior.

### 12. Age Distribution

Compared the age distribution of customers based on whether they purchased a bike.

### 13. Home Ownership

Analyzed whether homeowners have different bike purchase rates compared with non-homeowners.

---

## 📈 Key Insights

The analysis identified several patterns in the customer data:

* Married customers tend to have higher bike purchase rates than single customers.
* Customers with higher education levels show stronger purchasing tendencies.
* Professional occupations are associated with higher bike purchase rates.
* Shorter commute distances are associated with more bike purchases.
* Higher-income customers tend to be stronger potential bike buyers.
* Customers with fewer children show higher purchase tendencies.
* Homeowners tend to have stronger bike purchasing behavior.
* Certain regions, including the Pacific region, demonstrate stronger purchase rates.

---

## 💡 Business Recommendations

Based on the exploratory analysis, the following strategies could help the bike retailer:

### 🎯 Targeted Marketing

Focus marketing campaigns on customer segments showing higher purchase rates, particularly professionals and married customers.

### 🌍 Regional Marketing

Allocate additional marketing resources to regions with higher bike purchase rates.

### 🚲 Commuter-focused Campaigns

Promote bikes as an alternative transportation option for customers with shorter commuting distances.

### 💰 Customer Segmentation

Use income, occupation, education, age, and family characteristics to identify high-potential customer segments.

### 🤝 Customer Retention

Consider loyalty programs and targeted offers for high-income and high-value customers.

---



---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

### 4. Run the notebook

Open:

```text
Ai_and_applicationsproject.ipynb
```

and execute the cells sequentially.

---

## 📌 Skills Demonstrated

This project demonstrates practical skills in:

* Exploratory Data Analysis
* Data Cleaning
* Data Preprocessing
* Business Question Formulation
* Statistical Analysis
* Customer Segmentation
* Data Visualization
* Correlation Analysis
* Business Insight Generation
* Data-driven Recommendations
* Python for Data Science

---

## 👨‍💻 Author

**Chandra Sekhar**

Data Science Student | Python | SQL | Machine Learning | Data Analytics

---

## ⭐ Project Objective

The main objective of this project is to demonstrate how **data science and exploratory analysis can be used to understand customer purchasing behavior and translate data into actionable business recommendations.**
