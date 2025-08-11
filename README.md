# IPL Data Analysis & Machine Learning Models

##  Overview
This project analyzes IPL (Indian Premier League) data using **Exploratory Data Analysis (EDA)** and implements multiple **Machine Learning algorithms** for prediction and clustering.  
It also includes **Power BI** and **Tableau dashboards** for interactive visualizations.

We use two datasets:
- `cleaned_matches.csv` — Match-level information
- `cleaned_deliveries.csv` — Ball-by-ball details

---

## Dataset Description

### 1️ `cleaned_matches.csv`
| Column          | Description |
|----------------|-------------|
| `id`           | Match ID |
| `season`       | Year of the match |
| `city`         | Venue city |
| `winner`       | Winning team |
| `toss_winner`  | Toss-winning team |
| `toss_decision`| Bat/Field choice |

### 2 `cleaned_deliveries.csv`
| Column         | Description |
|----------------|-------------|
| `match_id`     | Match reference |
| `inning`       | Innings number |
| `batting_team` | Batting team |
| `bowling_team` | Bowling team |
| `batter`       | Name of batsman |
| `bowler`       | Name of bowler |
| `batsman_runs` | Runs scored by batsman |
| `is_wicket`    | Wicket indicator |

---

##  Exploratory Data Analysis (EDA)
- Team performance over seasons
- Toss decision impact on match outcome
- Venue-based win patterns
- Player batting & bowling performance
- Run distributions & wicket patterns

---

##  Machine Learning Models Implemented

### **Classification Algorithms**
1. **Decision Tree Classifier**  
2. **Random Forest Classifier**  
3. **K-Nearest Neighbors (KNN)**  
4. **Support Vector Machine (SVM)**  
5. **Logistic Regression**

**Goal:** Predict match winners and classify matches based on historical data.

---

### **Regression Algorithms**
1. **Linear Regression** — Predict runs scored  
2. **Logistic Regression** — Predict probability of win/loss  

---

### **Clustering Algorithms**
1. **K-Means Clustering** — Group players by performance  
2. **Hierarchical Clustering** — Identify similar players/teams  
3. **DBSCAN** — Detect outlier performances

---

##  Visualization
- **Power BI Dashboard (`IPL_POWERBI.pbix`)**
  - Season-wise win stats
  - Player performance
  - Toss impact
  - Venue statistics
- **Tableau Dashboard (`IPL_TABLEAU.twb`)**
  - Similar visuals, fully interactive

---

##  Requirements
Install dependencies:
```bash
pip install -r requirements.txt
