# 🧹 Project 1 - Data Cleaning and Exploration

### 🏢 Project Context
The e-commerce company **Store 1** is preparing to launch a new **Customer Loyalty Program**.  
The goal is to analyze the existing customer database, ensure data quality, and prepare it for future marketing campaigns and business insights.

As a member of the analytics team, your initial task is to **review, clean, and transform the dataset** to make it ready for analysis.

---

### 🎯 Objectives
- Clean and validate customer profiles.  
- Standardize names, ages, and product categories.  
- Calculate total spending per customer.  
- Detect and correct inconsistencies in the dataset.  
- Prepare the cleaned data for key business metrics (**KPIs**).  

---

### 🧩 Data Description
The dataset comes from *Store 1* and is provided as a **Python list** with the following columns:

| Column | Description |
|----------|-------------|
| `user_id` | Unique identifier for each user. |
| `user_name` | Customer’s name. |
| `user_age` | Customer’s age. |
| `favorite_categories` | List of preferred product categories. |
| `spending_per_category` | List of total amounts spent per category. |

---

### 🧠 Sample Data
```python
users = [ 
    ['32415', ' mike_reed ', 32.0, ['ELECTRONICS', 'SPORTS', 'BOOKS'], [894, 213, 173]],
    ['31980', 'kate morgan', 24.0, ['CLOTHING', 'BOOKS'], [439, 390]],
    ['32156', ' john doe ', 37.0, ['ELECTRONICS', 'HOME', 'FOOD'], [459, 120, 99]],
]
