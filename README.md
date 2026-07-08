# 🚖 Uber Business Intelligence Dashboard

> An end-to-end Business Intelligence solution built using **Power BI** to analyze over **103K Uber trip records**, providing actionable insights into booking trends, revenue, customer demand, vehicle performance, and operational efficiency.

---

# 📌 Project Overview

The Uber Business Intelligence Dashboard was developed to help stakeholders monitor business performance through interactive visualizations and KPI reporting.

The dashboard transforms raw trip-level data into meaningful insights that support operational planning, demand forecasting, pricing strategies, and customer behavior analysis.

This solution demonstrates the complete Business Intelligence workflow, including data transformation, data modeling, DAX calculations, interactive dashboard design, and business insight generation.

---

# 🎯 Business Problem

Uber generates thousands of trip records every day, making it difficult for business users to identify booking trends, monitor operational performance, and make data-driven decisions using raw data alone.

The objective of this project is to build an interactive Power BI dashboard that enables stakeholders to:

- Monitor booking performance
- Track revenue and operational KPIs
- Analyze trip efficiency
- Identify peak booking periods
- Understand customer demand by location and time
- Compare vehicle performance
- Support strategic business decisions

---

# 🎯 Project Objectives

- Analyze booking trends across different time periods
- Monitor business KPIs through interactive dashboards
- Evaluate trip distance and duration
- Identify high-demand pickup and drop-off locations
- Compare vehicle category performance
- Analyze booking behavior by payment method
- Detect peak demand hours for resource planning
- Improve decision-making using Business Intelligence

---

# 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| BI Tool | Power BI Desktop |
| Data Transformation | Power Query |
| Data Modeling | Star Schema |
| Language | DAX |
| Visualization | Power BI |
| Concepts | KPI Reporting, Business Intelligence, Interactive Dashboards, Drill-through, Bookmarks |

---

# 📊 Dataset

| Attribute | Details |
|-----------|---------|
| Dataset | Uber Trip Records |
| Total Records | 103,728+ |
| Data Type | Ride Booking Data |
| File Format | CSV / Excel |
| Reporting Tool | Power BI |

---

# 📈 Dashboard Pages

## 1️⃣ Overview Dashboard

Provides an executive summary of Uber business performance.

### KPIs

- Total Bookings
- Total Booking Value
- Total Trip Distance
- Average Trip Time
- Average Trip Distance
- Average Booking Value

### Overview Analysis

- Booking Trends
- Revenue Performance
- Vehicle Type Analysis
- Payment Method Analysis
- Pickup & Drop Location Analysis
- Top 5 Booking Locations
- Longest Trip (Farthest Trip) Info.

---

## 2️⃣ Time Analysis Dashboard

Analyzes customer demand over time.

### Analysis Includes

- Booking trends by 10-minute intervals
- Booking trends by weekday/Day Name
- Booking trends by hour
- Hour × Day Heatmap
- Peak demand periods

Business users can quickly identify high-demand hours for better driver allocation and pricing strategies.

---

## 3️⃣ Details Dashboard

Provides transaction-level analysis through drill-through functionality.

Features include:

- Detailed booking records
- Dynamic filtering
- Drill-through navigation
- Bookmark navigation
- Full data exploration

---

# ⭐ Key Features

- Interactive KPI Dashboard
- Dynamic Measure Selector
- Dynamic Chart Titles
- Drill-through Reports
- Bookmarks
- Interactive Slicers
- Matrix Heatmap
- Conditional Formatting
- Vehicle Performance Analysis
- Location Analysis
- Time-based Analysis

---

# 🧠 Data Model

The dashboard follows a **Star Schema** to improve query performance and simplify analytical reporting.

## Fact Table

### Uber Trips

Contains transactional ride information including:

- Booking ID
- Booking Value
- Trip Distance
- Trip Duration
- Pickup Location
- Drop Location
- Vehicle Type
- Payment Type
- Booking Date

## Dimension Tables

### Date

- Date
- Month
- Quarter
- Year
- Weekday
- Hour



