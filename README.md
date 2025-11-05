# 🌍 Global Earthquake & Tsunami Analysis (Power BI)

---

## 📘 1. Project Overview

This project explores **global earthquake and tsunami data** using **Microsoft Power BI**, uncovering key patterns and correlations between earthquake magnitude, depth, intensity (CDI/MMI), and significance (`sig`).

🔹 **Goal:** To visualize seismic activity worldwide, highlight tsunami-triggering earthquakes, and provide actionable insights through interactive dashboards.

**🎯 Objectives:**

* 🌎 Visualize earthquake locations and identify hotspots.
* 📊 Study correlations between magnitude, depth, and intensity.
* 🌊 Analyze events that triggered tsunamis.
* 🧭 Build a dynamic, interactive Power BI dashboard.

---

## 📁 2. Project Files

| File                                 | Description                                |
| ------------------------------------ | ------------------------------------------ |
| `GLOBAL EARTHQUAKE.pbix`             | Power BI report containing all dashboards. |
| `earthquake_data_tsunami.xlsx`       | Source dataset (Excel format).             |

---

## 🧾 3. Dataset Description

The dataset includes global earthquake records with the following key fields:

| Column                  | Description                            |
| ----------------------- | -------------------------------------- |
| `Year`, `Month`         | Time-based filters for analysis.       |
| `latitude`, `longitude` | Event location.                        |
| `depth`                 | Earthquake focal depth (in km).        |
| `magnitude`             | Earthquake magnitude (e.g., Mw scale). |
| `cdi`, `mmi`            | Intensity measures.                    |
| `sig`                   | Significance score (impact factor).    |
| `tsunami`               | 0 = No tsunami, 1 = Tsunami triggered. |

> ⚙️ **Tip:** Ensure all numeric columns are properly formatted and clean before refreshing Power BI data.

---

## 📊 4. Power BI Dashboard Pages

### 🧩 Overview

<img width="659" height="370" alt="OVERVIEW" src="https://github.com/user-attachments/assets/dad1defb-0163-4fbb-8efa-a41b04c343cb" />

* Displays total events, average magnitude, and yearly/monthly breakdowns.

### 🌐 Geographic Distribution

<img width="661" height="370" alt="GEOGRAPHIC DISTRIBUTION" src="https://github.com/user-attachments/assets/444d3860-252b-40e6-9850-d3e8ca08a4c3" />


* Interactive world map showing earthquake locations by magnitude.
* Latitude-based average magnitude & depth table.
* Scatter plot: *Depth vs Magnitude*, split by tsunami occurrence.

### 🌊 Tsunami Impact

<img width="659" height="370" alt="TSUNAMI IMPACT" src="https://github.com/user-attachments/assets/4970b079-15d1-4918-a981-d48dc0317e5b" />

* Focused visuals for tsunami-triggered earthquakes.
* Analysis of depth and magnitude in tsunami-prone areas.

### 🔬 Correlation & Pattern Insights

<img width="659" height="370" alt="CORELATION   RELATION INSIGHTS" src="https://github.com/user-attachments/assets/0ed933de-bbfa-4bbc-ac47-619812e78d48" />

* Scatter plots: `mmi by sig`, `cdi by sig`, and `depth per magnitude`.
* Insights table with Avg Magnitude, Avg CDI, Avg SIG, and Avg MMI.
* Helps visualize intensity and significance patterns.

---

## 💡 5. Key Insights

✨ **Observations from the dashboard:**

* 🌋 **Clusters:** Most earthquakes occur along tectonic boundaries, especially the Pacific “Ring of Fire.”
* ⛏️ **Depth vs Magnitude:** Larger magnitudes occur across a range of depths, but **shallow events** are more likely to trigger tsunamis.
* 📈 **Intensity correlation:** Higher magnitudes correspond with stronger CDI/MMI and significance values.
* 🌊 **Tsunami link:** Tsunami events show **lower depth** and **higher significance**.

This project combines data analytics and geoscience visualization to understand earthquake behavior and tsunami risks across the globe.*
