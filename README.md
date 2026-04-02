# 🪔 Diwali Sales Analysis

## 📌 Project Overview
Performed Exploratory Data Analysis (EDA) on 11,251 Diwali 
sales records to uncover customer buying patterns and help 
businesses improve sales strategy during the festive season.

---

## 📊 Dataset Summary
- **Rows:** 11,251 | **Columns:** 15 (cleaned to 13)
- **Key Features:** Customer demographics, purchase amount, 
  state, zone, occupation, product category, orders
- **Data Cleaning:**
  - Dropped 2 fully empty columns: `Status` and `unnamed1`
  - Removed 12 null values from `Amount` column using `dropna()`
  - Converted `Amount` from float64 to int64

---

## 🛠 Tools & Libraries
| Tool | Usage |
|------|-------|
| Python | Core programming |
| Pandas | Data cleaning & manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualizations |

---

## 🔧 Data Processing Steps
- Loaded CSV with `unicode_escape` encoding
- Checked structure using `df.info()` and `df.describe()`
- Dropped irrelevant empty columns
- Handled null values with `dropna()`
- Changed `Amount` dtype: `float64` → `int64`
- Used `df.rename()` for column standardization

---

## 📈 EDA Sections & Key Insights

### 👤 Gender Analysis
- **7,832 Female** buyers vs **3,407 Male** buyers
- Females generated **₹74.3M** in revenue vs Males **₹31.9M**
- ✅ **Conclusion:** Most buyers are female with higher purchasing power

### 🎂 Age Group Analysis
- **26-35 age group** dominates both in count and total spending
- Females in 26-35 are the single largest buying segment
- ✅ **Conclusion:** Age group 26-35, mostly female, are the primary buyers

### 🗺 State Analysis
- **Top 3 states by orders:** Uttar Pradesh, Maharashtra, Karnataka
- **Top 3 states by revenue:** Uttar Pradesh, Maharashtra, Karnataka
- ✅ **Conclusion:** UP, Maharashtra & Karnataka drive the most sales

### 💍 Marital Status Analysis
- **6,518 unmarried** vs **4,721 married** customers
- Married women show the **highest purchasing power**
- ✅ **Conclusion:** Married women are the most valuable customer segment

### 💼 Occupation Analysis
- Top buying occupations: **IT Sector, Healthcare, Aviation**
- IT Sector employees contribute the highest revenue
- ✅ **Conclusion:** Professionals from IT, Healthcare & Aviation buy the most

### 🛍 Product Category Analysis
- **Top categories by orders:** Food, Clothing & Apparel, 
  Electronics & Gadgets
- **Top categories by revenue:** Food, Clothing & Apparel, 
  Electronics & Gadgets
- ✅ **Conclusion:** Food, Clothing and Electronics are the top-selling categories

---

## 🎯 Final Business Conclusion
> **Married women aged 26-35 from Uttar Pradesh, Maharashtra 
> and Karnataka, working in IT Sector, Healthcare & Aviation, 
> are most likely to purchase Food, Clothing & Electronics 
> during Diwali.**

---

## 💡 Business Recommendations
- **Target married women (26-35)** with personalized festive offers
- **Focus ad campaigns** on UP, Maharashtra & Karnataka regions
- **Bundle Food + Electronics + Clothing** in Diwali combo deals
- **Partner with IT & Healthcare companies** for corporate gifting
- **Increase inventory** for Food, Clothing & Electronics before Diwali

---

## 👤 Author
**Aditya Kumar**  
Data Analyst | [GitHub](https://github.com/adityak024)
