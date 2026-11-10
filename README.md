# 🚲 Analyzing Smart City Bike Sharing Data Using Power BI

## 📌 Project Overview

This project focuses on analyzing Smart City Bike Sharing data using Microsoft Power BI to understand bike station performance, operational efficiency, and usage patterns across different cities.

Public bike-sharing systems generate large amounts of data from multiple stations. Analyzing this information helps identify station activity, bike availability, city-level performance, and operational patterns.

The project involves data cleaning, transformation, data modeling, DAX calculations, and interactive dashboard development to convert raw bike-sharing data into meaningful business insights.

This project demonstrates my practical knowledge of data analytics and business intelligence as part of my journey as an **Aspiring Data Analyst**.

## 🎯 Project Objectives

- Import and explore the bike-sharing dataset using Power BI.
- Clean and transform raw data using Power Query Editor.
- Handle missing values and inconsistent data.
- Create a structured data model using fact and dimension tables.
- Establish relationships between tables.
- Develop calculated columns and measures using DAX.
- Analyze bike station availability and operational performance.
- Compare performance across different cities.
- Develop interactive dashboards using Power BI.
- Generate actionable insights through data visualization.

## 📂 Dataset Information

**Dataset Name:** Bike Stations Sharing Data

**Source:** [GitHub – Bike Stations Sharing Dataset](https://github.com/GeethaGunasekaran1/Project-Dataset/raw/refs/heads/main/bike-stations-sharing-data.xlsx)

The dataset contains information about bike-sharing stations, including station details, location information, bike availability, and operational status.

The dataset is used to explore station distribution, bike availability, and city-level operational patterns.

## 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Data modeling and dashboard development |
| Power Query Editor | Data cleaning and transformation |
| DAX | Calculated columns and analytical measures |
| Excel | Dataset inspection and source data |
| GitHub | Project documentation and portfolio management |

## 🔄 Project Workflow

### 1. Data Import and Exploration

- Imported the bike-sharing dataset into Power BI.
- Explored the dataset structure and available columns.
- Identified important attributes for analysis.
- Reviewed data types and potential data quality issues.

### 2. Data Cleaning and Transformation

Used Power Query Editor to prepare the dataset for analysis.

Key activities:

- Identified and handled missing values.
- Checked for duplicate records.
- Corrected data types.
- Standardized column formats.
- Split the Last Updated column to extract relevant date and time information.
- Reviewed station information for consistency.
- Filtered and organized records for analysis.

### 3. Data Modeling

Designed a structured data model to organize the bike-sharing information.

**Fact Table:**
- Contains the main bike station records and measurable attributes.

**Dimension Tables:**
- Station Dimension
- City Dimension
- Date Dimension (where applicable)

**Relationships:**
- Established relationships between fact and dimension tables using appropriate keys.
- Reviewed relationship cardinality and filter direction.
- Ensured the model supports accurate reporting and analysis.

### 4. DAX Calculations

Created DAX measures and calculated columns to analyze station performance and operational efficiency.

Key analytical areas include:

- Total number of stations.
- Total available bikes.
- Total available bike stands.
- Active station count.
- Station distribution by city.
- Bike availability across cities.
- Station operational status.

These calculations help evaluate bike-sharing infrastructure and station-level performance.

*The final measures and formulas are based on the available dataset columns and the implemented Power BI model.*

### 5. Data Visualization and Dashboard Development

Developed an interactive Power BI dashboard to present important bike-sharing metrics and performance indicators.

The dashboard focuses on the following analytical areas:

| Visualization | Purpose |
|---|---|
| Card Visuals | Display important KPIs such as total stations and available bikes |
| Bar Chart | Compare station distribution across cities |
| Donut Chart | Show station status distribution |
| Column Chart | Compare bike availability across cities |
| Map Visual | Analyze geographical station distribution |
| Slicers | Filter data based on city and station attributes |
| Tables | Display detailed station-level information |

The dashboard includes appropriate titles, labels, formatting, and background customization to improve readability and presentation.

## 📊 Key Business Questions

The analysis aims to answer the following questions:

1. Which cities have the highest number of bike-sharing stations?
2. Which cities have the lowest number of stations?
3. How many bikes are currently available across the stations?
4. Which stations are active and inactive?
5. Which cities have the highest bike availability?
6. How are bike-sharing stations distributed geographically?
7. Which stations may require operational attention?

## 💡 Business Insights

The dashboard helps identify:

- Cities with higher bike-sharing infrastructure.
- Differences in bike availability across cities.
- Active and inactive station distribution.
- Stations with limited bike availability.
- Geographic patterns in bike-sharing infrastructure.
- Potential areas for improving bike-sharing operations.

These insights can help city planners and bike-sharing operators make better decisions about resource allocation and station management.

## 📁 Project Structure

```text
Smart-City-Bike-Sharing-Analysis/
│
├── README.md
│
├── Dataset/
│   └── bike-stations-sharing-data.xlsx
│
├── PowerBI/
│   └── Smart_City_Bike_Sharing_Analysis.pbix
│
├── Screenshots/
│   └── Dashboard.png
│
└── Documentation/
    └── Project_Report.pdf
```

*Update the folder structure according to the actual files uploaded to your repository.*

## 📚 Key Learning Outcomes

Through this project, I gained practical experience in:

- Importing and exploring datasets using Power BI.
- Cleaning and transforming data using Power Query.
- Handling missing values and duplicate records.
- Creating fact and dimension tables.
- Establishing relationships between tables.
- Writing DAX measures and calculated columns.
- Analyzing bike availability and station performance.
- Developing interactive Power BI dashboards.
- Using different visualizations to communicate insights.
- Understanding how data analytics supports smart city planning.

## 🏁 Conclusion

This project provided hands-on experience in analyzing bike-sharing data using Microsoft Power BI.

By applying data cleaning, transformation, data modeling, DAX calculations, and visualization techniques, I explored bike station distribution, bike availability, and operational performance across different cities.

The project demonstrates how data analytics can support smarter urban mobility planning, improve resource allocation, and provide useful insights into public bike-sharing systems.

As an **Aspiring Data Analyst**, I am continuously developing my analytical and technical skills through practical projects involving Excel, SQL, Python, and Power BI.

## 👨‍💻 About Me

**Jeeva S**

Aspiring Data Analyst

**Technical Skills:**
- Microsoft Excel
- Microsoft Power BI
- DAX
- SQL
- Python
- Data Cleaning
- Data Modeling
- Data Visualization
- Business Intelligence

---

⭐ Thank you for visiting my GitHub repository!
