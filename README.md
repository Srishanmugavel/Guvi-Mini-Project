# Cricsheet Match Data Analysis

## 📌 Project Overview
This end-to-end data analytics project focuses on scraping, processing, analyzing, and visualizing cricket match data from Cricsheet. You will leverage Selenium for web scraping, Python for data transformation, SQL for structured storage and querying, and Power BI for insightful dashboards.

---

## 🎯 Problem Statement
Scrape JSON files of different cricket match types (ODI, T20, Test, IPL) from https://cricsheet.org/matches/, store data into SQL tables, perform EDA in Python, and build a Power BI dashboard to analyze key performance metrics.

---

## 🧠 Skills You’ll Learn
- Web Scraping using Selenium
- Data Transformation with Pandas
- SQL Database Management
- Exploratory Data Analysis (EDA)
- Power BI Visualization
- Automation with Python
- Structured JSON Parsing

---

## 🏏 Domain
**Sports Analytics / Data Analysis**

---

## 🧭 Project Approach

### 1. Data Scraping Using Selenium
- Automate navigation to Cricsheet's match pages.
- Download JSON files for Test, ODI, T20, and IPL matches.

### 2. Data Transformation with Python
- Parse JSON files using `json` and `pandas`.
- Create DataFrames for each match type.
- Normalize nested structures.

### 3. Database Management (SQL)
- Create `test_matches`, `odi_matches`, and `t20_matches` tables.
- Insert cleaned data using SQLAlchemy/MySQL connector.

### 4. SQL Queries for Data Analysis
- Write 20 optimized queries such as:
  - Top batsmen by runs
  - Leading wicket-takers
  - Highest win % team
  - Total centuries
  - Closest margin victories

### 5. Exploratory Data Analysis (EDA)
- Create 10 visualizations using `matplotlib`, `seaborn`, `plotly`.

### 6. Power BI Dashboard
- Connect Power BI to SQL tables.
- Build dashboard to visualize player/team performance & match outcomes.

---

## 📁 Project Deliverables
- `selenium_scraper.py` – for scraping JSONs
- `json_to_sql.py` – for processing JSON and inserting into DB
- `sql_queries.sql` – 20 insight-oriented SQL queries
- `eda_analysis.py` – Python EDA script with visualizations
- `CricsheetDashboard.pbix` – Power BI dashboard
- `README.txt` – Project documentation
- `match_data.db` or SQL schema

---

## 🧪 Evaluation Metrics
- ✅ Accuracy of scraped and processed data
- ✅ SQL query quality and optimization
- ✅ Completeness and interactivity of Power BI dashboard
- ✅ Integration of all components (Selenium, SQL, BI)
- ✅ Clarity and insightfulness of presentation

---

## 💼 Business Use Cases
- Player Performance Analysis
- Team Insights by Format
- Match Outcome Predictions
- Support for Coaches/Analysts
- Fan Engagement Dashboards

---

## 🔧 Technologies Used
- Selenium (Web Scraping)
- Python (Data Parsing & EDA)
- Pandas, JSON, Matplotlib, Seaborn, Plotly
- SQL (MySQL/SQLite)
- Power BI
- Git for version control

---

## 🗃️ Dataset
- **Source:** https://cricsheet.org/
- **Format:** JSON (1 per match)
- **Includes:** Match metadata, innings data, players, runs, wickets

---

## 🧼 Data Preprocessing
- Load & flatten JSONs
- Structure innings/delivery/player data
- Normalize nested keys
- Clean column names & handle nulls

---

## 📬 Final Notes
Ensure code is modular and properly commented. Validate all scraped data before SQL insertion. Optimize queries and use meaningful visualizations for impactful storytelling.

Happy Analyzing! 🏏📊
