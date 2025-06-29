# Hotel Booking Data Analysis and Cancellation Predictions

This project predicts whether a hotel booking will be canceled, enabling hotels to improve booking management, reduce revenue loss, and enhance customer retention. By leveraging machine learning and exploratory data analysis, we identify key patterns in booking behavior and build robust classification models.

---

## Dataset

- **Source**: https://www.kaggle.com/code/farzadnekouei/hotel-booking-cancellation-prediction/input
- **Rows/Columns**: ~119,000 records × 32 features
- Contains data from a **resort** and a **city hotel**, with features related to customer demographics, stay duration, booking channel, special requests, and cancellation status.

---

## Problem Statement

Hotel cancellations disrupt operations and affect revenue. The goal is to build a predictive model to classify whether a booking will be canceled, so hotels can proactively manage inventory and overbooking strategies.

---

## Tools & Technologies Used

- **Python** (Pandas, NumPy)
- **Data Visualization**: Seaborn, Matplotlib
- **Machine Learning**: Scikit-learn, XGBoost
- **Model Evaluation**: F1 Score, Confusion Matrix, Classification Report

---

## Exploratory Data Analysis (EDA)

- Analyzed distributions, correlations, and booking trends across hotel types and time.
- Found key drivers of cancellations such as **lead time**, **deposit type**, **previous cancellations**, and **special requests**.
- Addressed **missing values** and **class imbalance** using appropriate preprocessing techniques.

---

## Model Development

- Applied feature engineering to improve predictive power.
- Built and compared multiple classification models:
  - Decision Tree
  - Random Forest
  - **XGBoost** (best-performing)
- Used **F1 score** as the primary evaluation metric due to class imbalance.

**Best Performance**:  
- **Model**: XGBoost  
- **F1 Score**: `0.79`  
- **Accuracy**: `85.04%`  

---

## Evaluation Metrics

- **F1 Score** (primary metric)
- Precision & Recall
- Confusion Matrix
- Classification Report
- ROC Curve (optional)

---

## Key Insights

- High **lead time** and **no special requests** are strong indicators of cancellations.
- **City hotel** bookings tend to have higher cancellation rates than resort hotel bookings.
- Certain booking channels and deposit types are more prone to cancellation.

---


