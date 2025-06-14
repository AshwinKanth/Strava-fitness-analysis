#  Strava Fitness Data Analysis

## Main Objective:

To analyze user wellness data collected from Fitbit smart devices and uncover actionable insights related to physical activity, sleep behavior, calorie burn, and weight patterns.
The ultimate goal is to support the marketing and product strategy for Stravia by helping them understand how users interact with fitness devices and where interventions can increase engagement and outcomes.



---

## 📦 Project Structure

```
strava-fitness-analysis/
├── data/                     
│   └── cleaned/                   # Cleaned datasets (12 files)
├── python/                        # Jupyter notebook + EDA report
├── sql/                           # SQL scripts, outputs, and report
├── powerbi/                       # Dashboard + Power BI report
```

---

##  Tools & Technologies Used:

| Application	    |               Purpose |
--------------------|------------------------|
| Python (Google Colab)| Performed EDA (Exploratory Data Analysis) using pandas, matplotlib, and seaborn for visualizations                      
|   SQL (DB Browser for SQLite)     |   Used for querying large cleaned datasets to find trends in steps, sleep, calories, and active time                    |
| Power BI            |   Built a 7-page interactive dashboard to visualize trends, filter behavior by user/hour/date, and support strategic recommendations |
| GitHub              | Centralized all project files and documentation for reproducible sharing and submission



---

## 📊 Key Insights

- 💤 **Sleep drops on weekdays** – users sleep more on Sundays (~7.5 hrs)
- 🚶 **Most steps and calories burned** between **12–7 PM**
- 🪑 Users are **sedentary for 12–20 hours/day** despite high step counts
- 🔥 **Step count strongly correlates** with calorie burn
- 🥇 Top users average **16,000+ steps/day** and sleep consistently

---

## 🎯 Recommendations

- 🔔 Send **reminders during inactive hours** and after calorie drop days
- 🎽 Promote **weekday activity and sleep streaks**
- 🏅 Leverage **top users for gamified challenges**
- 📈 Use **time-of-day targeting** to maximize engagement (especially 6 PM peak)

---

## Summary

By combining data cleaning, statistical queries, and interactive visuals, this project offers a 360° view of user behavior across:

* Daily & hourly step patterns

* Sleep consistency by weekday

* Calorie trends linked to activity levels

* Sedentary vs. active time distribution

* Most engaged and healthiest users

These insights help Stravia build data-driven product features such as personalized nudges, gamified challenges, and recovery tracking.

## 📁 Reports Available

- **Python (EDA)** → `Strava_fitness.ipynb` + PDF summary
- **SQL** → `bellabeat_analysis.sql` + PDF with queries and insights
- **Power BI** → `.pbix` dashboard + report with 7 pages of visuals

