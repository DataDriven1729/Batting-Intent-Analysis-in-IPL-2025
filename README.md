🏏 Batting Intent Analysis in IPL 2025

This project is a detailed **batting intent analysis** using Python and ball-by-ball data from a recent **IPL 2025 match between RCB and DC**.

## 🎯 Objective

To analyze how batters approached the game in different phases — Powerplay, Middle Overs, and Death Overs — by examining:

- 🔹 Strike Rate
- 🔹 Dot Ball Percentage
- 🔹 Boundary Percentage
- 🔹 Over-wise Performance Trends

## 🗂️ Dataset

- 📄 File: `ipl_match_1473461_deliveries.csv`
- Source: Ball-by-ball delivery data from an IPL 2025 match
- Columns include batter, bowler, runs, over, ball, and dismissal info.

## ⚙️ Tools & Technologies

- Python
- pandas, numpy
- matplotlib / seaborn (if plotting used)
- Jupyter Notebook

## 📊 Key Steps

1. **Data Loading & Preprocessing**
   - Imported the match data using pandas
   - Cleaned and structured relevant columns

2. **Phase Classification**
   - Defined `get_phase()` to categorize overs:
     - 0–5 ➝ Powerplay
     - 6–14 ➝ Middle Overs
     - 15–20 ➝ Death Overs

3. **Metric Calculation**
   - Grouped batters by match phase
   - Calculated:
     - 🚀 Strike Rate = (Runs / Balls) × 100
     - ❌ Dot Ball % = (Dot Balls / Total Balls) × 100
     - 💥 Boundary % = (4s + 6s) / Total Balls × 100

4. **Analysis**
   - Compared batter intent across phases
   - Identified aggressive vs defensive players
   - Detected phase-wise performance patterns

## 📌 Insights

- Some players drastically shift intent across phases
- Powerplay and Death overs show higher risk-taking
- Consistent intent across all phases is rare but valuable

## 🔚 Conclusion

This project highlights the power of **intent-based metrics** in performance analysis. It offers real-time decision support for team management and strategic planning.

## 📂 Folder Structure

