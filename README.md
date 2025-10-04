# IPL Data Analysis Dashboard (Power BI)

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Key Features](#key-features)
4. [Dashboard Highlights](#dashboard-highlights)
5. [Power BI Techniques Used](#power-bi-techniques-used)
6. [Usage](#usage)
7. [Insights & Outcomes](#insights--outcomes)
8. [Technologies](#technologies)

---

## Project Overview
The **IPL Data Analysis Dashboard** is an interactive Power BI project designed to provide **comprehensive insights into player and team performance** across multiple IPL seasons and matches. By integrating **ball-by-ball and match-level datasets**, this dashboard enables **analysts, team managers, and IPL enthusiasts** to explore trends, evaluate performances, and make informed decisions based on historical IPL data.  

Key objectives:
- Analyze **player and team performance** over multiple IPL seasons and 200+ matches.
- Compare team performance metrics across matches and seasons.
- Facilitate **data-driven decision-making** with interactive visuals and detailed evaluation metrics.

---

## Dataset
The dashboard is built on two primary IPL datasets:

### 1. Ball-by-Ball Dataset (`deliveries.csv`)
Contains detailed information for each ball of the IPL matches:

| Column Name       | Description |
|------------------|-------------|
| match_id          | Unique identifier for each match |
| inning            | Inning number (1 or 2) |
| batting_team      | Team batting in the delivery |
| bowling_team      | Team bowling in the delivery |
| over              | Over number |
| ball              | Ball number within the over |
| batsman           | Name of the batsman on strike |
| non_striker       | Non-striking batsman |
| bowler            | Name of the bowler |
| is_super_over     | Indicator for super over |
| wide_runs         | Runs scored as wides |
| bye_runs          | Runs scored as byes |
| legbye_runs       | Runs scored as leg byes |
| noball_runs       | Runs scored as no-balls |
| penalty_runs      | Penalty runs awarded |
| batsman_runs      | Runs scored by the batsman |
| extra_runs        | Total extra runs in the delivery |
| total_runs        | Total runs scored in the delivery |
| player_dismissed  | Player dismissed, if any |
| dismissal_kind    | Method of dismissal |
| fielder           | Fielder involved in dismissal, if any |

### 2. Match-Level Dataset (`matches.csv`)
Contains match summary and metadata for IPL matches:

| Column Name       | Description |
|------------------|-------------|
| id                | Match identifier |
| season            | IPL season |
| city              | City where match was played |
| date              | Match date |
| team1             | First team |
| team2             | Second team |
| toss_winner       | Team that won the toss |
| toss_decision     | Decision made by toss winner |
| result            | Match result |
| dl_applied        | Duckworth-Lewis method applied indicator |
| winner            | Match winner |
| win_by_runs       | Margin of win by runs |
| win_by_wickets    | Margin of win by wickets |
| player_of_match   | Player of the match |
| venue             | Match venue |
| umpire1           | First umpire |
| umpire2           | Second umpire |
| umpire3           | Third umpire (if any) |

---

## Key Features
- Integrated **ball-by-ball and match-level IPL datasets** for a unified analysis framework.
- Interactive **player and team performance metrics** with drill-down capabilities.
- Visualizations to identify **top-performing players, teams, and venues** in IPL history.
- Advanced **trend analysis** for runs, wickets, and performance across IPL seasons.
- Comparative analytics for **team head-to-head matchups**.
- **Filterable dashboard** by season, team, player, venue, and match outcome.

---

## Dashboard Highlights
- **Team Performance:** Visuals comparing cumulative runs, wickets, and win ratios.
- **Player Insights:** Batting and bowling performance dashboards highlighting top scorers and wicket-takers.
- **Match Trends:** Interactive charts for match results, toss decisions, and performance patterns.
- **Seasonal Analysis:** Line and bar charts tracking performance trends over IPL seasons.
- **Head-to-Head Metrics:** Compare historical performance between any two IPL teams.
- **Interactive Slicers:** Filters for season, team, player, venue, and match type.

---

## Power BI Techniques Used
- **Data Modeling:** Relationships between `deliveries.csv` and `matches.csv` optimized for analysis.
- **DAX Measures:** Custom measures for Total Runs, Wickets, Strike Rate, Economy Rate, and Win Percentage.
- **Drill-Through & Cross-Filtering:** Explore match and player-level details dynamically.
- **Conditional Formatting:** Highlight key metrics like high scores, low economy rates, and top performers.
- **Custom Visuals:** Applied slicers, clustered bar charts, line charts, and tables for comprehensive storytelling.
- **Performance Optimization:** Aggregations and calculated columns for fast rendering of large IPL datasets.

---

## Usage
1. Open **IPL Data Analysis Dashboard.pbix** in Power BI Desktop.
2. Connect to the provided **ball-by-ball and match datasets** (`deliveries.csv` and `matches.csv`).
3. Use **interactive slicers** to filter data by:
   - Season
   - Team
   - Player
   - Venue
   - Match outcome
4. Explore **drill-through visuals** for detailed match-level and player-level insights.
5. Export visuals or reports for presentations or stakeholder meetings.

---

## Insights & Outcomes
- Identified **top-performing IPL teams and players** across seasons.
- Evaluated impact of **toss decisions on match outcomes**.
- Tracked seasonal trends in **runs, wickets, and win margins**.
- Compared **player head-to-head performances** across matches.
- Supported **data-driven decisions** for match analysis, commentary, and team strategy evaluation.

---

## Technologies
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **CSV datasets** for ball-by-ball and match summaries
- Interactive visuals for trend and performance analysis

---

## Project Structure
 - IPL Data Analysis Dashboard.pbix
 - deliveries.csv
 - matches.csv
 - README.md


**Dashboard Components:**
- **Team Analysis:** Total runs, wickets, win ratio, and head-to-head comparisons.
- **Player Performance:** Batting and bowling metrics with rankings and filters.
- **Match-Level Insights:** Drill-through pages for detailed match stats.
- **Seasonal Trends:** Multi-season visualizations and trend lines.
