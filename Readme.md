# 🏏 T20 World Cup Match Analysis Dashboard

This project analyzes **T20 World Cup cricket data** with the help of **web scraping (JavaScript), preprocessing (Python), and visualization (Power BI)**.
It enables detailed **player performance analysis, team statistics, and Final XI selection** through interactive dashboards.

---

## 📂 Project Structure

```
T20_MATCH_ANALYSIS/
│
├── t20_csv_files/              # Cleaned & structured CSV datasets
│   ├── dim_match_summary.csv
│   ├── dim_players_no_images.csv
│   ├── dim_players.csv
│   ├── fact_batting_summary.csv
│   ├── fact_bowling_summary.csv
│
├── t20_json_files/             # Raw scraped JSON data
│   ├── t20_wc_batting_summary.json
│   ├── t20_wc_bowling_summary.json
│   ├── t20_wc_match_results.json
│   ├── t20_wc_player_info.json
│
├── web_scrapping_codes/        # Node.js scripts for web scraping
│   ├── t20_wc_batting_summary.js
│   ├── t20_wc_bowling_summary.js
│   ├── t20_wc_match_results.js
│   ├── t20_wc_player_info.js
│
├── Codebasics Cricket Best 11.pbix   # Power BI Dashboard file
├── DAX Measures and Calculated columns.xlsx  # DAX formulas documentation
├── t20_data_preprocessing.ipynb      # Python notebook for preprocessing
├── Readme.md
```

---

## ⚙️ Tech Stack

- **Data Extraction**: JavaScript (Node.js web scraping)
- **Data Storage**: JSON (raw) → CSV (structured)
- **Data Processing**: Python (Pandas, NumPy in Jupyter Notebook)
- **Visualization**: Power BI (Interactive dashboards, DAX measures)

---

## 📊 Workflow

1. **Data Collection**

   - Web scraping scripts (`.js`) fetch **match results, batting summaries, bowling stats, and player info**.
   - Data is stored in **JSON format**.

2. **Data Transformation**

   - JSON → CSV using Python (`t20_data_preprocessing.ipynb`).
   - Structured into **dimension and fact tables**.

3. **Visualization (Power BI)**

   - **Player Analysis**: Batting & Bowling insights.
   - **Final XI Selection**: Build your custom team with KPIs.
   - **Role-based Analysis**: Power Hitters, Anchors, Finishers, All-rounders, Fast Bowlers.
   - KPIs with **DAX Measures** (Batting Avg, Strike Rate, Economy, Dot Ball %, etc.).

---

## 🚀 Features

- 📌 **Custom Final XI selection** with performance summary
- 📊 **Role-based dashboards**: Openers, Anchors, Finishers, All-rounders, Bowlers
- ⚡ **Key metrics**: Batting Avg, Strike Rate, Economy, Dot Ball %, Boundary %
- 📈 **Interactive filters** for players, teams, and roles
- 🏆 **Dream XI creation** using data-driven insights

---

## 📷 Dashboard Previews

### 🔹 Final XI Selection

![Final XI Selection](https://github.com/your-repo-link/screenshots/final11.png)

### 🔹 Player Role Analysis

![Player Role Analysis](https://github.com/your-repo-link/screenshots/player_analysis.png)

---

## ▶️ How to Run

1. **Run Web Scraping (Optional, to refresh data)**

   ```bash
   node web_scrapping_codes/t20_wc_batting_summary.js
   node web_scrapping_codes/t20_wc_bowling_summary.js
   node web_scrapping_codes/t20_wc_match_results.js
   node web_scrapping_codes/t20_wc_player_info.js
   ```

2. **Preprocess Data**

   - Open `t20_data_preprocessing.ipynb` in Jupyter Notebook.
   - Run the cells to clean and generate CSV files.

3. **Visualize in Power BI**

   - Open `Codebasics Cricket Best 11.pbix` in Power BI Desktop.
   - Refresh data connections to see the latest stats.

---

## 📌 Future Enhancements

- Automate JSON → CSV pipeline with a scheduler
- Add predictive analytics (e.g., win probability, player impact score)
- Deploy dashboards to Power BI Service for online access

---
