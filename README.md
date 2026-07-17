# 🏢 SimPro Real Estate – Bengaluru Housing Market Analytics Dashboard

## 📌 Project Overview

The **SimPro Real Estate Dashboard** is an interactive Power BI project developed to analyze the Bengaluru housing market using the Bengaluru House Price dataset. The dashboard provides valuable insights into property pricing, premium locations, BHK distribution, area types, and investment trends through an executive-level business intelligence interface.

This project demonstrates the complete Power BI workflow, including data cleaning, transformation, data modeling, DAX calculations, and dashboard design.

---

# 🎯 Project Objectives

- Analyze Bengaluru housing market trends.
- Identify premium property locations.
- Compare property prices across BHK categories.
- Analyze different area types.
- Calculate key real estate performance indicators.
- Build an interactive executive dashboard for decision-making.

---

# 📊 Dashboard Features

### KPI Cards

- Total Properties
- Average Property Price
- Total Locations
- Average BHK
- Average Price per Sqft

### Interactive Visualizations

- Top Premium Locations
- Area Type Distribution
- Average Price by BHK
- Price vs Total Sqft (Scatter Plot)
- Property Details Table

### Interactive Filters

- Location
- BHK
- Area Type
- Property Status

---

# ⚙️ Data Preparation

The dataset was cleaned using **Power Query**.

Data preparation included:

- Removed duplicate records
- Removed missing values
- Corrected inconsistent data types
- Converted numeric columns
- Renamed columns
- Created Property Status column
- Prepared data for dashboard analysis

---

# 📐 Data Modeling

A dedicated Measures table was created to store all DAX measures.

The project follows a clean Power BI model with:

- Single fact table
- Measure table
- Optimized relationships
- Reusable DAX calculations

---

# 🧮 DAX Measures Used

The dashboard uses several DAX measures, including:

- Total Properties
- Total Locations
- Average Price
- Average BHK
- Average Sqft
- Average Price per Sqft
- Maximum Price
- Minimum Price
- Average Bathrooms
- Average Balconies

Example:

```DAX
Total Properties =
COUNTROWS('Properties')
```

```DAX
Average Price =
AVERAGE('Properties'[price])
```

```DAX
Total Locations =
DISTINCTCOUNT('Properties'[location])
```

---

# 📈 Business Insights

The dashboard helps answer business questions such as:

- Which locations have the highest average property prices?
- Which BHK category is most expensive?
- What is the average property price across Bengaluru?
- How does price vary with property size?
- Which area type has the highest number of properties?

---

# 🛠 Tools & Technologies

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Data Visualization
- Microsoft Excel (CSV Dataset)

---

# 📂 Dataset

Dataset Used:

**Bengaluru House Price Dataset**

Columns Used:

- Area Type
- Availability
- Location
- Bedroom Size (BHK)
- Total Sqft
- Bathroom
- Balcony
- Price

---

# 🎨 Dashboard Theme

The dashboard follows a professional **Luxury Real Estate Theme** using:

- Dark Executive UI
- Gold Accent Colors
- Interactive KPI Cards
- Business-Oriented Visualizations
- Corporate Branding (SimPro Real Estate)

---

# 📸 Dashboard Preview

<img width="100%" src="Screenshot 2026-07-17 080929.png">

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- KPI Development
- Dashboard Design
- Business Intelligence
- Interactive Reporting
- Data Visualization
- Storytelling with Data

---

# 📌 Future Improvements

- Integration with SQL Database
- Live Data Refresh
- Market Trend Forecasting
- Geospatial Property Mapping
- Predictive Analytics using Python

---

# 👨‍💻 Author

**Shashank C**

Aspiring Data Analyst


LinkedIn: https://linkedin.com/in/shashank-c-419169333

---

⭐ If you found this project helpful, feel free to star this repository.
