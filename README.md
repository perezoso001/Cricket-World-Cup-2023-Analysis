# 🏆 Cricket World Cup 2023 Analysis

*A Complete Exploratory Data Analysis (EDA) Using Python & Google Colab*

## 📌 Project Overview

This project presents a **comprehensive exploratory data analysis
(EDA)** of the **ICC Cricket World Cup 2023**, using four custom-built
datasets. The analysis was carried out using a **Google Colab (.ipynb)**
notebook and focuses on **team performance**, **batting & bowling
statistics**, **pressure situations**, **venue impact**, and **top
player insights**.

## 📂 Dataset Information

### 1️⃣ batting_summary.csv

-   Match_no, Match_Between, Team_Innings, Batsman_Name,
    Batting_Position, Dismissal, Runs, Balls, 4s, 6s, Strike_Rate

### 2️⃣ bowling_summary.csv

-   Match_no, Match_Between, Bowling_Team, Bowler_Name, Overs, Maidens,
    Runs, Wickets, Economy

### 3️⃣ match_schedule_results.csv

-   Match_no, Date, Venue, Team1, Team2, Winner, Scorecard URL

### 4️⃣ world_cup_players_info.csv

-   player_name, team_name, image_of_player, battingStyle, bowlingStyle,
    playingRole, description

## 🧪 Analysis Summary

# 📊 ICC Cricket World Cup 2023 -- Analysis Summary

This document provides a **comprehensive summary** of the analytical
findings from the ICC Cricket World Cup 2023 dataset.

------------------------------------------------------------------------

## 🏆 1. Team Performance Overview

-   **Top-performing teams**:
    -   🇦🇺 **Australia** -- 81.8% win rate (9/11)
    -   🇮🇳 **India** -- 81.8% win rate (9/11)
    -   🇿🇦 **South Africa** -- 70% win rate
-   **Lower-performing teams**: Bangladesh and Netherlands

------------------------------------------------------------------------

## 🏏 2. Batting Strength & Insights

### ⭐ Average Runs Per Wicket

-   **Highest**: New Zealand & India\
-   **Lowest**: England & Netherlands

### ⭐ Batting Order Effectiveness

-   India's **middle order (positions 4--7)** recorded **66.2
    runs/wicket**, the highest among all teams.

### ⭐ Teams with Most 300+ Scores

-   Australia -- 6
-   South Africa -- 6
-   India -- 4

### ⭐ Centuries & Half-Centuries

-   **India**: 25 scores of 50+ (highest)
-   **South Africa**: 11 centuries (most)

------------------------------------------------------------------------

## 🎯 3. Bowling Strength

### ⭐ Total Wickets

-   India -- 99\
-   South Africa -- 88\
-   Australia -- 86

### ⭐ Economy Rate Leaders

-   India\
-   Afghanistan\
-   South Africa

### ⭐ Bowling Average

-   India -- 22.42\
-   South Africa -- 26.41

### ⭐ Strike Rates (Balls per Wicket)

-   India -- 28.09\
-   South Africa -- 29.04

### ⭐ Most "Bowled Out" Performances

-   India -- 7 times

------------------------------------------------------------------------

## 🔥 4. Pressure Situations

### ⭐ Chasing 300+ Runs

-   Very low success across teams\
-   SA, PAK, SL each succeeded *once*

### ⭐ Defending Under 250

-   **100% success**: Afghanistan, Australia, Bangladesh, Pakistan\
-   **India**: 75% success rate

### ⭐ Batting First vs Chasing

-   **Batting first** win rate: **68.8%**\
-   **Chasing** win rate: **31.2%**

### ⭐ Higher Targets → Higher Defense Success

-   Defending 300--349 → **87.5% wins**\
-   Defending 350+ → **80% wins**

------------------------------------------------------------------------

## 💪 5. Players Under Pressure (50+ in Successful Chases)

Players who scored **2 match-winning 50+ scores**: - Aiden Markram\
- David Miller\
- Marnus Labuschagne\
- Quinton de Kock\
- Pathum Nissanka

------------------------------------------------------------------------

## 🏟️ 6. Venue & Toss Impact

### ⭐ Best for Batting First

-   Hyderabad\
-   Chennai

### ⭐ Balanced Venues

-   Mumbai\
-   Kolkata\
-   Bengaluru

### ⭐ Highest Average First Innings Score

-   Hyderabad -- 315\
-   Delhi -- 313.33

------------------------------------------------------------------------

## 🌟 7. Top 10 Player Rankings

### 🥇 Top Run Scorers

1.  Virat Kohli -- 765\
2.  Rohit Sharma -- 597\
3.  Quinton de Kock -- 594

### 🎯 Best Batting Averages (Min 200 Runs)

-   Virat Kohli -- 95.62\
-   Rohit Sharma -- 59.7\
-   Rachin Ravindra -- 57.8

### ⚡ Best Strike Rates (Min 200 Runs)

-   Glenn Maxwell -- 150.3\
-   Heinrich Klaasen -- 136.2

### 🎳 Top Wicket-Takers

-   Mohammed Shami -- 24\
-   Adam Zampa -- 23\
-   Dilshan Madushanka -- 21

### 💥 Best Bowling Strike Rate

-   Mohammed Shami -- 12.20 balls/wicket

------------------------------------------------------------------------

## ✅ Summary

The 2023 Cricket World Cup highlighted: - **India** as the strongest
overall team\
- **South Africa** as the powerhouse batting side\
- **Australia** with consistent top-tier performances\
- Bowlers like **Shami**, **Zampa**, and **Madushanka** dominated
wickets\
- High-pressure situations favored **teams batting first**

This analysis captures the tournament's key trends across batting,
bowling, venues, and match conditions.


## 📝 Project Structure

    Cricket-World-Cup-2023-Analysis/
    ├── data/
    ├── notebooks/
    └── README.md

## ▶️ How to Run the Notebook

1.  Upload CSVs to Colab\
2.  Install libraries\
3.  Run all cells

## 🎯 Conclusion

This analysis provides detailed insights into batting, bowling, venue
impact, and overall team performance for the ICC Cricket World Cup 2023.
