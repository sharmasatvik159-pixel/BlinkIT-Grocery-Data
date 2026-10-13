# BlinkIT Grocery Sales Analysis

![Domain](https://img.shields.io/badge/Domain-Retail%20%26%20Grocery%20Sales%20Analytics-blue)
![Tools](https://img.shields.io/badge/Tools-Python%20%7C%20Pandas%20%7C%20Seaborn%20%7C%20Matplotlib-green)
![Environment](https://img.shields.io/badge/Environment-Google%20Colab-orange)

## 📌 Project Overview
This project focuses on analyzing grocery sales data for **BlinkIT** under **Sapphire IQ**[cite: 1]. As a Data Analyst, the goal is to evaluate sales performance across various product categories, outlet types, store locations, and customer characteristics[cite: 1]. The insights generated help management optimize product selection, inventory distribution, outlet efficiency, and strategic business planning[cite: 1, 2].

---

## 🎯 Project Objectives & Workflow

### Objective 1: Business Overview & Sales Performance
- Analyze the distribution of product categories sold by BlinkIT[cite: 2].
- Examine outlet types and location tiers (Tier 1, Tier 2, Tier 3)[cite: 2].
- Evaluate overall gross sales, mean sales, and median sales metrics[cite: 2].
- Assess overall customer satisfaction ratings across products[cite: 2].

### Objective 2: Data Reliability & Quality Assurance
- Identify and summarize missing values across dataset features[cite: 2].
- Detect and eliminate duplicate entries[cite: 2].
- Identify statistical outliers in numerical columns using boxplots[cite: 2].
- Standardize categorical entries (e.g., merging `LF`, `low fat`, and `Low Fat`) and impute missing records[cite: 2].

### Objective 3: Key Drivers of Sales Performance
- Identify high-performing product categories contributing most to total sales[cite: 2].
- Evaluate performance across different outlet models and location tiers[cite: 2].
- Analyze correlation between sales, product visibility, weight, and ratings[cite: 2].
- Compare top 10% high-performing items against bottom 10% underperforming items[cite: 2].

### Objective 4: Management Decision Support & Actionable Insights
- Apply Pareto analysis (80/20 rule) to measure cumulative sales contribution[cite: 2].
- Rank top-performing outlets and pinpoint underperforming locations[cite: 2].
- Identify items with zero visibility on digital storefronts requiring indexing fixes[cite: 2].
- Formulate practical strategic recommendations for management[cite: 2].

---

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Google Colab / Jupyter Notebook[cite: 1]

---

## 📁 Repository Structure

```text
├── BlinkIT_Grocery_Sales_Analysis.ipynb    # Google Colab Python Analysis Notebook
├── BlinkIT Grocery Data.xlsx                # Sales Dataset
├── BlinkIT Grocery Sales Analysis.pdf       # Project Requirements Document
└── README.md                                # Project Documentation
