# 🚗 Uber Trip Analysis – Power BI Dashboard

This project presents an end-to-end **Power BI dashboard** analyzing Uber's trip data to uncover booking trends, revenue patterns, time-based demand, trip efficiency, and location-based insights. The dashboard is designed to support strategic decisions in ride-hailing operations.

---

## 📌 Project Objective

To provide a centralized analytics dashboard that enables:
- Operational efficiency through time-based demand forecasting
- Revenue optimization by analyzing trip and payment behavior
- Location-level planning through pickup/drop-off hotspot analysis
- Strategic vehicle placement based on customer booking patterns

---

## 🛠 Tools & Technologies

- **Power BI Desktop**
- **DAX** (Data Analysis Expressions)
- **Power Query**
- **Excel** (Trip & Location Data)
- **Bookmarks, Slicers, Tooltips, Drill-throughs**
- **Disconnected Table for Dynamic Measure Switching**

---

## 📊 Dashboards & KPIs

**Core KPIs Tracked:**
- **Total Bookings**
- **Total Booking Value** (Revenue)
- **Average Booking Value**
- **Total Trip Distance** and **Average Distance**
- **Average Trip Duration**
- **Top 5 Booking Locations**
- **Most Frequent Pickup and Drop-off Points**
- **Farthest Trip by Distance**

**Key Visual Features:**
- 🔄 **Dynamic Measure Selector** (Bookings, Revenue, Distance) using a disconnected table
- 📆 **Time-Based Analysis**: 10-minute interval area chart, day-of-week trends, and heatmap (Hour × Day)
- 🗺️ **Location Intelligence**: Pickup/drop-off frequency, preferred vehicle by location, and high-demand zones
- 🚘 **Vehicle Type KPI Matrix** with conditional formatting
- 🖱️ **Drill-through Functionality** to explore full trip-level records from summary views
- 🧰 **User-Friendly Tools**: slicers (City, Date, Trip Type, Payment Type), "Clear Filters" button, bookmarks, and data export

## 📈 Key Business Insights

- 🚀 **Peak demand periods** identified by 10-min pickup windows and weekday patterns
- 💳 **Wallet and card payments dominate** certain cities/times
- 🗺️ Top 5 **pickup and drop-off locations** reveal high-traffic hotspots
- 🚘 **Vehicle preferences vary by location**, optimizing fleet allocation
- 🕓 Heatmap visualizes **hourly booking surges** by day
- 🔁 Long trips and booking patterns help refine **fare models** and detect outliers

---

## 📁 Data Sources

- `Uber Trip Details.xlsx`: Booking, trip duration, distance, payment, vehicle, timestamp
- `Location Table.xlsx`: Mapping for pickup and drop-off areas
- Cleaned and modeled using **Power Query** with key relationships between **Trip ID**, **Location ID**, and **Vehicle Type**

---

## 📎 Advanced Features

- **Dynamic Measure Selector** via disconnected table for interactive metric switching
- **Bookmarks** for toggling views and resetting filters
- **Clear Filter Button** for full report reset
- **Download Button** for exporting raw data
- **Conditional formatting** to highlight high-performing metrics

---

## 🚀 Getting Started

1. Download or clone the repository
2. Open the <a href="https://github.com/HimXRaj/Uber-Trip-Analysis/blob/main/Uber/Uber%20DB.pbix">`Election.pbix`</a>file in Power BI Desktop
3. Refresh data if needed
4. Navigate via the **Landing Page** to explore dashboards

---

## 👤 Author

**Himanshu Rajput**  
🔗 [LinkedIn](https://www.linkedin.com/in/himxraj)  
📧 workfhimanshu@gmail.com

---