Using a dimensional model improves report scalability, performance, and filter propagation.

---

# 📐 DAX Highlights

The dashboard makes extensive use of DAX for KPI calculations and dynamic reporting.

### Measures Created

- Total Bookings
- Total Booking Value
- Average Booking Value
- Total Trip Distance
- Average Trip Distance
- Average Trip Time

### DAX Functions Used

- CALCULATE()
- SUM()
- COUNTROWS()
- AVERAGE()
- DIVIDE()
- SWITCH()
- SELECTEDVALUE()
- FILTER()
- ALL()

### Advanced Techniques

- Dynamic Measure Selection
- Dynamic Titles
- Disconnected Table
- Drill-through
- Filter Context
- Context Transition

---

# 📊 Business Insights

### 🚖 Booking & Demand Analysis

- **Saturday recorded the highest booking volume with 18,663 trips**, indicating significantly higher weekend demand and the need for increased driver availability.
- **3:00 PM was the busiest booking hour with 7,908 trips**, highlighting peak demand during afternoon hours and supporting dynamic pricing and workforce planning.
- **4:00 AM recorded the lowest booking volume with only 331 trips**, representing off-peak demand and potential opportunities to optimize driver scheduling.

### 🚘 Vehicle Performance

- **UberX emerged as the most preferred vehicle category**, generating the highest number of bookings as well as the highest booking revenue, making it the primary contributor to overall business performance.
- Customer preference for **UberX** indicates strong demand for cost-effective ride options compared to premium vehicle categories.

### 💳 Payment Analysis

- **Uber Pay was the most frequently used payment method**, demonstrating a strong customer preference for digital payments and supporting opportunities for targeted cashback and loyalty programs.

### 📍 Location Analysis

- **Pickup Location ID 186 recorded the highest booking volume**, identifying it as a key demand hotspot for driver allocation and fleet optimization.
- The **longest recorded trip covered 144.1 km from Pickup Location ID 148 to Drop-off Location ID 61**, highlighting long-distance travel patterns that can be evaluated for pricing and operational efficiency.

### 💰 Revenue & Trip Performance

- The **highest recorded booking fare was 563.79**, representing premium-value trips that contribute significantly to revenue despite lower booking frequency.
- The **average trip duration of 15.86 minutes** indicates that most Uber trips are short to medium-distance journeys, supporting efficient vehicle utilization and faster trip turnover.
---

# 💼 Business Recommendations

Based on the analysis, the following recommendations can improve operational efficiency and customer satisfaction:

- Increase driver availability during peak booking hours.
- Optimize fleet distribution around high-demand pickup locations.
- Use demand trends to support dynamic pricing strategies.
- Promote underutilized vehicle categories through targeted offers.
- Monitor payment preferences to encourage digital transactions.
- Analyze long-distance trips for fare optimization.
- Continuously monitor booking trends for demand forecasting and workforce planning.

---

# 🚀 Skills Demonstrated

- Business Intelligence
- Power BI
- Dashboard Development
- Data Visualization
- Data Analysis
- KPI Reporting
- Data Modeling
- Star Schema
- Power Query
- DAX
- Business Analysis
- Trend Analysis
- Interactive Reporting
- Drill-through Reports
- Data Transformation

---

# 🎓 Learning Outcomes

Through this project, I strengthened my understanding of:

- Business Intelligence reporting
- Dashboard design principles
- KPI development
- DAX calculations
- Data modeling
- Power Query transformations
- Interactive dashboard development
- Business storytelling
- Performance optimization in Power BI

---

# 💡 Future Enhancements

- Integrate live data refresh using Power BI Service.
- Add geographical map visualizations.
- Implement demand forecasting using predictive analytics.
- Include cancellation analysis and driver performance metrics.
- Publish the dashboard with Row-Level Security (RLS).

---

# 📬 Contact

**Asi Lokesh**

📧 Email: asilokesh11@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/asi-lokesh-904638266

💻 GitHub: https://github.com/Lokesh-loki-11

---

⭐ If you found this project useful, feel free to star the repository!
