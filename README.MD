# 🏏 IPL Dashboard Power BI Project (2008–2024)

## 📌 Introduction

This Power BI project is focused on analyzing **Indian Premier League (IPL)** matches from **2008 to 2024**. The aim is to convert raw IPL cricket data into **insightful visual dashboards** using Power BI.

IPL is one of the most-watched cricket leagues globally, making it a rich source for data analysis. This project helps uncover:

- 🏆 Which teams have been consistently strong over the years?
- 👑 Who are the best-performing batters and bowlers?
- 🎲 Does the toss impact the match outcome?
- 📈 What trends and patterns can we find across seasons?

---

## 📊 Dashboard Features

- Season-wise match overview
- Toss analysis vs match outcome
- Team vs team win distributions
- Player performance (top batters and bowlers)
- Venue-wise stats and win rates
- Match result types and trends
- Ball-by-ball run analysis

---

## 🧾 About the Dataset

I used two main CSV datasets:

### 1. `matches.csv`

- **Rows:** ~1000
- **Columns:** 21
- **Details:** Match-level information
- **Includes:**
  - Match ID, Season, Date, Venue, City
  - Toss winner, Match winner
  - Player of the Match
  - Result type (normal, tie, no result)

### 2. `deliveries.csv`

- **Rows:** ~260,000+
- **Columns:** 18
- **Details:** Ball-by-ball delivery records for each match
- **Includes:**
  - Batter, Bowler, Runs scored
  - Wickets, Extras, Over and Ball number
  - Match ID linking to `matches.csv`

These datasets together offer **complete IPL history**, allowing us to track both match-level and ball-by-ball stats.

---

## 📂 Files in this Repository

| File/Folder | Description |
|-------------|-------------|
| `IPL_Dashboard.pbix` | Main Power BI dashboard file |
| `matches.csv` | Dataset with match-level data |
| `deliveries.csv` | Dataset with ball-by-ball data |
| `screenshots/` | Preview images of the dashboard |
| `README.md` | This documentation file |

---

## 🖼️ Dashboard Preview

> *(Add screenshots in the `screenshots/` folder and display them here)*

```markdown
![Dashboard Overview](screenshots/dashboard-overview.png)

