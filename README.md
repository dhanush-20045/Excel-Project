# 📞 Call Center Report Dashboard – 2023


## 📌 Problem Statement

The call center required a visual dashboard to analyze call volume, revenue, agent performance, customer satisfaction, and gender distribution across cities. 

The goal was to enable better decision-making, operational planning, and performance tracking.


---


## 🎯 Objectives

1. Provide a centralized **dashboard view** to analyze performance metrics  

2. Enable **interactive filtering** by representative  

3. Track **monthly and weekly trends** in calls and performance  

4. Identify **customer satisfaction levels** using rating distribution  

5. Highlight key KPIs like **total calls**, **revenue**, and **average rating**  


---


## 📊 Key Metrics Tracked


| Metric            | Description                                              |

|-------------------|----------------------------------------------------------|

| **Calls**         | Total number of calls handled (overall and by agent)     |

| **Amount**        | Revenue generated from calls                             |

| **Duration**      | Total call duration (in minutes or seconds)              |

| **Average Rating**| Average customer feedback score (scale of 1 to 5)        |

| **Happy Calls**   | Number of calls with high satisfaction rating            |

| **Gender Split**  | Customer gender distribution across cities               |


---


## 🧩 Dashboard Sections


- **Top KPIs (Left Panel):** High-level stats like total calls, revenue, average rating, duration, and happy calls  

- **Call Trend (Top Middle):** Line graph showing monthly call volume  

- **Day-wise Trend (Top Right):** Bar chart of calls by weekday  

- **Gender Distribution (Top Right):** Stacked bar chart of male/female split by city  

- **Rating Distribution (Top Right):** Histogram of customer feedback ratings (1–5)  

- **Performance by Representative (Middle):** Bar charts for calls and revenue per agent  

- **Detailed Table (Bottom Right):** Revenue breakdown by city and representative  

- **Interactive Filter (Middle Right):** Dropdown slicer to filter by representative  


---


## ⚙️ Steps Implemented


1. **Data Collection:**  

   - Gathered call records including call ID, city, agent ID, duration, amount, rating, gender, and call date  


2. **Data Cleaning & Preparation:**  

   - Removed duplicates and blank rows  

   - Converted date/time fields to proper format  

   - Created calculated fields for “Happy Calls” and “Average Rating”  


3. **Pivot Table Creation:**  

   - Summarized metrics by city, representative, and month  

   - Aggregated key values: call count, duration, revenue, and ratings  


4. **Dashboard Design:**  

   - Used Excel charts (line, bar, stacked bar, histogram)  

   - Added interactive slicers for filtering  

   - Applied conditional formatting for visual cues  


5. **Styling & Layout:**  

   - Consistent theme (orange-red) for readability  

   - KPI cards for snapshot views  

   - Human-readable formatting for currency, time, and percentages  


---


## 💡 Insights Generated


1. **October** had the highest call volume spike  

2. **Wednesday** recorded the most customer calls  

3. **Cleveland** had the highest number of female callers  

4. **Representative R03** ranked **1st in revenue** and **2nd in call volume**  

5. Majority of customers rated **4 or 5**, indicating high satisfaction  


---


## 📁 File Details


- **File Name:** `Call Center Report Dashboard (2023)`  

- **Format:** Microsoft Excel (.xlsx/.xlsb)  

- **Sheets Included:**  
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


- **October** had the highest call volume  

- **Wednesday** was the busiest day of the week  

- **Cleveland** had the highest number of female callers  

- **Representative R03** ranked **1st in revenue** and **2nd in call volume**  

- A majority of customers gave ratings of **4 or 5**, reflecting high satisfaction  
