---
layout: default
title:  "San Francisco Crime Trends: Two Decades of Data (2003-2024)"
date:   2025-03-25 09:48:32 +0100
categories: sf crime data
---

# **San Francisco Crime Trends: A Decade of Data (2003-2024)**

### **Group 27 Members :**

Clara Mejlhede Lorenzen, s180350

Pol Triquell Lombardo, s243271

Marie Sophie Mudge Woods, s194384

---

## **Introduction**

San Francisco is a vibrant city known for its tech industry, cultural landmarks, and scenic beauty. However, like any major urban area, it also faces challenges with crime. Using the [SFPD Crime Incident Reporting dataset](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783), we can analyze crime trends over a 21-year period (2003-2024) to uncover patterns, hotspots, and shifts in criminal activity.

This data story explores:
- **How crime rates have changed over time**
- **Where crimes are most concentrated**
- **Which types of crimes are most frequent**

Let’s dive in.

---

## **1. Crime Trends Over Time**

Our first visualization shows the total number of reported crimes per year from 2003 to 2024.

*(Insert time-series line chart or bar chart here)*

```python 
your_code = do_some_stuff
```

**Key Observations:**
- Crime peaked around **2006-2008**, coinciding with economic instability before the Great Recession.
- A sharp **decline occurs post-2014**, possibly due to increased policing strategies or changes in reporting.
- Certain crimes (like larceny theft) dominate, while violent crimes (like assault) remain relatively stable.

---

## **2. Mapping Crime Hotspots**  

Next, we map the density of crimes across San Francisco.  

*(Insert a heatmap or point-based map of crime locations)*  

**Key Findings:**  
- **Downtown (Tenderloin, Union Square, Market St.)** has the highest concentration of incidents.  
- **Residential neighborhoods (Sunset, Richmond)** see fewer reports.  
- Some clusters align with nightlife areas (Mission District) and transit hubs (Civic Center BART).  

---

## **3. Interactive Exploration: Crime by Category**  

Finally, let’s explore the distribution of different crime types interactively.  

*(Embed a Bokeh interactive plot—e.g., a bar chart or scatter plot where users can filter by crime category, year, or district)*  

**Try it yourself:**
- Filter by **"Larceny Theft"** to see its dominance.
- Compare **"Assault"** vs. **"Burglary"** trends over time.

---

## **Conclusion**

Crime in San Francisco has evolved over the years, with notable declines in certain categories post-2014. However, hotspots remain in high-traffic urban centers. Understanding these patterns helps policymakers and residents address safety concerns more effectively.

**Further Reading:**
- [SFPD Crime Data Dashboard](https://data.sfgov.org/Public-Safety)
- [San Francisco Chronicle: Crime Trends Analysis](https://www.sfchronicle.com)

*(Code and data available on [GitHub](your-repo-link))*

---

### **Technical Notes**
- Built with Python (Pandas, Matplotlib, Folium, Bokeh).
- Data cleaned to remove incomplete entries.
- All visualizations use consistent color schemes (e.g., `#1f77b4` for primary data).