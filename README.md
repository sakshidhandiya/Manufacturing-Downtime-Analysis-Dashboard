
# Manufacturing Downtime Analysis Dashboard

## 📌 Project Overview

This project provides an **interactive Excel dashboard** for analyzing downtime in a manufacturing environment. The dashboard is designed to help operations and management teams monitor machine utilization, identify downtime causes, and support data-driven decision-making to improve efficiency.

The dataset contains **~3000 rows of machine downtime records** with details such as machine IDs, dates, durations, comments (downtime reasons), shifts, and categorized time buckets.

## 🎯 Objectives

* Track and visualize **downtime across machines, shifts, and months**.
  
* Categorize downtime into **minor, medium, and major buckets** for better prioritization.
  
* Identify major contributors to downtime (e.g., tool change, coolant issue, no operator, maintenance).
  
* Provide **KPIs and trends** to support operational excellence.


## 📂 Dataset Details

The dataset includes the following columns:

* **Machine_ID** → Unique identifier for each machine.
  
* **Date** → Date of downtime occurrence.
  
* **Duration in Mins / Duration in Hrs** → Time lost due to downtime.
  
* **Comments** → Reason for downtime (e.g., break, tool change, coolant issue, planned maintenance, power supply failure, etc.).
  
* **Shift** → Shift in which downtime occurred.
  
* **Time Bucket** → Categorized downtime:

  * **Minor**: 0 – 0.5 hrs
    
  * **Medium**: 0.5 – 2 hrs
    
  * **Major**: > 2 hrs


## 📊 Dashboard Features

### 1. **Pivot Analysis**

* Downtime by **comment category (reason)** in hours.
  
* Machine-wise downtime distribution.
  
* Month-wise downtime trends.
  
* Machine-wise + shift-wise downtime view.

### 2. **Visualizations**

* **Bar Chart** → Machine-wise downtime comparison.
  
* **Column Chart** → Month-wise downtime.
  
* **Stacked Chart** → Machine + shift downtime analysis.
  
* **Category Breakdown** → Time spent in each downtime reason.

### 3. **KPIs**

* **Total number of machines** under monitoring.
  
* **Total downtime in hours** for the selected period.


## 🚀 Usage Instructions

1. Open the Excel file and navigate to the **Dashboard** sheet.
2. Use **slicers/filters** (by machine, month, shift, or time bucket) to interactively analyze downtime.
3. Explore pivot tables for detailed breakdowns of downtime by reason.
4. Use KPI tiles to monitor overall downtime performance at a glance.


## 📈 Insights & Applications

* **Identify recurring downtime causes** (e.g., “tool change” or “no operator”) for targeted improvements.
  
* **Monitor machine-level performance** and flag machines with consistently high downtime.
  
* **Plan preventive maintenance** by analyzing downtime trends across shifts/months.
  
* **Support continuous improvement initiatives** in manufacturing by reducing avoidable downtime.


## ✅ Future Enhancements

* Integration with **Power BI / Tableau** for advanced visualizations.
  
* Root cause categorization (planned vs. unplanned downtime).
  
* Automated alerts for machines with high major downtime.
  
* Predictive modeling to anticipate downtime trends.

