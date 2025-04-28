
**Aviation Safety Analysis**  

---

##  Project Overview

A company is interested in purchasing aircraft for commercial and private use but lacks insight into the potential risks associated with different airplane models. This analysis was conducted to determine low-risk aircraft and recommend actionable strategies for risk mitigation.

 **Dashboard:**  
[Tableau Dashboard – Aviation Safety Analysis](https://public.tableau.com/views/version1aviationanalysis1/AirplanesAnalysisDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

![Screenshot 2025-04-28 114102](https://github.com/user-attachments/assets/cebe1598-49d5-453c-94d9-b0d8349ae353)


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

  ##   Presentation
  
![Screenshot 2025-04-27 163843](https://github.com/user-attachments/assets/6b3700ed-d00a-4f4d-b5d2-41b1128b1ffc)
![Screenshot 2025-04-27 163911](https://github.com/user-attachments/assets/183f1f8f-acbf-4542-9484-74062ac6cadb)
![Screenshot 2025-04-27 163933](https://github.com/user-attachments/assets/b39fbfd5-083f-43d9-9a89-2cf3c6652013)
![Screenshot 2025-04-27 163951](https://github.com/user-attachments/assets/bab6456a-3f8c-4761-8bda-544693684462)
![Screenshot 2025-04-27 164014](https://github.com/user-attachments/assets/59bf6a49-7e26-4eb7-ac8d-b1848115552a)
![Screenshot 2025-04-27 164034](https://github.com/user-attachments/assets/ae53f16e-8e22-475e-a236-816e2997e592)
![Screenshot 2025-04-27 164121](https://github.com/user-attachments/assets/febd8810-82c6-4557-848d-81a00ec22a27)
![Screenshot 2025-04-27 164143](https://github.com/user-attachments/assets/81c3b791-8619-42af-9f5c-b51717707cf1)
![Screenshot 2025-04-27 164205](https://github.com/user-attachments/assets/c1768fde-c041-4552-8710-abfe43fe55d0)
![Screenshot 2025-04-27 164314](https://github.com/user-attachments/assets/be000440-7998-467a-9a9c-cad9184cbe32)
![Screenshot 2025-04-27 164337](https://github.com/user-attachments/assets/10cca1a6-34a2-4df5-baa9-71f0c67a8f89)
![Screenshot 2025-04-27 164410](https://github.com/user-attachments/assets/e8455570-403b-4659-ba45-54a0415513a5)
![Screenshot 2025-04-27 164443](https://github.com/user-attachments/assets/9d80387e-fd97-46e2-868b-d82a3343e4ca)
![Screenshot 2025-04-27 164508](https://github.com/user-attachments/assets/61cfc445-3463-4324-a49c-76e14bff2688)
![Screenshot 2025-04-27 164528](https://github.com/user-attachments/assets/ec598291-a22c-46ec-92f2-23aba8777fda)

**PDF:**  
[Presentation PDF](https://drive.google.com/file/d/1-4zmo5qZMo_fa9K661NjWhLBYGjWHNWd/view?usp=sharing)








---

