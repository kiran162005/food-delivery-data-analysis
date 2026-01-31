# Food Delivery Data Integration & Analysis

This project integrates food delivery data from multiple sources and performs
analysis to derive business insights.

---

## 📌 Overview

The project combines three datasets representing different data formats:

- Orders data (CSV)
- User data (JSON)
- Restaurant data (SQL)

These datasets are merged into a single unified dataset for analysis.

---

## 📂 Files

- **Food_Delivery_Data_Integration.ipynb**  
  Jupyter Notebook containing data loading, merging, and analysis.

- **final_food_delivery_dataset.csv**  
  Final merged dataset used for all analysis.

- **data/** *(optional)*  
  - orders.csv  
  - users.json  
  - restaurants.sql  

---

## 🔗 Data Integration

- **Base dataset:** Orders  
- **Join type:** Left Join  
- **Join keys:**
  - `user_id`
  - `restaurant_id`

---

## 📊 Analysis

The notebook includes analysis on:
- Revenue and order metrics
- User membership behavior
- City-wise and cuisine-wise performance
- Rating-based insights
- Time-based revenue trends

---

## 🛠 Tools Used

- Python
- Pandas
- SQLite
- Jupyter Notebook
