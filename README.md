# 🚕 UBER Rides: End-to-End Analytics for Enhancing Ride-Booking Efficiency 🛠️

Welcome to the **Ride Booking Data Analysis Project**! This project analyzes a **real-world dataset** from a ride-booking platform, showcasing **data cleaning**, **exploratory data analysis (EDA)**, and the creation of an interactive **Power BI dashboard** to provide actionable insights for solving real-world business problems. 🚀

---
<div style="text-align: center;">
    <img src="image.png" alt="alt text" width="600" height="130">
</div>

## 🌟 Project Overview
The goal of this project is to:
- 🧹 Clean 50000+ rows raw ride-booking data using **Python** and **Excel**.
- 📊 Perform in-depth exploratory data analysis (EDA) using **SQL**.
- 📈 Visualize key metrics and trends using **Power BI Dashboards**.
- 💡 Solve real-world business problems with **data-driven insights**.

## 🛠 **Tech Stack Overview**
- **Excel**: Initial data inspection and preparation.
- **Python 🐍**: Data cleaning and preprocessing.
- **SQL 🗃️**: EDA and advanced query analysis using PostgreSQL.
- **Power Query**: ETL (Extract, Transform, Load) for Power BI integration and new measures calculation.
- **Power BI 📊**: Interactive dashboards for data visualization and reporting.


<div style="text-align: center;">
    <img src="uber power bi.jpg" alt="alt text">
</div>

<!-- 👉 **[Explore the Dashboard Here](https://app.powerbi.com/view?r=eyJrIjoiYzA5ODVmZmItYTkxMi00NmEzLTgwNmItZjhhMGIwOGNmY2IzIiwidCI6ImE4ZWVjMjgxLWFhYTMtNGRhZS1hYzliLTlhMzk4YjkyMTVlNyIsImMiOjN9&pageName=8d6b3ce8e13d3a7f99b3)** -->

---

## 🛠️ Real-World Problems Solved
### **1. Dynamic Surge Pricing 💸**
- **Problem**: How to adjust pricing dynamically in high-demand areas?
- **Solution**: Identified high-demand pickup locations using SQL and suggested surge multipliers to balance supply and demand.

### **2. Customer Compensation for Delays 🤝**
- **Problem**: How to maintain customer trust when rides are delayed?
- **Solution**: Automatically flagged delayed rides and allocated compensation using SQL procedures.

### **3. Driver Notification for Long-Distance Rides 🚗**
- **Problem**: How to reduce cancellations for long-distance rides?
- **Solution**: Developed SQL procedures to notify drivers of long trips, ensuring preparedness.

### **4. Revenue Insights 💰**
- **Problem**: How to identify profitable customers and locations?
- **Solution**: Power BI dashboards showcased revenue trends by location, vehicle type, and payment methods.

---

## 📊 Key Insights
1. **🚀 Top Pickup Locations**:
   - Boston, Cambridge, and Worcester are high-demand areas.
   - **Actionable Insight**: Deploy more drivers to these locations.

2. **⏰ Peak Booking Hours**:
   - Most bookings occur between **5 PM - 8 PM**.
   - **Actionable Insight**: Increase driver availability during these hours.

3. **❌ Cancellation Analysis**:
   - **Customer Reasons**: "Change of plans" and "Driver asked to cancel."
   - **Driver Reasons**: "Vehicle issues" and "Customer was unavailable."
   - **Actionable Insight**: Improve driver training and enhance communication with customers.

4. **💸 Revenue Trends**:
   - Higher revenue on **weekends** and for **premium vehicle types (SUVs)**.
   - **Actionable Insight**: Focus marketing efforts on weekends and premium rides.

---

## 🗂️ Dataset Overview
The dataset contains **ride booking information** for a month in Massachusetts, with details on:
- **📅 Dates & 🕒 Times**
- **📄 Booking IDs & ✅ Status**
- **🚗 Vehicle Types & 📍 Locations (Pickup & Drop)**
- **📏 Ride Metrics** (e.g., distance, value, ratings)
- **👤 Customer and Driver Details**

---

## 🔧 Tools & Technologies Used

---

### **1. Python Data Cleaning**
- **Libraries Used**:
  - `pandas`: For data wrangling and manipulation.
  - `numpy`: For statistical computations.
- **Key Steps**:
  - ✅ Replaced null values with meaningful defaults (e.g., averages).
  - ✅ Removed duplicates to ensure clean and reliable data.
  - ✅ Exported the cleaned dataset as a `.csv` for SQL and Power BI analysis.

---

### **2. SQL Analysis**
- **Database**: PostgreSQL
- **Key Queries**:
  - 🚦 **Running Totals**: Calculated cumulative revenue by date.
  - 📈 **Aggregations**: Analyzed booking trends by location, vehicle type, and time.
  - ❌ **Cancellations Analysis**: Identified top cancellation reasons for both customers and drivers.
  - 📊 **Ranking**: Ranked top-performing locations and drivers.

---

### **3. Power BI Dashboards**
📊 **Interactive Dashboards** were created to provide a clear visualization of key metrics and trends. Here's an overview of the pages:

#### **Page 1: Overall 🚀**
- **Breakdown by Booking Status** 🟢🔵🔴
- **Total Bookings** 📄
- **Total Booking Value** 💰
- **Peak Booking Hours** ⏰
- **Number of Bookings Over Time** 📈
- **Date Slicer** 📅

#### **Page 2: Vehicle 🚗**
- Total Booking Value 💵
- Success Booking Value ✅
- Total Distance Travelled 📏
- Average Distance Travelled 📊
- Breakdown by Vehicle Type 🚙 🚴 🚐

#### **Page 3: Revenue 💸**
- Revenue by Payment Methods 💳
- Revenue by Pickup Location 📍
- Top 5 Customers 👤
- Date Trends 📆

#### **Page 4: Cancellations ❌**
- **Cancelled Rides by Drivers** 🧑‍✈️
- **Cancelled Rides by Customers** 👤
- **Cancellation Rate (%)** 📉
- **Total Cancellations vs. Total Bookings** 📊
- Date Trends 📅

#### **Page 5: Ratings ⭐**
- **Average VTAT (Vehicle Arrival Time)** ⏱️
- **Average CTAT (Customer Arrival Time)** ⏱️
- **Average Ratings** 🌟
- **Customer & Driver Ratings by Vehicle Type** 🚙👤

---

## 🚀 Future Enhancements
1. **Integrate Machine Learning**:
   - Predict cancellations 🧠.
   - Forecast revenue trends 📊.
   - Optimize resource allocation based on demand.

2. **Advanced API Integration**:
   - Automate surge pricing recommendations 💸.
   - Real-time data fetching for live dashboards 🚦.

3. **Enhanced Visualization**:
   - Add heatmaps for ride density 📍.
   - Interactive drill-downs for customer and driver analytics 🔍.

---

## 🎯 Conclusion
This project demonstrates how combining **Excel**, **Python**, **SQL**, and **Power BI** can unlock valuable insights, optimize business processes, and solve real-world problems in the ride-booking industry. 🚕💡

---
