# 📊 Bellabeat Consumer Health Data Analysis

## 📄 Project Overview & Summary

### About Bellabeat
Bellabeat is a high-tech manufacturer of health-focused products for women. They design smart devices—such as wellness trackers, smartwatches, and smart water bottles—that monitor activity, sleep, stress, and hydration to empower women with personalized health insights.

### Business Objective
Analyze non-Bellabeat smart device usage data (Fitbit datasets) to uncover consumer behavioral trends and movement habits. The insights gained will help guide marketing strategies for Bellabeat's product line and identify new growth opportunities.

### Key Questions Addressed
1. What are some trends in smart device usage?
2. How could these trends apply to Bellabeat customers?
3. How can these trends help influence Bellabeat’s marketing strategy?

---

## 🛠️ Technical Workflow & Analysis Highlights

* **Tools Used:** Python (`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`), Jupyter Notebooks.
* **Data Processing:** Cleaned and merged daily activity, step, and sleep tracking datasets; filtered out non-wear days to isolate genuine user habits.
* **Exploratory Insights:** Identified a bimodal distribution in user behavior (clustering heavily into high-activity vs. highly sedentary segments) and evaluated how activity volume impacts overall sleep efficiency.
* **Visualization:** Custom side-by-side panel visualizations mapping daily active minutes against sleep metrics to highlight user engagement trends.
## 🎯 Key Answers & Data-Driven Recommendations

### 1. What are the key trends in smart device usage?
* **Sedentary Dominance:** Users spend an overwhelmingly large percentage of their waking day in sedentary states compared to active minutes.
* **Sleep Impact:** Sedentary minutes show a significant negative correlation with total time asleep ($r = -0.59$), indicating that high daytime inactivity directly impairs sleep quality and duration.

### 2. How do these trends apply to Bellabeat customers?
* Bellabeat users seeking overall wellness often focus heavily on workout minutes, but the underlying barrier to better recovery and sleep health is prolonged, unmonitored daytime sitting.

### 3. How can these trends influence Bellabeat’s marketing strategy?
* **Product Positioning:** Shift marketing messaging from just tracking intensive workouts to driving *holistic daily movement* (e.g., active breaks throughout the workday).
* **Smart App Notifications:** Feature predictive "Inactivity & Sleep Warnings" within the Bellabeat app—notifying users when their sedentary threshold risks damaging their sleep recovery for that night.
* **Targeted Engagement:** Schedule wellness nudges during peak sedentary periods (early afternoon) to encourage light activity before post-work hours.
