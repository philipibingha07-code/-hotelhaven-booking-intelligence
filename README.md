# -HotelHaven-booking-intelligence
##### Machine learning project analyzing 36K+ hotel bookings to predict cancellations and optimize revenue management.

### 📌 Project Overview
****Hotel cancellations significantly impact occupancy rates, staffing requirements, resource allocation, and revenue generation****.
  **This project analyzes hotel booking behavior and develops predictive models capable of identifying customers  cancelation  partners likely to cancel reservations**.
  **The objective is to enable hotels to make proactive business decisions that improve forecasting, customer retention, Reduce revenue leakage caused by last-minute cancellations. and Revenue growth**.

### 🎯 Business Problem
##### Unexpected booking cancellations create several operational challenges:

- Reduced occupancy rates
- Revenue leakage
- Inefficient staffing allocation
- Inventory management difficulties
- Inaccurate demand forecasting

| Metric                     | Value       |
| -------------------------- | ----------- |
| Total Bookings             | 36,285      |
| Cancellation Rate          | 32.7%       |
| Average Lead Time          | 57 Days     |
| Average Booking Value      | $103        |
| Average Adults per Booking | 1.84        |
| Online Reservations        | 64%         |
| Preferred Meal Plan        | Meal Plan 1 |

### 🔍 Key Insights
##### Cancellation Drivers
**Guests booking further in advance were significantly more likely to cancel**.
  **Less than 30 Days → Lowest cancellation rate, 90–180 Days → Cancellation begin and from 180–365 Days → High cancellation frequency and a high   cancellation tendency from a year and above**.   
- **Weeknight Stay Duration**: **longer stays correlate strongly with cancellation behavior with  0-3 night showing low trend and an increase       from 6-9 while the cancellation rate get to its peak from 10 nights and above**.
- **Weekend Stay Duration** **Extended weekend stays exhibited the highest risk**. 
    **Guests staying more than seven weekend nights displayed cancellation rates nearly three times above the overall average**.
  
### 💰 Revenue Optimization Recommendations
**Implement a Lead-Time-Based Deposit Policy
Cancellation risk rises sharply with lead time — low under 30 days, emerging between 90–180 days, and peaking beyond 180 days. Hotels should   require    no deposit under 30 days, a 20–25% deposit for 90–180 day bookings, and a larger deposit beyond 180 days. This protects revenue from the riskiest        segment while keeping reliable short-lead bookers friction-free. It also gives earlier visibility into which reservations will likely hold,        improving staffing and inventory forecasts**

- **Restrict Flexible Cancellation for Extended Stays
Cancellation risk climbs steeply with stay length — weeknight cancellations rise past 6 nights and peak past 10, while weekend stays beyond 7 nights cancel at nearly three times the average rate. Hotels should keep flexible terms only for short stays (0–3 nights) and apply stricter, partly non-refundable terms to longer stays. This targets the highest-risk segment without discouraging low-risk, high-volume bookings. It also opens a paid "flex rate" option for guests wanting full refundability, turning flexibility into a revenue lever**.

### ⚙️ Machine Learning Workflow
- Data Preprocessing
- Missing value treatment
- Feature Engineering
- Label Encoding
- StandardScaler
- SMOTE balancing

- Train-Test Split
- Training Set → 80%
- Testing Set → 20%
## Modeling Process
- Logistic Regression
- Random Forest
- XGBoost
- Model Evaluation
- 
### 🛠 Technology Stack
- Python
- Pandas
- NumPy
- Scikit-Learn
- SMOTE
- Matplotlib
- Seaborn
- Jupyter Notebook
- Machine Learning
- Predictive Analytic
### 📈 Business Impact
**Addressing the cancellation drivers identified in this analysis directly protects revenue and improves operational efficiency. With a 32.7% cancellation rate across 36,285 bookings at an average value of $103, unrealized revenue currently exceeds $1.2M in gross booking value. Even a modest reduction in cancellations among high-risk segments (long lead times, extended stays) would recover a meaningful share of this loss. Beyond revenue, more accurate cancellation forecasting allows hotels to align staffing and resource allocation with realistic occupancy rather than booked occupancy — cutting both overstaffing costs and last-minute service gaps. Together, these changes convert an unmanaged risk into a predictable, monetizable part of the booking process**.

### 📷 Project Visualizations
**Cancellation Rate by Lead Time**
<img width="673" height="349" alt="hotelheaven days" src="https://github.com/user-attachments/assets/152d7af7-a21b-439b-a8d0-f9c37b15e450" />
### Cancellation Rate by Weeknight Duration
**Longer stays displayed stronger cancellation tendencies.**<img width="583" height="324" alt="Hotelheaven post" src="https://github.com/user-attachments/assets/588cc13b-f5ef-45ce-9e90-7729d3b81883" />

### 🚀 Future Enhancements
- Deploy model using Streamlit
- Build interactive Tableau dashboard
- Hyperparameter tuning
- SHAP Explainability
- Real-time cancellation prediction API
- Recommendation Engine for meal package
- 
📬 Connect With Me

  #### Philip Ibingha
- 📧 philipibingha07@gmail.com
- 💼 www.linkedin.com/in/philip-ibingha-a296a5380
- 🐙 GitHub: Add your GitHub URL
