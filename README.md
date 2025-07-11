# E-commerce-Product-Delivery-Prediction

This project focuses on predicting whether an e-commerce product will be delivered **on time** or **late** using machine learning models. It is aimed at helping businesses **optimize logistics**, **enhance customer satisfaction**, and **gain operational insights**.

---

## 📌 Project Overview

An international e-commerce company specializing in electronic products wants to improve its delivery system. By analyzing historical order and delivery data, the goal is to build a model that accurately predicts the **delivery status** of new orders.

---

## 🎯 Objectives

- Predict if a product will be delivered on time or late.
- Identify key features affecting delivery delays.
- Compare performance of different classification models.
- Deploy a simple, interactive web app using **Streamlit**.

---

## 📁 Dataset

The dataset includes customer and product-related information such as:

- `Customer_rating`
- `Cost_of_the_Product`
- `Discount_offered`
- `Weight_in_gms`
- `Prior_purchases`
- `Reached_on_time` (Target variable)

> 🔗 *Dataset link:* [Insert your dataset link here]

---

## 🔍 Exploratory Data Analysis (EDA)

- Visualized feature distributions using histograms and boxplots.
- Identified outliers (e.g., in `Weight_in_gms` and `Discount_offered`).
- Analyzed delivery patterns by customer rating, prior purchases, and product cost.

---

## ⚙️ Feature Engineering

- Handled categorical variables with One-Hot Encoding.
- Normalized numerical features where needed.
- Created new features like discount-to-cost ratio, weight categories, etc.

---

## 🤖 Models Used

- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**

> 🔎 **Random Forest** performed best based on accuracy, ROC AUC, and confusion matrix.

---

## 📈 Model Evaluation

- **Confusion Matrix**, **Accuracy**, **Precision**, **Recall**, **F1-Score**
- **ROC AUC Curve** for all models
- Random Forest gave the best balance between **precision and recall**

---

## 🌲 Feature Importance (Random Forest)

Top influential features:
- `Discount_offered`
- `Weight_in_gms`
- `Cost_of_the_Product`

---

## 🌐 Model Deployment

The best-performing model was deployed using **Streamlit**.  
Users can input order details and receive a prediction instantly.

> 📸 *[Insert screenshot or Streamlit app link]*

---

## ✅ Key Findings

- High discounts are correlated with late deliveries.
- Heavier items are usually delivered on time (better packaging/shipping).
- Repeat customers and high product cost slightly improve on-time delivery rates.

---

## ⚠️ Limitations

- Limited to the features provided in the dataset.
- No external factors like weather, traffic, or location included.
- May not generalize well across all product types or seasonal variations.

---

## 🚀 Future Scope

- Include real-world data like location, shipping partner, and delivery distance.
- Use advanced models like **XGBoost** or **LightGBM**.
- Build real-time alerts for at-risk deliveries.
- Integrate with business dashboards for live decision support.

---

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)
- Matplotlib, Seaborn
- Streamlit
- Jupyter Notebook



