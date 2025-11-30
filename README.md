# cricket-player-performance-dashboard
This repository contains a Power BI project that analyzes cricket batting performance metrics. The dashboard visualizes player-level statistics such as matches, innings, runs, highest score (HS), batting average, balls faced (BF), strike rate (SR), centuries (100), half-centuries (50), ducks (0), and boundary counts (4s, 6s). 

# Cricket Batting Performance Dashboard (Power BI)

## 📌 Project Summary
This repository contains a Power BI dashboard that analyzes **cricket batting performance** across players. It is intended as a portfolio project demonstrating data cleaning, modeling, DAX, and interactive visualization skills applied to cricket statistics.

**Files included**
- `ESP.pbix` — Power BI report 
- `Headers.xlsx` — Column header reference (list of fields)
- `Column definitions.xlsx` — Data dictionary describing each column
- `ESP_Dashboard.pdf` —  the report for quick viewing
- `screenshots/` — screenshot images for preview

---

## 🔎 Dataset & Key Fields
The dashboard uses batting-level statistics. Main columns :

- **Player** — Player name  
- **Span** — Career span (years)  
- **Mat** — Matches played  
- **Inns** — Innings batted  
- **NO** — Not outs  
- **Runs** — Total runs scored  
- **HS** — Highest score  
- **Ave** — Batting average  
- **BF** — Balls faced  
- **SR** — Strike rate  
- **100** — Number of centuries  
- **50** — Number of half-centuries  
- **0** — Number of ducks (score of zero)  
- **4s** — Number of fours hit  
- **6s** — Number of sixes hit

Detailed descriptions for each field are available in **`Column definitions.xlsx`**.

---

## 📈 Dashboard Features
- Player-level cards and leaderboards (top run-scorers, highest SR, most 100s/50s)  
- Trend charts for runs and strike rate across span/time. 
- Distribution visuals: runs distribution, ducks, boundaries per player. 
- Interactive slicers: filter by player, span/year, and other categorical fields.

---

## 🛠 Tools & Techniques
- **Power BI Desktop** — report authoring  
- **Power Query** — data cleaning and shaping  
- **DAX** — calculated measures and KPIs  
- Excel — original data sources (`Headers.xlsx`, `Column definitions.xlsx`)

---

## 📥 How to View

### Option A — Interactive (recommended)
1. Download `ESP.pbix`.  
2. Install **Power BI Desktop** (free): https://powerbi.microsoft.com/desktop/  
3. Open `ESP.pbix` in Power BI Desktop and use slicers to interact.

### Option B — Quick preview (no install)
- Open `ESP_Dashboard.pdf` (exported report) or view images inside `screenshots/`.

---


## 📬 Contact
**Yash Charde**  
Email: *yashraj.charde@gmail.com*  
GitHub: https://github.com/yashcharde11
