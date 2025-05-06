# 📦 LR_Delivery_Time_Prediction_Jyoti_Mitkar

A linear regression-based machine learning project to predict delivery times for a food delivery platform. The goal is to identify key factors affecting delivery time and generate actionable insights to improve operational efficiency.

---

## 🧠 Project Objective

To develop and evaluate a **Linear Regression** model that accurately predicts delivery time based on operational and order-related features, and to interpret which factors increase or reduce delivery delays.

---

## 📊 Data Summary

This dataset encompasses detailed information about food delivery orders, capturing various aspects from order placement to delivery fulfillment. It serves as a foundation for analyzing delivery times and understanding factors influencing them.

### 🔑 Key Features

- **market_id**: Unique identifier for the market or region where the restaurant operates.  
- **created_at**: Timestamp indicating when the order was placed.  
- **actual_delivery_time**: Timestamp indicating when the order was delivered to the customer.  
- **store_primary_category**: Primary category of the restaurant (e.g., fast food, dine-in).  
- **order_protocol**: Integer denoting how the order was placed (e.g., via app, phone call).  
- **total_items**: Total number of items included in the order.  
- **subtotal**: Final price of the order in cents.  
- **num_distinct_items**: Number of unique items in the order.  
- **min_item_price**: Price of the cheapest item in the order (in cents).  
- **max_item_price**: Price of the most expensive item in the order (in cents).  
- **total_onshift_dashers**: Number of delivery partners available at the time the order was placed.  
- **total_busy_dashers**: Number of delivery partners currently occupied with other orders.  
- **total_outstanding_orders**: Number of orders pending fulfillment at the time of the order.  
- **distance**: Estimated distance from the restaurant to the customer (in miles).  

---

## 🔄 Data Pipeline

The data pipeline for this project encompasses the following sequential steps to ensure efficient data processing and model development:

1. **Data Loading**  
   Import raw data from source files into the working environment for analysis.

2. **Data Preprocessing and Feature Engineering**  
   Clean and transform the data by handling missing values, encoding categorical variables, and creating new features to enhance model performance.

3. **Exploratory Data Analysis (EDA)**  
   Conduct statistical analyses and visualizations to understand data distributions, identify patterns, and detect anomalies or outliers.

4. **Model Building**  
   Develop predictive models using appropriate algorithms, tuning hyperparameters to optimize performance.

5. **Model Inference**  
   Apply the trained model to new, unseen data to make predictions and assess its generalization capabilities.

---

## 📬 Contact

**Jyoti Mitkar**  
📧 [LinkedIn](https://www.linkedin.com/in/jyoti-patil-9808067a/) <!-- Replace '#' with your actual LinkedIn profile URL -->
