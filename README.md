# Video Performance Analysis (Power BI)

## 📊 Project Overview
This project analyzes video monetization performance by visualizing cumulative earnings over time, normalized by days since publish.

By focusing on lifecycle performance rather than calendar dates, the report enables fair comparison of videos published at different times.

---

## ❓ Problem Statement
Using calendar dates to compare video performance makes it difficult to:
- Evaluate true lifecycle performance
- Compare videos published at different times
- Identify top-performing content fairly

A normalized, time-based approach is required to assess how videos perform after publication.

---

## ✅ Solution
I built a Power BI report that:
- Defines **publish date** as the first recorded activity per video
- Calculates **days since publish**
- Uses **DAX cumulative measures** to track earnings growth over time
- Applies a **Top N filter** based on total earnings to highlight the highest-performing videos

---

## 🧠 Key Features
- Cumulative earnings by days since publish
- Per-video lifecycle performance comparison
- Top N video ranking by total earnings
- Interactive filtering for time-based analysis

---

## 🛠 Tools & Technologies
- Power BI Desktop
- DAX (cumulative calculations, ranking)
- Data modeling
- Time-based analysis
- Dashboard design

---

## 📷 Dashboard Preview
<img width="1329" height="743" alt="image" src="https://github.com/user-attachments/assets/2df6551d-0d86-49e1-93d5-673c7e632f8f" />


---

## 📂 Repository Contents
- `[Video_Performance_Analysis.pbix](https://github.com/Ivbuena/video-performance-analysis-powerbi/blob/main/Cumulative%20Video%20Earnings%20Analysi.pbit))` – Power BI report file  
- `README.md` – Project documentation  

---

## 💡 Outcome
This analysis helps stakeholders:
- Identify videos with strong early monetization
- Compare long-term vs short-term performance trends
- Make data-driven decisions using normalized lifecycle data

---

## 📌 Notes
- Dataset used is anonymized / sample data
- PBIX file included for portfolio demonstration purposes
