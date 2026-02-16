# IPL Data Analysis (2008–2024)

## Introduction
This project analyzes the Indian Premier League (IPL) from 2008 to 2024 using Python data analysis and visualization tools. The dataset includes detailed information about matches, teams, seasons, venues, and players.

The objective of this project is to understand team performance, player contributions, match trends, and the impact of toss decisions using Exploratory Data Analysis (EDA) and basic Machine Learning techniques.

---

## Project Type
- Exploratory Data Analysis (EDA)
- Sports Analytics
- Basic Machine Learning (Classification)

---

## Dataset Description

### matches.csv
Columns include:
- id
- season
- city
- date
- team1
- team2
- toss_winner
- toss_decision
- winner
- player_of_match
- venue
- result_margin
- umpires

### deliveries.csv
Contains ball-by-ball match data including:
- Runs scored
- Wickets taken
- Over details
- Batsman and bowler information

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Data Understanding & Cleaning (Using Pandas)

- Loaded datasets using Pandas
- Checked data types and missing values
- Removed duplicates
- Handled missing entries (e.g., unknown umpires or match results)
- Converted date column to datetime format
- Merged matches.csv and deliveries.csv for advanced analysis

---

# Exploratory Data Analysis (EDA)

### 1. Total Matches per Season
- Analyzed IPL growth over the years

### 2. Most Successful Teams
- Counted total match wins per team
- Identified dominant franchises

### 3. Toss Analysis
- Most toss-winning teams
- Comparison between toss-winning and match-winning

### 4. Venue Analysis
- Stadiums hosting the most matches
- Venue-based winning patterns

### 5. Player Analysis
- Most “Player of the Match” awards
- Highest run-scorers (from deliveries data)
- Highest wicket-takers

### 6. Run-Scoring Patterns
- Powerplay performance
- Death over scoring trends
- Season-wise average team scores

### 7. Team Rivalries
- Head-to-head statistics (e.g., MI vs CSK)

---

# Data Visualization (Matplotlib & Seaborn)

- Bar Charts → Wins per team
- Line Charts → Season-wise trends
- Pie Charts → Toss decision split
- Heatmaps → Team win comparisons
- Scatter plots → Runs vs Overs analysis

---

# Machine Learning Component

A basic classification model was built to analyze whether:
- Winning the toss increases the probability of winning the match.

Algorithm Used:
- Logistic Regression (or similar classification model)

Result:
- Toss-winning does not always guarantee match victory.

---

# Key Insights

- Mumbai Indians and Chennai Super Kings are the most successful teams overall.
- Toss-winning does not strongly guarantee match-winning.
- Average team scores have increased after 2015, indicating more aggressive batting strategies.
- Certain venues like Wankhede and Eden Gardens favor chasing teams.
- Consistent “Player of the Match” winners highlight top-performing players.

---

# Project Summary

- Analyzed IPL matches from 2008–2024.
- Identified top teams, players, and match trends.
- Visualized season-wise performance and toss impact.
- Built a simple ML model to analyze toss influence.
- Demonstrated how sports analytics helps understand competitive performance.

---

## Conclusion
This project showcases how data analytics and machine learning can be applied to sports data to extract meaningful insights. It highlights team dominance, player impact, scoring evolution, and match strategies across 17 IPL seasons.
