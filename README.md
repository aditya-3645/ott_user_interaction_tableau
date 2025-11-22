# 📊 OTT User Behavior Analysis — Dashboard Preview  
![Dashboard Preview](https://github.com/aditya-dhumal-30/Ott_user_analysis_report/blob/be72b2805ff04c281ca3f07e28b2596381c47757/Screenshot%202025-11-21%20102123.png)

---

## 🔍 Project Overview  
This project delivers an end-to-end analysis of user behavior on an OTT streaming platform using four core datasets: **Watch History**, **User Profiles**, **Preferred Genres**, and **Content Catalog**.

The dataset spans **nine years (2015–2023)**, covering the **first five months of each year**.  
The objective is to build a robust analytical data model and an interactive **Tableau dashboard** that uncovers viewing trends, engagement patterns, and content performance insights.

---

## 📁 Datasets  
- 📄 **Watch History** – Session-level data: timestamps, session length, completion rate  
  ➤ https://github.com/aditya-dhumal-30/Ott_user_analysis_report/commit/a0dc9224ea2668ed4f0f7d83d897b6a3d5f0da24  

- 👤 **User Profiles** – Account attributes and demographic fields  
  ➤ https://github.com/aditya-dhumal-30/Ott_user_analysis_report/blob/main/profiles.csv  

- 🎧 **Preferred Genres** – Genre-level preferences per user profile  
  ➤ https://github.com/aditya-dhumal-30/Ott_user_analysis_report/blob/main/profile_preferred_genres.csv  

- 🎬 **Content Catalog** – Metadata including genre, duration, release year, popularity  
  ➤ https://github.com/aditya-dhumal-30/Ott_user_analysis_report/blob/main/content_catalog.csv  

---

## 🚀 Project Highlights  
- Multi-year trend analysis for the first five months of **2015–2023**  
- Computed engagement KPIs: **Watch Time**, **Avg. Session Duration**, **Completion %**, **Session Count**  
- User segmentation based on demographics and genre affinities  
- Designed an optimized **relational data model** for Tableau  
- Developed an interactive dashboard featuring drill-downs, dynamic KPIs, and parameter switching  

---

## 🧠 Tableau Concepts Applied  

### 🔗 Data Joins & Blending  
- Defined primary–foreign key relationships  
- Used inner and left joins for referential integrity  

### 🧮 Calculated Fields  
- KPI formulas: Watch Time, Completion %, Session Count  
- Date parsing, logical operations, string functions, numeric aggregations  

### 🏷 Level of Detail (LOD) Expressions  
- Used **FIXED**, **INCLUDE**, **EXCLUDE** LODs  
- Ensured KPI accuracy under filters  

### 🎚 Parameters  
- Built dynamic parameters for KPI switches and user selections  

---

## 🚀 Steps to Download & Run the Project  
1. Open the project’s **GitHub page**  
2. Click **Code → Download ZIP**  
3. Unzip the downloaded folder  
4. Locate the **.twb / .twbx** Tableau file  
5. Open it in **Tableau Desktop**  

---
