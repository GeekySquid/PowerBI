<div align="center">

# 📊 Power BI Customer Insights Dashboard

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&weight=700&size=28&duration=3500&pause=1000&color=F2C811&center=true&vCenter=true&width=900&lines=🚀+My+First+Power+BI+Project;Power+Query+⚡+DAX+⚡+Data+Modeling;Interactive+Business+Dashboard;Turning+Raw+Data+into+Insights" />

<br>

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge)
![DAX](https://img.shields.io/badge/DAX-02569B?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-blue?style=for-the-badge)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-success?style=for-the-badge)

</div>

---

# 📖 About The Project

This is my **first Power BI project**, created as part of my journey into **Business Intelligence** and **Data Analytics**.

The objective of this project was to transform raw customer and order data into meaningful business insights using **Power Query**, **DAX**, **Data Modeling**, and **Interactive Dashboards**.

Through this project, I learned the complete Power BI workflow—from importing data to creating professional dashboards.

---

# 🚀 Project Workflow

```text
Raw CSV Data
      │
      ▼
Import Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Power Query
      │
      ▼
Data Modeling
      │
      ▼
DAX Calculations
      │
      ▼
Dashboard Development
      │
      ▼
Business Insights
```

---

# ✨ Features

- 📊 Interactive Dashboard
- 📈 KPI Cards
- 📉 Sales & Customer Analysis
- 📅 Dynamic Filters
- 📌 Slicers
- 📍 Business Insights
- 📦 Data Modeling
- 📐 DAX Calculations
- ⚡ Power Query Transformations

---

# 🧹 Data Cleaning

One of the main tasks in this project was cleaning the dataset before visualization.

### ✔ Missing Score Values

Some records contained blank values in the **Score** column.

To handle this, I created a new calculated column using **DAX**.

```DAX
Clean Score = COALESCE(customers[score], 0)
```

### 💡 Explanation

- If **Score** has a value → keep it.
- If **Score** is blank → replace it with **0**.

This ensured consistent and accurate analysis.

---

# ⚡ Power Query Transformations

Using **Power Query**, I performed several data transformation tasks.

### ✔ Created Full Name

Merged

- First Name
- Last Name

into a new column

```text
Full Name
```

This improved readability and dashboard presentation.

---

# 🔗 Data Modeling

Using **Model View**, I

- Created relationships between tables
- Connected Customers and Orders datasets
- Built an optimized relational model
- Improved report performance

---

# 📐 DAX Learning

This project introduced me to **DAX (Data Analysis Expressions)**.

### Calculated Column

```DAX
Clean Score = COALESCE(customers[score], 0)
```

### What I Learned

- Calculated Columns
- Handling Missing Values
- COALESCE()
- Basic DAX Syntax

---

# 📊 Dashboard Highlights

✔ Customer Insights

✔ Sales Analysis

✔ KPI Cards

✔ Order Analysis

✔ Interactive Charts

✔ Filters & Slicers

✔ Business Reports

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| Power BI | Dashboard Development |
| Power Query | Data Transformation |
| DAX | Business Calculations |
| Model View | Table Relationships |
| CSV Files | Data Source |

---

# 🎯 Skills Learned

- Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- Business Intelligence
- Dashboard Design
- KPI Tracking
- Interactive Reports
- Data Visualization

---

# 📂 Project Structure

```text
PowerBI-Customer-Dashboard
│
├── Dataset
│   ├── customers.csv
│   └── orders.csv
│
├── Dashboard.pbix
├── Dashboard.png
└── README.md
```

---

# 📸 Dashboard Preview

> Add your dashboard screenshot below.

<p align="center">
<img src="Dashboard.png" width="90%">
</p>

---

# 🌱 What I Learned

This project helped me understand:

✅ Importing CSV Data

✅ Data Cleaning

✅ Power Query

✅ Merging Columns

✅ Data Modeling

✅ Relationships

✅ DAX Calculations

✅ Dashboard Development

✅ Interactive Visualizations

✅ Business Intelligence

---

# 🚀 Future Improvements

- Advanced DAX
- Drill Through Reports
- Time Intelligence
- Bookmarks
- Parameters
- Row Level Security (RLS)
- Power BI Service
- Real-Time Dashboards

---

# 🤝 Connect With Me

<p align="center">

<a href="https://github.com/GeekySquid">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github">
</a>

<a href="https://www.linkedin.com/in/rama-krishna-sahoo/">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin">
</a>

</p>

---

<div align="center">

## ⭐ If you like this project, don't forget to Star this Repository!

<img src="https://capsule-render.vercel.app/api?type=waving&color=F2C811&height=140&section=footer"/>

</div>
