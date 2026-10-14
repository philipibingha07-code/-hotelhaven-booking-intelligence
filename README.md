# 🏨 HotelHaven Booking Intelligence

### Predicting Hotel Cancellations to Protect Revenue and Improve Occupancy Planning

<p align="center">

**36,285+ Bookings**   |   **32.7% Cancellation Rate**   |   **$1.2M+ Potential Revenue Exposure**   |   **Machine Learning**

</p>

---

## 📌 Project Overview

HotelHaven Booking Intelligence is an end-to-end **machine learning and predictive analytics project** analyzing more than **36,000 hotel bookings** to understand cancellation behavior and identify opportunities to reduce revenue leakage.

The project combines **data cleaning, exploratory data analysis, feature engineering, machine learning, and business recommendations** to help hotels identify high-risk reservations before cancellation occurs.

The objective is to enable hotels to make proactive decisions that improve:

* 💰 Revenue protection
* 🏨 Occupancy planning
* 📊 Demand forecasting
* 👥 Staffing allocation
* 🎯 Customer retention
* 📦 Inventory management

---

## 🎯 Business Problem

Unexpected booking cancellations create several operational and financial challenges:

* Reduced occupancy rates
* Revenue leakage
* Inefficient staffing allocation
* Inventory management difficulties
* Inaccurate demand forecasting

### Key Business Question

> **Can historical booking behavior be used to identify customers who are more likely to cancel and help hotels take proactive action?**
---
## 📊 Project at a Glance

| KPI                                       |          Result |
| :---------------------------------------- | --------------: |
| **Total Bookings**                        |      **36,285** |
| **Cancellation Rate**                     |       **32.7%** |
| **Average Lead Time**                     |     **57 Days** |
| **Average Booking Value**                 |        **$103** |
| **Average Adults per Booking**            |        **1.84** |
| **Online Reservations**                   |         **64%** |
| **Preferred Meal Plan**                   | **Meal Plan 1** |
| **Estimated Gross Booking Value at Risk** |      **$1.2M+** |

---

# 🔎 Key Business Insights

## 📅 1. Lead Time Is a Major Cancellation Driver

Guests booking further in advance were significantly more likely to cancel.

| Lead Time        | Cancellation Behavior          |
| :--------------- | :----------------------------- |
| **< 30 Days**    | Lowest cancellation rate       |
| **90–180 Days**  | Cancellation begins increasing |
| **180–365 Days** | High cancellation frequency    |
| **1 Year+**      | High cancellation tendency     |

**Business implication:** Long-lead reservations should receive additional risk controls.

---

## 🌙 2. Longer Weeknight Stays Have Higher Cancellation Risk

Longer stays correlate strongly with cancellation behavior.

* **0–3 nights** → Low trend
* **6–9 nights** → Cancellation rate increases
* **10+ nights** → Cancellation rate reaches its peak

**Business implication:** Extended reservations require stronger cancellation controls.

---

## 🌅 3. Extended Weekend Stays Are High Risk

Guests staying more than **seven weekend nights displayed cancellation rates nearly three times above the overall average**.

**Business implication:** Hotels can introduce differentiated cancellation policies for extended weekend reservations.

---

## ⚙️ Machine Learning Workflow

### Data Preprocessing

* Data preprocessing
* Missing value treatment
* Feature engineering
* Label encoding
* StandardScaler
* SMOTE balancing

---

## 🧠 Models Evaluated

* Logistic Regression
* Random Forest
* Gradient Boosting

---

## 🏆 Model Performance

| Model             | Accuracy | Precision (Class 0) | Recall (Class 0) | F1 (Class 0) | Precision (Class 1) | Recall (Class 1) | F1 (Class 1) |
| :---------------- | -------: | ------------------: | ---------------: | -----------: | ------------------: | ---------------: | -----------: |
| **Random Forest** |  **90%** |             **91%** |          **89%** |      **90%** |             **89%** |          **91%** |      **90%** |
| Gradient Boosting |      83% |                 85% |              80% |          82% |                 80% |              85% |          83% |

### 🥇 Best Performing Model

**Random Forest achieved the strongest performance among the models reported, reaching 90% accuracy and a 0.90 F1-score for both classes.**

The model demonstrated balanced precision and recall across both classes, providing a strong foundation for identifying customers who are likely to cancel.

### Random Forest Classification Report

```text
              precision    recall  f1-score   support

           0       0.91      0.89      0.90      4785
           1       0.89      0.91      0.90      4669

    accuracy                           0.90      9454
   macro avg       0.90      0.90      0.90      9454
weighted avg       0.90      0.90      0.90      9454
```

### Gradient Boosting Classification Report

```text
              precision    recall  f1-score   support

           0       0.85      0.80      0.82      4785
           1       0.80      0.85      0.83      4669

    accuracy                           0.83      9454
   macro avg       0.83      0.83      0.83      9454
weighted avg       0.83      0.83      0.83      9454
```

