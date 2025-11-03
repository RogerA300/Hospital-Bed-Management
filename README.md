# Hospital-Bed-Management
In sighting trends and how staff and schedules correlate with patients and satisfaction.


# Hospital Bed Management Analytics Project  

# Overview  
This project explores **hospital operations and efficiency** through data-driven insights.  
Using Python and MySQL, we analyze patient admissions, service demand, and satisfaction metrics to uncover trends that reflect real-world healthcare capacity challenges.

The goal is to demonstrate **data analytics and visualization skills** in a hospital operations context — from importing and cleaning data to deriving actionable insights.

---

# Tech Stack  
- **Database:** MySQL  
- **Language:** Python  
- **Libraries:** Pandas, SQLAlchemy, Matplotlib, Seaborn  
- **Visualization Tools:** Matplotlib, Seaborn, (optional Power BI integration)  
- **Focus Areas:** Data cleaning, exploratory data analysis, capacity utilization, and patient satisfaction analytics  

---

# Dataset Summary  

| Table | Description |
|--------|--------------|
| `patients` | Contains patient demographics, satisfaction scores, and length of stay |
| `staff` | Lists active hospital personnel and their roles |
| `services_weekly` | Weekly hospital performance metrics such as requests, admissions, and bed occupancy |
| `staff_schedule` | Mock schedule data (excluded from analysis) |

---

# 1. Services Weekly Insights  

# Key Findings  
| Metric | Observation | Interpretation |
|--------|--------------|----------------|
| **Avg Weekly Requests:** 65 | High variability (5–388 requests per week) | Indicates inconsistent patient inflow |
| **Avg Weekly Admissions:** 28 | ~65% of requests admitted | Suggests limited hospital capacity |
| **Avg Refusals:** 37 | Often exceeds admissions | Reflects frequent over-demand periods |
| **Bed Occupancy Rate:** 92% avg (often 100%) | Hospital operates near full capacity | Minimal flexibility during surges |
| **Satisfaction–Morale Correlation:** 0.008 | No strong relationship | Possibly due to mock dataset limitation |

# Visual Insights  
- **Patient Demand vs Admissions:** Shows clear bottlenecks when weekly requests spike.  
- **Bed Occupancy Distribution:** Most weeks at or near 100%, confirming limited spare capacity.  
- **Satisfaction vs Staff Morale:** Flat trend line, reinforcing need for better morale tracking data.

# Takeaway  
> The hospital is **operating at near-maximum capacity**, limiting its ability to handle patient surges.  
> Future focus should be on **forecasting**, **bed allocation strategies**, and **enhanced satisfaction-morale monitoring**.

---

# 2. Patients Data Correlation Insights  

# Relationship Findings  
| Correlation | Strength | Interpretation |
|--------------|-----------|----------------|
| **Length of Stay ↔ Satisfaction** | Moderate Negative | Longer stays slightly reduce satisfaction — possible fatigue or recovery stress. |
| **Age ↔ Length of Stay** | Moderate Positive | Older patients tend to stay longer, reflecting care complexity. |
| **Service Type ↔ Average Stay** | Variable | Intensive care and surgical departments show longest recovery periods. |

# Visual Insights  
- Regression plots for **Length of Stay vs Satisfaction** and **Age vs Stay Duration**.  
- Bar charts for **Average Stay per Service Type**.

# Takeaway  
> **Satisfaction decreases** as hospital stay increases — patient experience improvements should target longer-term admissions.  
> **Elderly populations** require longer stays, highlighting a need for effective discharge and follow-up planning.

---

# Project Reflection  

| Skill Area | Demonstrated Application |
|-------------|--------------------------|
| **Data Engineering** | Imported CSVs into MySQL and queried using SQLAlchemy |
| **EDA & Visualization** | Analyzed trends with Pandas, Matplotlib, and Seaborn |
| **Healthcare Insight** | Identified relationships between operational and satisfaction metrics |
| **Data Communication** | Summarized results into a clear, professional report |

> This project showcases both **technical proficiency** and **analytical storytelling** — translating healthcare data into meaningful operational insights.

---

  
**Roger Anderson**  
 * Data Analyst | SQL • Python • Power BI*  
 [GitHub Portfolio](https://github.com/) *(https://github.com/RogerA300/Hospital-Bed-Management/edit/main/README.md)*  

---

