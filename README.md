# 🏏 IPL Analytics Dashboard — Excel 2008–2025

![IPL Dashboard](https://drive.google.com/uc?export=view&id=11mu0TnIQ28C8MoPoTnPfrsH11VEy9KkX)

> 18 Seasons · 1,169 Matches · 19 Teams · 37 Cities

---

## 📂 Sheets Overview

| Sheet | What it Contains |
|-------|-----------------|
| **IPL DASHBOARD** | Main visual dashboard — open this first |
| **IPL Data** | All 1,169 raw match rows (16 columns, auto-filter) |
| **Team Wins** | Top 10 teams by all-time wins + Bar Chart |
| **Season Stats** | Matches per season + Line Chart |
| **MOM Stats** | Top 10 Man of the Match + Bar Chart |
| **Venue Stats** | Top 10 venues + Bar Chart |
| **Toss Stats** | Bat vs Field win analysis + Pie Chart |
| **Champions** | All IPL champions 2008–2025 |

---

## 🗃️ Raw Data Columns (`IPL Data` sheet)

| Column | Field | Description |
|--------|-------|-------------|
| A | `match_number` | Unique match ID |
| B | `team1` | First team |
| C | `team2` | Second team |
| D | `Season` | e.g. `IPL-2025` |
| E | `Year` | 2008–2025 |
| F | `match_date` | Date of match |
| G | `toss_winner` | Toss-winning team |
| H | `toss_decision` | `bat` or `field` |
| I | `result` | `Win`, `tie`, or `no result` |
| J | `eliminator` | Eliminator team (if tie) |
| K | `winner` | Match winner |
| L | `player_of_match` | Man of the Match |
| M | `venue` | Stadium name |
| N | `city` | Host city |
| O | `team1_players` | Playing XI — Team 1 |
| P | `team2_players` | Playing XI — Team 2 |

---

## ⚙️ How to Work in the Dashboard

### 1. Open the File
Open `IPL_Dashboard_Final.xlsx` → go to the **IPL DASHBOARD** sheet. Grid lines are hidden and the layout is pre-styled.

### 2. Read the KPI Cards
Three cards at the top show headline numbers — Total Matches, IPL Seasons, and Total Teams.

### 3. Use the Slicer to Filter by IPL Season

1. Click any cell inside the **IPL Data** table
2. Go to **Insert → PivotTable** → place on a new sheet
3. Drag `Season` to **Rows**, `match_number` (Count) to **Values**
4. Click inside the PivotTable → **PivotTable Analyze → Insert Slicer → Season → OK**
5. **Copy** the slicer → paste it onto the **IPL DASHBOARD** sheet
6. Right-click the slicer → **Report Connections** → connect all PivotTables you want it to control
7. Click any season (e.g. **IPL-2025**) to filter everything instantly
8. Hold **Ctrl** to select multiple seasons at once
9. Click the **🚫** icon on the slicer to clear the filter

### 4. Explore the Charts
Each data sheet contains an embedded chart. Copy any chart and paste it onto the dashboard to build your own layout.

### 5. Filter the Raw Data
On the **IPL Data** sheet, Row 1 is frozen and every column has a dropdown filter. Use these to search by team, city, season, or player.

---

## 📈 Key Insights

- **Most titles:** Mumbai Indians & Chennai Super Kings — 5 each
- **2025 Champion:** Royal Challengers Bengaluru (first ever title)
- **Toss strategy:** Teams fielding first win **65.5%** of matches
- **Top MOM (all-time):** AB de Villiers — 25 awards
- **Biggest venue:** Eden Gardens, Kolkata — 77 matches hosted

---

## 📜 License

MIT License — data sourced from publicly available IPL statistics (2008–2025).
