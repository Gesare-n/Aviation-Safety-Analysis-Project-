
**Aviation Safety Analysis**  

---

##  Project Overview

A company is interested in purchasing aircraft for commercial and private use but lacks insight into the potential risks associated with different airplane models. This analysis was conducted to determine low-risk aircraft and recommend actionable strategies for risk mitigation.

 **Dashboard:**  
[Tableau Dashboard – Aviation Safety Analysis]()

 **Data Source:** `cleaned_AviationData.csv`  
 **Tools Used:** Tableau, Visual Studio Code  
 **Skills Applied:** Data Cleaning, Exploratory Data Analysis, Data Visualization

---

##  Business Objective

To identify the **lowest risk aircraft**, we focused on:

- Planes with the **lowest fatalities**
- Common causes of accidents
- Levels of aircraft damage during incidents

---

##  Data Mining Goal

- Ensure the dataset was clean (no null values)
- Prepare for effective visualization and exploration

---

##  Data Description

- Original dataset: **88,889 rows**, **31 columns**
- Cleaned dataset: **88,889 rows**, **28 columns**
- Dropped columns with over 60% missing values
- Filled missing values appropriately
- Created a new `State.Codes` column from the `Location` field

---

##  Approach

**Descriptive & Exploratory Analysis**:
- Analyzed injury levels among passengers
- Examined extent of aircraft damage
- Explored when accidents most frequently occur (e.g., landing, takeoff)

---

##  Key Findings

- **Timing:** Most accidents occur during **landing** and **takeoff**
- **Aircraft Safety:**  
  - *Cessna* has the highest number of **uninjured passengers**  
  - Safer compared to other popular makes like *Boeing*
- **Trends:** Overall number of accidents has **decreased over the years**
- **Airport Influence:** Higher accident rates observed at **specific airports**, likely due to infrastructure or environmental factors

---

##  Business Recommendations

1. ###  Targeted Pilot Training
   - **Insight:** Takeoff and landing are the riskiest phases.
   - **Action:** Provide advanced simulator training and pilot monitoring focused on these phases.

2. ###  Engine Maintenance Strategies
   - **Insight:** Certain engine types are linked to more severe accidents.
   - **Action:** Increase inspection frequency and replace high-risk engines proactively.

3. ###  Operational Adjustments
   - **Insight:** Some airports show higher accident rates.
   - **Action:** Review airport safety procedures and consider rerouting flights when necessary.

---

##  Next Steps & Considerations

- **Data Enrichment:** Bring in additional variables to improve insights.
- **Predictive Modeling:** Build models to forecast accident risk by aircraft type or other features.

---

##  Limitations

- Focused on aircraft model risks; didn’t account for:
  - Pilot experience
  - Maintenance protocols
  - Weather conditions
- Assumes each `Event.Id` represents a unique flight
- Lacks flight count data, so some rates are based on assumptions

---

