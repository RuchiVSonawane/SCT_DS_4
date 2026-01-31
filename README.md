# Task 4: Road Traffic Accident Data Analysis

## 📌 Objective
The objective of this task is to perform **exploratory data analysis (EDA)** on
road traffic accident data to identify patterns related to **time, weather,
road surface conditions, lighting conditions, and accident severity**.

This task focuses on **data understanding and storytelling through
visualizations**, not machine learning.

---

## 📊 Dataset
- **Name:** RTA (Road Traffic Accidents) Dataset  
- **Source:** Kaggle  
- **Description:**  
  The dataset contains detailed records of road traffic accidents, including
  time of accident, weather conditions, road surface conditions, lighting
  conditions, and severity of accidents.

---

## 🛠 Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Seaborn  

---

## ⚙️ Methodology
The following steps were performed in this task:

1. **Data Loading**
   - Loaded the RTA dataset using Pandas.

2. **Data Understanding**
   - Examined dataset structure, column names, and data types.

3. **Feature Engineering**
   - Extracted hour of the day from the accident time to analyze time-based patterns.

4. **Exploratory Data Analysis**
   - Analyzed accident frequency by hour of day.
   - Studied the impact of weather conditions on accidents.
   - Examined road surface conditions related to accidents.
   - Analyzed accident severity distribution.
   - Explored the effect of lighting conditions (day/night).

5. **Visualization**
   - Created clear and informative visualizations using Seaborn and Matplotlib.

---

## 📈 Key Insights
- Road accidents occur most frequently during peak traffic hours.
- Adverse weather conditions contribute to a higher number of accidents.
- Poor road surface conditions are associated with increased accident risk.
- Serious and fatal accidents form a significant portion of total cases.
- Lighting conditions (day vs night) influence accident occurrence.

---

## ✅ Conclusion
This analysis demonstrates how exploratory data analysis can be used to
understand real-world accident data and identify high-risk scenarios.
Such insights can help support better road safety planning and awareness.

---

## 📁 Repository Structure
SCT_DS_4/
│── dataset/
│ └── RTA Dataset.csv
│── images/
│── task4_accident_analysis.ipynb
│── README.md

