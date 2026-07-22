# 🎬 Netflix Content Analytics Dashboard

An interactive **Power BI dashboard** built to analyze the **Netflix Movies & TV Shows** dataset. This project demonstrates the complete data analytics workflow, including **data cleaning, normalization, relational data modeling, DAX calculations, and interactive dashboard development**.

---

## 🚀 Tech Stack

| Category | Technologies |
|----------|--------------|
| Dashboard & BI | Power BI |
| Data Cleaning & Transformation | Microsoft Excel, Power Query |
| Data Modeling | Relational Data Model |
| Analytics | DAX |
| Version Control | Git, GitHub |

---

## 📂 Dataset

- **Dataset:** Netflix Movies & TV Shows
- **Source:** Kaggle
- **Format:** CSV
- **Records:** 8,800+ Netflix Titles

The original dataset (`netflix_titles.csv`) is included in this repository.

---

# 📋 Project Objective

The objective of this project is to analyze Netflix's content library and build an interactive dashboard that helps users understand:

- Movies vs TV Shows distribution
- Content growth over time
- Rating distribution
- Genre popularity
- Country-wise content availability
- Detailed information about each Netflix title

---

# 🧹 Data Cleaning & Transformation

The original dataset consisted of a single CSV file containing multiple comma-separated values in columns such as:

- Cast
- Director
- Country
- Genre (Listed In)

To prepare the data for analysis, Microsoft Excel was used to:

- Remove blank and missing values
- Trim unnecessary spaces
- Standardize text values
- Clean inconsistent records
- Split multi-value columns into separate normalized tables

This process improved data quality and enabled efficient relational modeling in Power BI.

---

# 🗂️ Data Modeling

Instead of importing one large flat table into Power BI, the dataset was normalized into multiple tables.

The following tables were created:

| Table | Description |
|--------|-------------|
| **netflix_data_titles** | Main table containing title information |
| **netflix_data_netflix_cast** | Cast members for each title |
| **netflix_data_netflix_directors** | Directors of each title |
| **netflix_data_netflix_listed_in** | Genres / Categories |
| **netflix_data_countries_released** | Countries where content is available |
| **netflix_data_description** | Description of each title |

All tables are connected using the **show_id** column, creating a relational data model that enables efficient filtering, improved performance, and accurate cross-table analysis.

> **Note:** The original CSV dataset is included in this repository. The normalized tables were created from this dataset using Microsoft Excel before importing the data into Power BI.

---

# 📊 Dashboard Features

## Dashboard 1 — Netflix Content Analytics

The overview dashboard provides high-level insights into Netflix's content library.

### Features

- KPI Cards
  - Total Titles
  - Movies
  - TV Shows
- Shows Added by Year
- Rating Distribution
- Top 10 Genres
- Country-wise Content Availability
- Interactive Filters & Slicers
- Responsive Visualizations

---

## Dashboard 2 — Netflix Content Explorer

A dynamic dashboard for exploring individual Netflix titles.

### Features

- Movie/TV Show Selector
- Title Description
- Release Year
- Content Rating
- Director Information
- Cast Members
- Genres
- Country Availability
- Interactive Map

---

# 📈 Key Insights

- Movies represent the majority of Netflix's content library.
- TV-MA is one of the most common content ratings.
- The United States contributes the highest number of Netflix titles.
- Drama and International Movies are among the most popular genres.
- Netflix experienced significant content growth after 2015.

---

# 💡 Power BI Concepts Used

- Data Modeling
- Relationships
- DAX Measures
- Power Query
- KPI Cards
- Line Charts
- Clustered Bar Charts
- Column Charts
- Filled Map
- Slicers
- Drill-through Navigation
- Interactive Filtering

---

# 📁 Repository Structure

```
Netflix-Content-Analytics-Dashboard
│
├── README.md
├── Netflix Dashboard.pbix
├── netflix_titles.csv
│
├── Screenshots
│   ├── Dashboard Overview.png
│   ├── Netflix Content Explorer.png
│   └── Data Model.png
│
├── Assets
│   └── Netflix Logo.png
│
└── LICENSE
```

---

# 📸 Dashboard Preview

## Dashboard Overview

*(Add Screenshot Here)*

---

## Netflix Content Explorer

*(Add Screenshot Here)*

---

## Data Model

*(Add Screenshot of Power BI Model View Here)*

---

# 🎯 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Normalization
- Relational Data Modeling
- Power BI Dashboard Development
- DAX
- Power Query
- KPI Reporting
- Data Visualization
- Business Intelligence Reporting

---

# 🚀 Future Enhancements

- Publish dashboard to Power BI Service
- Add advanced drill-through pages
- Automate scheduled data refresh
- Expand dashboard with additional KPIs

---

# 👩‍💻 Author

**Aachal Raut**

📧 Email: aachalraut2010@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/aachal-raut-777111288/

🐙 GitHub: https://github.com/Aachalraut
