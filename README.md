# 🏏 IPL Data Analysis & Match Winner Prediction

##  Project Overview
This project performs **Exploratory Data Analysis (EDA)**, builds a **Random Forest Classifier** to predict IPL match winners, and presents insights through a **Power BI interactive dashboard**.  

It uses two datasets:
- `cleaned_matches.csv`
- `cleaned_deliveries.csv`

---

##  Dataset Description
### 1. `cleaned_matches.csv`
Contains match-level data:
- `id` — Match ID  
- `season` — Year of the match  
- `city` — Venue city  
- `winner` — Winning team  
- `toss_winner` — Toss-winning team  
- `toss_decision` — Bat/Field choice  

### 2. `cleaned_deliveries.csv`
Contains ball-by-ball data:
- `match_id` — Match reference  
- `inning` — Innings number  
- `batting_team`, `bowling_team`  
- `batter`, `bowler`  
- `batsman_runs`  
- `is_wicket`  

---

##  Machine Learning Model
**Algorithm:** Random Forest Classifier  
**Purpose:** Predict the winning team based on match context.  

**Why Random Forest?**
- Handles categorical and numerical features effectively
- Captures non-linear relationships between match factors
- Reduces overfitting compared to a single decision tree

**Evaluation Metrics:**
- Accuracy score
- Classification report

---

## 📊 Power BI Dashboard
The **Power BI Dashboard** provides:
- Year-wise team performance
- Player statistics (batting & bowling)
- Toss decision impact
- Venue-wise win patterns

 **File:** `IPL POWER BI dashboard.pbix`  
You can open it in Power BI Desktop to explore interactive visuals.

---

 **File:** `IPL_TABLEAU.twb`  
You can open it in Tableau to explore interactive visuals.

---

## 📦 Requirements
Install dependencies:
```bash
pip install -r requirements.txt