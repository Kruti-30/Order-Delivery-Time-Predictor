# Order-Delivery-Time-Predictor

A machine learning-powered Streamlit web application that predicts the delivery time (in days) for e-commerce orders using the Olist dataset. This project helps logistics teams and customers anticipate delivery durations more accurately. Users input the payment value, purchase day of the week, and hour of purchase through an interactive Streamlit web app, which then provides a predicted delivery duration. The model was trained using features engineered from real order data, aiming to help e-commerce platforms improve logistics planning and customer satisfaction.

This project aims to:
- Predict the estimated delivery time of an online order.
- Visualize key order-related features such as shipping delays, product categories, and customer locations.
- Provide a simple user interface built with Streamlit.
- Deliver insights using a trained regression model on real-world data from [Olist e-commerce dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

## ⚙️ Features

- 🧠 Trained regression model (e.g., RandomForestRegressor or XGBoost)
- 📊 Real-time prediction based on order inputs
- 📍 Handles customer location, product weight, freight value, and shipping info
- 💡 Visual insights using Streamlit widgets and Matplotlib/Seaborn plots

