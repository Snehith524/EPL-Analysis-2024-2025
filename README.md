# ⚽ EPL 2024–25 Player Stats Analysis

This project contains a complete exploratory data analysis (EDA) of player performance in the **English Premier League 2024–25 season**. It explores individual player stats across goals, assists, passing, defense, and discipline to uncover insights about role-based contributions and performance metrics.

---

## 📁 Dataset Overview

- **Dataset**: `epl_player_stats_24_25.csv`
- **Records**: 562 players
- **Columns Include**:
  - `Player Name`, `Club`, `Nationality`, `Position`
  - `Goals`, `Assists`, `Shots`, `Minutes`
  - `Passes`, `Passes %`, `Conversion %`
  - `Crosses`, `Tackles`, `Interceptions`
  - `Saves`, `Clean Sheets`, `Yellow Cards`, `Red Cards`

---

## 🎯 Project Objectives

- Perform end-to-end data preprocessing and cleaning
- Analyze top-performing players in various roles
- Visualize distribution of key stats like goals, assists, tackles, saves, etc.
- Identify most disciplined and most efficient players
- Provide actionable insights based on real performance metrics

---

## 🛠️ Tools & Technologies

- **Language**: Python 3
- **Libraries**:  
  - `pandas` – data processing  
  - `matplotlib`, `seaborn` – visualizations  
  - `numpy` – numeric operations  
  - `jupyter` – interactive environment

---

## 📊 Key Metrics Explored

### 🥅 Goals
- Top 15 goal scorers identified using sorting.
- Additional breakdowns by player positions (forwards, midfielders).

### 🎯 Assists
- Top 15 assist providers visualized.
- Includes goal + assist contributions (`goal+assist` column).

### 🧠 Passing Accuracy
- Top players by `Passes %` — especially central midfielders and defenders.
- Identified consistent passers with 85%+ accuracy.

### 🚀 Conversion Rate
- Top 15 players with best `Conversion %` — goals per shot.
- Great for identifying clinical finishers.

### 🎯 Crosses
- Most crosses made by fullbacks and set-piece takers.
- Visualized to show high delivery players like Trent and Trippier.

---

## 🧤 Goalkeeping

### 🛡️ Saves
- Goalkeepers with the most total saves.
- Includes breakdown of save numbers and consistency.

### 🧼 Clean Sheets
- Top 15 goalkeepers by clean sheets.
- Insight into teams' defensive solidity.

---

## 🧱 Defensive Stats

### 🥷 Tackles
- Most tackles by defensive midfielders and center-backs.
- Tackle leaders showed high work rate and dueling ability.

### 🛡️ Interceptions
- Interceptions indicate defensive awareness and positioning.
- Highlighted players with high interception counts.

---

## ❌ Discipline Metrics

### 🟨 Yellow Cards
- Players with highest yellow card count — often defenders and aggressive midfielders.

### 🟥 Red Cards
- Players receiving 1 or more red cards during the season.

---

## 🕊️ Most Disciplined Players

- Players with **0 yellow or red cards** and **more than 1710 minutes played**.
- Reflects maturity, positional discipline, and clean tackling.

---

## 🏆 Hat-Tricks

- Players with **2 or more hat-tricks** identified based on goals in a match (if data available).
- Spotlights explosive forwards.

---

## ⏱️ Playtime

- Top 15 most-used players (by minutes played).
- Bottom 15 least-used players also identified.
- Helps assess squad depth and rotation.

---

## 📈 Visualizations Included

- Bar plots: Top scorers, assisters, savers, tacklers
- Horizontal charts: Minutes played, cards, pass/conversion %
- Scatter plots for efficiency (optional)

---

## 📌 Future Enhancements

- Add player **age** to analyze experience vs performance
- Include **team performance aggregation**
- Use **Plotly/Streamlit** for interactive dashboards
- Integrate **injury data** and **match-by-match tracking**

---

## 🧑‍💻 Author

**Gampa Snehith**  
Computer Science Student | Data Analyst  
📍 Portfolio: [GitHub.com/Snehith524](https://github.com/Snehith524)  
📧 Email: gampasnehith383@gmail.com  

---

> “Football is beautiful. Stats just help us see why.”

