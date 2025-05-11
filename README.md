![Crime Analysis Banner](crime_wallpaper.png)

# 🚨 Welcome to the **Crime Analysis & Investigation Dashboard** Project!

This repository contains an end-to-end **data analysis and visualization solution** focused on city-level crime data using Power BI. The dashboard provides law enforcement, policymakers, and researchers with **actionable insights into crime patterns**, pending investigations, and operational effectiveness.

---

## 📑 Table of Contents

* [📌 Project Overview](#project-overview)
* [🎯 Dataset Information](#dataset-information)
* [📊 Key Highlights](#key-highlights)
* [📂 Visualizations](#visualizations)
* [🛠 Technologies Used](#technologies-used)
* [📈 Installation and Usage](#installation-and-usage)
* [📁 Project Structure](#project-structure)
* [🤝 Contributions](#contributions)
* [📄 License](#license)
* [📬 Contact](#contact)

---

## **Project Overview**

This Power BI project explores crime data to uncover patterns in:

* Crime types
* Regional distributions
* Crime resolution trends (solved vs. pending)
* Weapon usage and time of occurrence
* Pending investigation matrix

The dashboard is built to enable **better decision-making**, **trend monitoring**, and support crime investigation strategies.

---

## **Dataset Information**

The dataset includes structured crime records across multiple dimensions such as:

| Column Name             | Description                                    |
| ----------------------- | ---------------------------------------------- |
| Crime ID                | Unique identifier for each crime case          |
| City / State            | Geographic location of the crime               |
| Crime Type              | Type/category of the crime committed           |
| Date Time of Occurrence | Timestamp of when the crime occurred           |
| Date Case Closed        | Closure date (if available)                    |
| Weapon Used             | Object or weapon used in the crime             |
| Status                  | Solved or Pending status based on closure date |
| Description             | Brief narrative of the incident                |

📝 *Data is anonymized and/or simulated for project purposes.*

---

## **Key Highlights**

### 🗓️ 1. Time-Based Crime Patterns

* Monthly & Yearly crime trend lines
* Most dangerous hours of the day categorized by intervals

### 🧭 2. Geographical Insights

* Crime heatmaps by City and State
* Filtering capability by location and case status

### ⚖️ 3. Solved vs. Pending Analysis

* Stacked bar charts comparing month-wise crime resolution status
* Solved % trend line to assess investigation performance

### 🔪 4. Weapon & Crime Description Linkage

* Relationship between weapon types and crime categories
* Matrix visualization for pending crimes with full details

### 🔍 5. Search & Filter Experience

* Interactive slicers (search bar style) for Crime ID and City
* Drill-through capabilities and slicer interactivity across visuals

---

## **Visualizations**

* 📈 **Crimes by Month-Year (Trend Line/Area Chart)** — *"Tracking Crime Trends Over Time"*
* 📊 **Crimes by Month (Bar/Line Chart)** — *"Monthly Crime Distribution Overview"*
* 💥 **Solved vs Pending Timeline** — *"Investigation Status Tracker"*
* ⏰ **Time Demographics** — *"When Crimes Happen: Hourly Intervals"*
* ⚔️ **Weapon vs Crime Type Matrix** — *"Weapon Use Across Crime Categories"*
* 🧾 **Pending Case Explorer** — *"Matrix View of All Unresolved Crimes"*

Interactive tooltips include Total Crimes, % Solved, City, and Crime Type.
---
![Dashboard-Preview](Crime_analysis_page-2.jpg)


## 🛠 **Technologies Used**

* **Power BI**: Interactive dashboard creation
* **DAX**: Measures, calculated columns, KPIs
* **Excel / CSV**: Data source structuring and cleaning
* **GitHub**: Version control and project publishing

---

## **Installation and Usage**

### 🧰 To View and Explore:

1. Clone the repository or download it as a ZIP file.
2. Open `Crime_analysis.pbix` in **Power BI Desktop**.
3. Use slicers and filters to explore crime insights by:

   * Crime type
   * Date & Time
   * City / State
   * Case status (Solved / Pending)

---

## **Project Structure**

```
crime-analysis-dashboard/
│
├── data/
│   └── crime_data.csv                # Cleaned dataset (optional)
│
├── visualizations/
│   └── Crime_analysis.pbix           # Power BI dashboard file
│
├── screenshots/
│   └── *.png                         # Visual previews (optional)
│
├── README.md                         # Project documentation
```

---

## **Contributions**

Contributions, suggestions, and feature requests are welcome!
Feel free to fork the repo, make changes, and submit a pull request.

---

## **License**

This project is licensed under the [MIT License](LICENSE).

---

## **Contact**

📧 For collaboration or feedback, connect via
🔗 [LinkedIn – Sahil Jena](https://www.linkedin.com/in/sahil-jena-067b1b301)

---


