# Food Delivery Data Analysis

## 📌 Project Overview
This project focuses on analyzing a food delivery dataset by combining data from multiple sources.  
The goal is to create a single, reliable dataset that can be used to study user behavior, revenue trends, and restaurant performance.

---

## 📂 Datasets Used
The following datasets were provided in different formats to simulate real-world systems:

- **orders.csv** – Transactional order data  
- **users.json** – User master data  
- **restaurants.sql** – Restaurant master data (cuisine and ratings)

---

## 🔗 Data Integration Logic
The datasets were merged using **LEFT JOINs** to ensure all orders are retained.

### Join Keys:
- `orders.user_id` → `users.user_id`
- `orders.restaurant_id` → `restaurants.restaurant_id`

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- SQLite  
- Jupyter Notebook  

---

## 📊 Output
The final merged dataset is saved as:
- **final_food_delivery_dataset.csv**

This dataset is used for analytical tasks such as:
- Revenue analysis  
- User behavior analysis  
- City-wise and cuisine-wise performance  

---

## 📁 Repository Contents
- `food_delivery_analysis.ipynb` – Jupyter Notebook with data loading and merge logic  
- `README.md` – Project documentation  

---

## ✅ Notes
- The repository is public and accessible.
- The Jupyter Notebook opens correctly on GitHub.
- The analysis follows the instructions provided in the problem statement.

