# 📊 Project 2: Batting Intent Analysis in IPL 2025 using Python

This project is part of my **Data Science Portfolio** as an aspiring analyst. The goal was to explore player performance in IPL 2025 using a custom metric called **Intent Index** to measure batting aggression and strategy during different phases of a T20 match.

---

## 🧠 Objective

Analyze IPL 2025 ball-by-ball data to understand:
- Batting intent across different overs (Powerplay, Middle, Death)
- Player-wise aggression patterns
- Impact of match situations on batting behavior
- Insights to assist team analysts, coaches, and strategists

---

## 🗂️ Dataset Details

- 🏏 **Name:** ipl_2025_ball_by_ball.csv  
- 🧾 **Rows:** Ball-by-ball data from all IPL 2025 matches  
- 🧩 **Columns:** 10+  
- 🏷️ **Key fields:** Batter, Bowler, Runs Off Bat, Extras, Over, Ball, Wickets, Match ID, Teams  
- 📌 **Source:** Kaggle / Compiled match data for IPL 2025

---

## 🛠️ Tools & Libraries

- **Python**
- **Pandas** – Data cleaning & transformation  
- **Matplotlib & Seaborn** – Visual trend analysis  
- **Jupyter Notebook** – Interactive analysis  
- *(Optional)* Streamlit – For dashboard version

---

## 🔢 Key Metric: Intent Index

A custom metric to estimate a player’s batting intent using:

Intent Index = (Boundaries + Strike Rotation Score) / Balls Faced

yaml
Copy
Edit

- Higher index → aggressive gameplay  
- Adjusted for over-phase context (Powerplay, Middle, Death)

---

## 📊 Key Insights

- 🚀 **Powerplay** showed the highest batting intent across teams  
- 💥 Finishers like **Nicholas Pooran**, **Glenn Maxwell**, and **Hardik Pandya** had the most consistent high intent
- 🧠 Experienced batters showed **situational adaptability** rather than blind aggression
- 🧮 Intent scores correlated well with match-winning contributions

---

## 📈 Visualizations

- Player-wise Intent Index comparison  
- Phase-wise intent (Powerplay vs Middle vs Death)  
- Heatmaps for batting intent by batting position  
- Team-level average intent index  
- Intent variation by match context (wickets left, chase/defend)

*(All visuals included in notebook and PDF report)*

---

## 📁 Folder Structure

Project2_IPL2025_Batting_Intent
├── IPL_2025_Batting_Intent_Analysis.ipynb
├── ipl_2025_ball_by_ball.csv
├── Batting_Intent_Visuals/
├── Intent_Index_Report.pdf
├── README.md

yaml
Copy
Edit

---

## 🧾 Deliverables

- ✔️ Cleaned & structured IPL ball-by-ball dataset  
- ✔️ Computation of custom intent index  
- ✔️ Exploratory and trend analysis using Python  
- ✔️ Clear visual storytelling of insights  
- ✔️ Final PDF report with key takeaways  

---

## 📌 Author

**Nusrat**  
_Software Trainer | Aspiring Data Analyst | Cloud & Big Data Enthusiast_  
[LinkedIn](https://www.linkedin.com/in/mnusratgulbarga/) • [GitHub](https://github.com/NusratGulbarga)

---

> 🔖 Built as part of my data science portfolio  
> 📌 Hashtags: #IPL2025 #BattingIntent #SportsAnalytics #PythonEDA #CricketData #NusratProjects
