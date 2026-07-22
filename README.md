# 🎬 Netflix Content Analytics Dashboard

## 📌 Project Overview

This project presents an interactive **Netflix Content Analytics Dashboard** built using **Power BI**. The dashboard provides insights into Netflix's content library, including movies and TV shows, by analyzing trends in content additions, ratings, genres, countries, and release years.

The project demonstrates the complete data analytics workflow, including **data cleaning, transformation, data modeling, DAX calculations, and dashboard development**.

---

## 🛠️ Tools & Technologies

- Power BI
- Microsoft Excel
- Power Query
- DAX
- Data Modeling
- Data Visualization

---

## 📂 Dataset

- **Source:** Netflix Movies & TV Shows Dataset (Kaggle)
- **Format:** CSV
- **Records:** ~8,800+ Titles

The original dataset is included in this repository.

---

## 🧹 Data Preparation & Cleaning

The original Netflix dataset was provided as a **single CSV file** containing multiple comma-separated values for attributes such as **cast, directors, genres, and countries**.

To improve data quality and create a scalable data model, the dataset was cleaned and transformed in **Microsoft Excel** by:

- Removing blank values and handling missing data
- Trimming unnecessary spaces
- Standardizing text values
- Splitting multi-value columns into separate normalized tables
- Preparing the data for relational modeling in Power BI

---

## 🗂️ Data Modeling

Instead of using a single flat table, the dataset was normalized into multiple tables in Excel.

The following tables were created:

| Table | Description |
|--------|-------------|
| **netflix_data_titles** | Main table containing Netflix title information |
| **netflix_data_netflix_cast** | Cast members for each title |
| **netflix_data_netflix_directors** | Directors of each title |
| **netflix_data_netflix_listed_in** | Genres/Categories |
| **netflix_data_countries_released** | Countries where content is available |
| **netflix_data_description** | Description of each title |

All tables are connected using the **show_id** column, creating a relational data model inside Power BI that improves filtering, report performance, and dashboard scalability.

> **Note:** The repository includes the original Netflix CSV dataset. The normalized tables were created from this dataset using Microsoft Excel before importing the data into Power BI.

---

## 📊 Dashboard Features

### Dashboard 1 – Netflix Content Analytics

- Total Movies & TV Shows KPIs
- Movies vs TV Shows Analysis
- Shows Added by Year
- Rating Distribution
- Top Genres
- Country-wise Content Availability
- Interactive Filters & Slicers

---

### Dashboard 2 – Netflix Content Explorer

An interactive page to explore individual Netflix titles.

Features include:

- Title Selection
- Release Year
- Rating
- Description
- Genre
- Director
- Cast Members
- Country Availability
- Interactive Map

---

## 📈 Key Insights

- Movies make up the majority of Netflix's content library.
- TV-MA is one of the most common content ratings.
- The United States contributes the highest number of Netflix titles.
- Netflix experienced significant content growth after 2015.
- Drama and International Movies are among the most popular genres.

---

## 📁 Repository Structure

```
Netflix-Content-Analytics-Dashboard
│
├── README.md
├── Netflix Dashboard.pbix
├── netflix_titles.csv
├── Screenshots
│   ├── Dashboard Overview.png
│   └── Content Explorer.png
└── Assets
    └── Netflix Logo.png
```

---

## 📷 Dashboard Preview

### Dashboard Overview

*(Insert Screenshot Here)*

---

### Netflix Content Explorer

*(Insert Screenshot Here)*

---

## 💡 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Normalization
- Data Modeling
- Relational Database Design
- Power Query
- DAX
- Power BI Dashboard Development
- KPI Reporting
- Interactive Data Visualization

---

## 🚀 Future Improvements

- Add bookmarks for dashboard navigation
- Include additional DAX measures
- Publish dashboard to Power BI Service
- Add advanced drill-through pages
- Automate data refresh using Power BI Service

---

## 👩‍💻 Author

**Aachal Raut**

LinkedIn: https://www.linkedin.com/in/aachal-raut

GitHub: https://github.com/yourusername