---

# 💰 Revenue Optimization Recommendations

## 1. Lead-Time-Based Deposit Policy

Cancellation risk rises sharply with lead time — low under 30 days, emerging between 90–180 days, and peaking beyond 180 days.

Hotels should consider:

* **No deposit** under 30 days
* **20–25% deposit** for 90–180 day bookings
* **Larger deposit** beyond 180 days

This protects revenue from the riskiest segment while keeping reliable short-lead bookers friction-free.

---

## 2. Restrict Flexible Cancellation for Extended Stays

Cancellation risk climbs steeply with stay length.

Hotels should keep flexible terms primarily for short stays **(0–3 nights)** and apply stricter, partly non-refundable terms to longer stays.

A paid **"flex rate"** could also provide guests with full refundability while turning flexibility into an additional revenue opportunity.

---

# 📈 Business Impact

With a **32.7% cancellation rate across 36,285 bookings at an average value of $103**, unrealized revenue currently exceeds **$1.2M in gross booking value**.

Even a modest reduction in cancellations among high-risk segments could recover a meaningful share of this potential revenue.

More accurate cancellation forecasting can also help hotels:

* Improve occupancy forecasting
* Optimize staffing levels
* Improve inventory allocation
* Reduce last-minute service gaps
* Identify high-risk bookings earlier
* Protect revenue from avoidable cancellations

### 💡 Business Value

> **The project converts cancellation behavior from an unmanaged operational risk into a measurable and predictable revenue-management opportunity.**

---

# 📊 Project Visualizations

## Cancellation Rate by Lead Time

<img width="673" height="349" alt="HotelHaven cancellation rate by lead time" src="https://github.com/user-attachments/assets/152d7af7-a21b-439b-a8d0-f9c37b15e450" />

---

## Cancellation Rate by Weeknight Duration

**Longer stays displayed stronger cancellation tendencies.**

<img width="583" height="324" alt="HotelHaven cancellation rate by weeknight duration" src="https://github.com/user-attachments/assets/588cc13b-f5ef-45ce-9e90-7729d3b81883" />

---

# 🛠️ Technical Skills & Tools

| Technology              | Purpose                            |
| :---------------------- | :--------------------------------- |
| 🐍 **Python**           | Core analysis and machine learning |
| 🐼 **Pandas**           | Data manipulation and analysis     |
| 🔢 **NumPy**            | Numerical analysis                 |
| 🤖 **Scikit-Learn**     | Machine learning                   |
| ⚖️ **SMOTE**            | Class imbalance handling           |
| 📊 **Matplotlib**       | Data visualization                 |
| 📈 **Seaborn**          | Statistical visualization          |
| 📓 **Jupyter Notebook** | Development environment            |

### Skills Demonstrated

**Data Analytics · Machine Learning · Predictive Analytics · Feature Engineering · Data Cleaning · EDA · Classification · Business Intelligence · Revenue Analytics · Business Recommendations**

---

# 🚀 Future Enhancements

* Deploy model using Streamlit
* Build interactive Tableau dashboard
* Hyperparameter tuning
* SHAP Explainability
* Real-time cancellation prediction API
* Recommendation Engine for meal package

---

# ⭐ Why This Project Matters

This project demonstrates the ability to move beyond building a machine learning model and connect:

**Data → Prediction → Business Decision → Financial Impact**

The project combines technical machine learning capability with **business-oriented problem solving and revenue optimization**.

| Capability                | Demonstrated |
| :------------------------ | :----------: |
| Python                    |       ✅      |
| Pandas / NumPy            |       ✅      |
| Data Cleaning             |       ✅      |
| Exploratory Data Analysis |       ✅      |
| Feature Engineering       |       ✅      |
| Machine Learning          |       ✅      |
| Classification            |       ✅      |
| SMOTE                     |       ✅      |
| Business Analysis         |       ✅      |
| Revenue Optimization      |       ✅      |
| Data Storytelling         |       ✅      |
| Business Recommendations  |       ✅      |
---
# 👤 About the Author

## Philip Ibingha

**Data Scientist | Predictive Analytics & Machine Learning**

I use data analytics and machine learning to transform complex datasets into **actionable business insights, predictive solutions, and measurable opportunities for growth.**
---
## 📬 Connect With Me

**Philip Ibingha**

**Data Scientist | Predictive Analytics & Machine Learning**

* 📧 **[philipibingha07@gmail.com](mailto:philipibingha07@gmail.com)**
* 💼 **LinkedIn:** [www.linkedin.com/in/philip-ibingha-a296a5380](http://www.linkedin.com/in/philip-ibingha-a296a5380)
* 🐙 **GitHub:** Add your GitHub URL
