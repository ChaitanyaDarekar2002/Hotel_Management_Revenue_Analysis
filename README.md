# 🏨 Hotel Revenue Analysis

An interactive **Hotel Revenue Analysis** project built using **Microsoft Power BI** to analyze hotel performance, revenue, bookings, guests, room categories, cities, and booking trends.

The project transforms raw hotel booking data into meaningful business insights through data modeling, DAX calculations, and interactive Power BI dashboards.

---

## 📌 Project Workflow

**Dataset → Data Preparation → Data Modeling → Power BI Dashboard → Business Insights**

### 1️⃣ Get Dataset

The project starts with hotel booking data containing information related to:

- Hotel
- City
- Room Category
- Booking Date
- Revenue
- Guests
- Successful Bookings
- Room Capacity
- Booking Status
- Booking Platform / Category

The dataset is used to analyze hotel revenue and booking performance.

---

## 📊 2️⃣ Data Preparation & Modeling

The raw data was organized into a structured data model in Power BI.

The project uses dimension and fact tables such as:

- `dim_date`
- `dim_hotels`
- `dim_rooms`
- `fact_bookings`
- `fact_aggregated_bookings`

The data model helps connect hotel, room, date, and booking information for efficient analysis.

---

## 🧮 3️⃣ Power BI & DAX

Microsoft Power BI was used to create calculated measures and an interactive dashboard.

DAX measures were created to calculate important KPIs such as:

- Total Revenue
- Number of Guests
- Average Revenue
- Average Capacity
- Successful Bookings

---

## 📈 4️⃣ Dashboard

The **Hotel Revenue Analysis Dashboard** provides an overview of hotel business performance.

### 📌 Key KPIs

- 💰 **Total Revenue:** 846M
- 👥 **Number of Guests:** 56.683K
- 💵 **Average Revenue:** 14.93K
- 🏨 **Average Capacity:** 25.28
- ✅ **Successful Bookings:** 9.2K

---

## 📊 Dashboard Visualizations

The dashboard includes:

### Revenue Analysis
- Revenue by City
- Revenue by Room Category
- Revenue by Booking Date
- Revenue by Hotel

### Booking Analysis
- Number of Guests
- Successful Bookings
- Daily Booking Trends
- Booking Category Analysis

### Hotel Analysis
- Hotel-wise Revenue
- City-wise Performance
- Room Category Performance
- Hotel Capacity Analysis

### Interactive Analysis
- Date Filter
- City Filter
- Room Class Filter
- Drill-through functionality
- Interactive charts and slicers

---

## 🏙️ City Analysis

The dashboard allows comparison of hotel revenue across major cities including:

- Mumbai
- Bangalore
- Hyderabad
- Delhi

The city-wise analysis helps identify high-performing locations and revenue contribution.

---

## 🛏️ Room Category Analysis

The dashboard analyzes revenue and performance across different room categories:

- Elite
- Premium
- Presidential
- Standard

This helps understand which room categories contribute most to hotel revenue.

---

## 🔍 Key Insights

The dashboard can be used to identify:

- Highest revenue-generating cities
- Revenue contribution by room category
- Hotel booking trends over time
- Guest volume and booking performance
- Average revenue generated
- Hotel capacity utilization
- Daily and monthly booking patterns
- Performance differences between hotels

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Microsoft Power BI** | Dashboard & Data Visualization |
| **DAX** | Measures & Calculations |
| **Power Query** | Data Transformation |
| **Data Modeling** | Fact & Dimension Relationships |
| **GitHub** | Project Documentation |

---

## 🔄 Project Pipeline

```text
Raw Dataset
     ↓
Data Cleaning & Transformation
     ↓
Data Modeling
     ↓
Fact & Dimension Tables
     ↓
DAX Measures
     ↓
Power BI Dashboard
     ↓
Interactive Analysis
     ↓
Business Insights
