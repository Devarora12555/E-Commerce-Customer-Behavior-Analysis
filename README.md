# E-Commerce-Customer-Behavior-Analysis
# 🛒 E-Commerce Customer Behavior Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3.0-red)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11.0-lightblue)

## 📌 Actual Project Details (From PDF)
Exploratory Data Analysis of **550,068 customer records** from an e-commerce platform featuring:

- Customer demographics (Age/Gender/City)
- Purchase history across 20 product categories 
- Spending patterns analysis
- Missing value treatment

## 🔍 Key Features from PDF
```python
import pandas as pd
df = pd.read_csv('Product.csv') # Contains:
# User_ID, Product_ID, Gender, Age, Occupation
# City_Category, Purchase (₹5823-₹23961 range)
# Product_Category_1-3, Marital_Status
Analysis Performed (PDF Content)
Data Cleaning:

Dropped empty 'New' column

Handled NaN values in Product_Category_2/3

Gender encoding (F=0, M=1)

Statistical Analysis:

df.describe() showed mean purchase ₹9263

Product_Category_1 (Most frequent: 5)

Age groups: '0-17' to '55+'

Visualizations (To Add):

Age vs Purchase distribution

City-wise spending heatmap

Product category preferences

🚀 How to Run
bash
git clone https://github.com/Devarora12555/E-Commerce-Customer-Behavior-EDA.git
jupyter notebook Ecommerce_Analysis.ipynb
Why this name?
The PDF shows retail data (Product.csv) with:

Purchase amounts (₹)

Product categories

No telecom-specific fields

Typical e-commerce attributes (User_ID, Product_ID)

Alternative names:

Retail-Customer-Analytics-EDA

E-Commerce-Purchase-Patterns

Product-Sales-Data-Exploration

Want me to modify any part of this? The PDF clearly shows this is retail/e-commerce data analysis, not telecom. 😊

New chat
