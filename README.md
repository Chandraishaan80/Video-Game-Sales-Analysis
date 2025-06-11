# 🎮 Video Game Sales Analysis: Discovering the Golden Age of Gaming

## 📌 Overview

This project analyzes 400 of the best-selling video games (since 1977) to explore industry trends, identify standout publishers and titles, and determine when the video game industry was at its peak.

We use:
- **BigQuery** for querying structured game sales data
- **Google Sheets** for visualising results

---

## 🛠 Tech Stacks
- **SQL (Google BigQuery)** – for querying and aggregating sales data  
- **Google Sheets** – for creating visuals (charts, tables, and summaries)  
- **GitHub** – for project documentation and version control  

---

## 📁 Project Contents

### 🔹 SQL Scripts

| File | Description |
|------|-------------|
| `highest_total_sales_by_game.sql` | Finds the top 10 best-selling games (calculates total global sales) |
| `highest_selling_game_per_publisher.sql` | Lists each publisher’s highest-selling individual game |
| `top_years_by_average_sales.sql` | Ranks years by average game sales and identifies strong sales periods |
| `total_games_sold_by_year.sql` | Counts how many games were sold each year |

> 💡 **Only `highest_total_sales_by_game.sql` uses**:  
> ```sql
> (NA_Sales + EU_Sales + JP_Sales + Other_Sales) AS total_sales
> ```

---

### 📈 Visualizations

All SQL results were exported to **Google Sheets** and visualized using built-in charts.

🗂️ File: `results-Highest selling game per publisher.xlsx`

Included visuals:
- **Bar Charts**: Top games and publisher performances  
- **Line Graphs**: Sales trends across years  
- **Summary Tables**: Yearly sales and hit counts

---

## ⚙️ How to Use

1. Clone this repo
2. Upload `.sql` scripts into BigQuery
3. Replace the table path with your own dataset
4. Run queries individually
5. Export each result to Google Sheets
6. Use **Insert → Chart** to build visualizations

---

## ✅ Project Status

- [x] SQL queries tested and validated  
- [x] Visual charts created from live data  
- [x] Project completed and fully documented  

---

## 📜 License

Released under the **MIT License** – open to use, remix, and share.

---

## 🙌 Acknowledgments

- [Google BigQuery](https://cloud.google.com/bigquery) – data analysis engine  
- [Google Sheets](https://sheets.google.com) – for smooth visual storytelling  

---

## 🔗 Contact

Want to collab or chat? 
Reach out via www.linkedin.com/in/ishan-chandra2000 or chandraishaan80@gmail.com]

