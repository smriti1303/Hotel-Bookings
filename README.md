# Hotel-Bookings
# 🏨 Hotel Booking Cancellation Analysis

This project analyzes hotel booking data to uncover trends and insights related to guest behavior and cancellations. The visuals and data breakdown help stakeholders understand key patterns across different customer types, booking times, and hotel categories.

---

## 📊 Dashboard Overview

The analysis is visualized using a dashboard that includes:

- Pie Charts for **Total Bookings** and **Cancellations** by hotel type.
- Bar Charts comparing:
  - **Guest Type vs Cancellations**
  - **Booking Intent (Desired vs Undesired)**
  - **Monthly Booking Trends**
- KPI indicators:
  - Total Bookings: **119,390**
  - Total Cancellations: **44,244**

---

## 🗂️ Dataset Description

**Columns used:**

| Column              | Description                          |
|---------------------|--------------------------------------|
| `hotel`             | Hotel type: City or Resort           |
| `is_canceled`       | Booking cancellation status          |
| `lead_time`         | Number of days before arrival        |
| `arrival_date_year` | Booking arrival year (2015-2017)     |
| `customer_type`     | Guest category (e.g., Couples, Family)|
| `reservation_status`| Status of the reservation            |
| `arrival_date_month`| Month of booking arrival             |

---

## 📈 Key Insights

1. **Hotel Type:**
   - **City Hotels** received more bookings (38140) but also faced higher cancellations (15407).
   - **Resort Hotels** had fewer bookings and cancellations.

2. **Guest Type:**
   - **Couples** were the most frequent and had the most cancellations.
   - **Singles** and **Families** followed in volume.

3. **Booking Intent:**
   - Guests with **Desired** booking types had a higher cancellation rate.

4. **Monthly Trends:**
   - **April, May, and October** showed the highest total bookings.
   - Cancellations were fairly consistent across months, peaking in **June**.
  
## Acknowledgment
Dataset inspired by the Hotel Booking Demand dataset from Kaggle.

## Conclusion
These insights can help hotels optimize revenue management, implement stricter cancellation policies during peak seasons, and target guest types more effectively with personalized offers.


