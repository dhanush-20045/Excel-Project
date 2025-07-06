
# Call Center Report Dashboard – 2023 

## Problem Statement 

  The call center needed a visual dashboard to analyze call volume, revenue, agent performance, customer satisfaction, and gender-wise distribution across cities, enabling
  
  better decision-making and performance tracking.
  
---

## Objectives

1. Provide a centralized **dashboard view** to analyze performance metrics.
 
2. Enable **interactive filtering** by representative.

3. Track **monthly and weekly trends** in calls and performance.
   
4. Identify **customer satisfaction levels** using rating distribution.
   
5. Highlight **key metrics** like total calls, revenue, and average rating.

---

## Key Metrics Tracked

| Metric            | Description |
|-------------------|-------------|

|  Calls         | Total number of calls handled (overall and by agent) |

|  Amount        | Revenue generated from calls |

|  Duration      | Total call duration (in minutes or seconds) |

|  Average Rating | Average customer feedback score (scale of 1 to 5) |

|  Happy Calls   | Number of calls with high satisfaction rating |

|  Gender Split  | Customer gender distribution across cities |

---

## Dashboard Sections

-  Top KPIs (Left Panel): High-level stats like total calls, amount, average rating, duration, and happy calls.
  
  1) Call Trend (Top Middle): Line graph of monthly call volume.
 
  2) Day-wise Trend (Top Middle-Right): Bar chart showing calls by day of the week.
 
  3) Gender Distribution (Top Right): Stacked bar chart showing male/female breakdown by city.
 
  4) Rating Distribution (Top Right): Histogram of customer feedback ratings (1–5).
  
  5) Performance by Representative (Middle): Bar charts showing calls and revenue per rep.
 
  6) Detailed Table (Bottom Right): City and agent-wise breakdown of revenue contributions.
  
  7) Interactive Filter (Middle Right): Dropdown slicer to focus analysis on specific agents.

---

## Steps Implemented

1) Data Collection: Gathered call records including call ID, city, agent ID, duration, amount, rating, gender, and call date.

2) Data Cleaning & Preparation:

   - Removed duplicates and blank rows.
     
   - Converted date/time fields to proper format.
     
   - Calculated derived metrics like "Happy Calls" and "Average Rating."

3) Pivot Table Creation:
   
   - Built summarized pivot tables by city, representative, and month.
     
   - Aggregated values for calls, duration, amount, and ratings.

4) Dashboard Design:

   - Used Excel charts (line, bar, stacked bar, column) for trend visualizations.
     
   - Added slicers for interactivity (e.g., representative filter).
     
   - Applied conditional formatting in the detailed table for visual ranking.

5) Styling & Layout:
   
   - Consistent color theme (orange-red) for readability.
     
   - KPI cards for quick glance metrics.
     
   - Human-friendly formatting for currency and percentages.

---

## 💡 Insights Generated

1) October had the highest call volume spike.

2) Wednesday saw the most customer calls.

3) Cleveland** had the highest female call volume.
   
4) Representative R03 ranked **1st** in revenue generation and **2nd** in call volume.

5) Most customers gave ratings of **4 and 5**, indicating good service levels.

---

## 📁 File Details

- File Name: `Call Center Report Dashboard (2023)`
 
- Format: Microsoft Excel (.xlsx/.xlsb)
  
- Sheets Included:
  
  - Raw Data
    
  - Pivot Tables
    
  - Dashboard

---

## 🔧 Tools Used

- **Microsoft Excel 2022+**
  
- **Pivot Tables** – For summarizing and aggregating data
  
- **Advanced Excel Formulas** – Including `VLOOKUP`, `HLOOKUP`, `INDEX-MATCH`, `IF`, `SUMIFS`, etc.
  
- **Data Validation** – To restrict inputs and improve data quality
  
- **Conditional Formatting** – For dynamic visual highlighting
  
- **Charting** – Line, Bar, Stacked Column, Histogram visuals
  
- **Slicers** – For interactive dashboard filtering
  
- **Calculated Fields** – For dynamic KPI metrics (e.g., Happy Calls, Avg Ratings)

---

## ✅ Result Summary

The dashboard analysis showed:

- **October** had the highest call volume.
  
- **Wednesday** was the busiest day of the week.
  
- **Cleveland** had the highest number of female callers.
  
- **Representative R03** ranked **1st** in revenue and **2nd** in call volume.
  
- A majority of customers gave ratings of **4 or 5**, reflecting high satisfaction.
