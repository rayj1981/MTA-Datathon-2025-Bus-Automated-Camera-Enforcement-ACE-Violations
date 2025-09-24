# 🚍 Bus Lanes, ACE, and Congestion Pricing: Impacts on CUNY Communities

## 📌 Overview
This project investigates how **Automated Camera Enforcement (ACE)** and upcoming **Congestion Pricing** affect bus performance in New York City, with a focus on **CUNY campuses**.

🚍 Challenge 1: CUNY Student Reliance & ACE Impact
Goal: Identify key bus routes for CUNY students and measure ACE's effect on their speed/reliability.

🚗 Challenge 2: Exempt Vehicle Violations & Hotspots
Goal: Find patterns in violations from exempt vehicles (government, diplomatic plates) and identify geographic hotspots.

🗺️ Challenge 3: Manhattan's CBD & Congestion Pricing
Goal: Analyze the current state of ACE in the CBD and model the potential impact of congestion pricing.


---

## 🗂️ Data Sources
- **MTA Bus Speeds (2020–2024)** — NYC Open Data  
- **Automated Camera Enforcement Violations (2019–2025)** — NYC Open Data  
- **Bus Lanes Shapefile** — NYC DOT Open Data  
- **CUNY Campus Locations** — NYC Open Data  
- **Congestion Pricing Zone (CBD boundary)** — NYC DOT  

---

## 🔍 Methodology
1. **Data Integration**  
   - Collected bus speed data from 2020–2024 and linked it with Automated Camera Enforcement (ACE) violations.  
   - Mapped CUNY campus locations and overlaid them with ACE-enforced bus routes.  
   - Incorporated the Central Business District (CBD) boundary to assess congestion pricing impacts.  

2. **Spatial Analysis**  
   - Used geospatial joins to identify violations occurring inside vs. outside the CBD.  
   - Cross-referenced ACE bus corridors with proximity to CUNY campuses.  
   - Produced violation heatmaps to identify hotspots of bus lane blockages.  

3. **Temporal Trends**  
   - Compared average bus speeds before ACE (2020–2022) vs. after rollout (2023–2024).  
   - Examined violation patterns by time of day and day of week.  
   - Identified peak congestion and enforcement periods.  

---

## 📊 Key Findings
- **Bus Speeds Improved on ACE Routes**  
  - Example: The **M101** saw a **+13% speed increase**, the **M2** +12%, and the **M42** +4%.  
  - Improvements were strongest on corridors with consistent ACE enforcement.  

## Comparative Analysis of Bus Speeds

The following chart compares average bus speeds before and after the implementation of key initiatives like the Automated Camera Enforcement (ACE) program, highlighting trends from 2020-2023 versus 2023-2024.

![Comparison of Bus Speeds 2020-2023 vs 2023-2024](https://github.com/rayj1981/MTA-Datathon-2025-Bus-Automated-Camera-Enforcement-ACE-Violations/blob/main/Pictures/comparison_bus_speeds_2020-2023_vs_2023-2024.png)


- **Violations Cluster in Busy Midtown Corridors**  
  - Hotspots align with **major commercial avenues** (e.g., 42nd Street, 14th Street).  
  - Violations peak **midday (12–2 PM)** and **evening (5–7 PM)** — overlapping with student commuting hours.  

## Temporal Analysis of Violation Statuses

This chart breaks down the status of ACE violations (e.g., Paid, Open, Disputed) by the hour of the day they were issued. This temporal analysis reveals patterns in driver compliance and dispute behavior throughout the day.

![Violations by Status Across Hours of the Day](https://github.com/rayj1981/MTA-Datathon-2025-Bus-Automated-Camera-Enforcement-ACE-Violations/blob/main/Pictures/violations_by_status_across_hours.png)

## Peak Violation Heatmap Analysis

This heatmap provides a detailed view of ACE violation frequency, analyzing patterns across both hours of the day and days of the week. It identifies specific time windows where bus lane incursions are most concentrated.

![Heatmap of ACE Violations by Hour and Day of Week](https://github.com/rayj1981/MTA-Datathon-2025-Bus-Automated-Camera-Enforcement-ACE-Violations/blob/main/Pictures/HEATMAP%20PICTURE.PNG)



- **Congestion Pricing Likely to Amplify ACE Benefits**  
  - By reducing private vehicle trips into the CBD, congestion pricing could further cut delays.  
  - Expected synergy: **fewer violators + lower traffic volumes = faster buses.**
  
## Geographic Analysis of Bus Speeds

This map visualizes bus routes in New York City's Central Business District (CBD), colored by their average speed. The spatial representation helps identify corridors with persistent congestion and areas where interventions like ACE have had the most significant impact.

![CBD Bus Routes Colored by Average Speed](https://github.com/rayj1981/MTA-Datathon-2025-Bus-Automated-Camera-Enforcement-ACE-Violations/blob/main/Pictures/CBD_routes_colored_by_average_speed.png)
---

## 🎓 Impact on CUNY Communities
- **Accessibility:** Faster buses reduce commute times for thousands of students who rely on them daily.  
- **Equity:** Many CUNY students come from outer boroughs — ACE and congestion pricing make travel more reliable without additional cost.  
- **Safety:** Clearer bus lanes mean fewer pedestrian conflicts and safer streets around campuses.  

