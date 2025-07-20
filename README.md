# 🚀 PySpark Mini Project: Joins & Aggregations

This project demonstrates how to use PySpark for performing joins and aggregations on two small datasets: `orders_df` and `products_df`.

---

## 📂 Datasets

1. **Orders**
   - `order_id`
   - `customer_id`
   - `product_id`
   - `quantity`
   - `order_date`

2. **Products**
   - `product_id`
   - `product_name`
   - `price`
   - `category`

---

## 🔧 Objectives & Tasks

### ✅ 1. Create DataFrames
Created Spark DataFrames from sample `orders_df` and `products_df` data.

### ✅ 2. Inner Join between Orders & Products
Performed an inner join on `product_id` to combine order info with product names.

### ✅ 3. Total Revenue per Product
Calculated revenue as `quantity * price` and grouped by product.

### ✅ 4. Most Popular Product
Identified the product with the highest total quantity sold.

### ✅ 5. Total Revenue per Customer
Grouped orders by `customer_id` and calculated their total spending.

### ✅ 6. Left Join: All Products (Even if Not Ordered)
Performed a left join to display all products, including those with no orders.

---

## 🛠 Technologies Used

- Python 🐍  
- PySpark 🔥  
- Jupyter Notebook 📓  

---
 
