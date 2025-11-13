# 🚗 Car Accidents Analysis Dashboard

## 📖 Overview
This project analyzes **car accident data** from the **United States (2016–2023)** to identify the **main causes, patterns, and contributing factors** behind road accidents.  
The analysis aims to provide **data-driven insights** that can later be applied to **Egyptian traffic data** to help reduce accident rates and improve road safety.

---

## 👥 Team Members
- Arwa Nabil  
- Mohamed Ibrahim  
- Kareem Farahat  
- Mahmoud Ahmed  
- Omar Mohammed  
- Muhammed Megahed  

---

## 🎯 Problem Statement
According to the **Central Agency for Public Mobilization and Statistics (CAPMAS)** in Egypt, road accident fatalities reached **5,260**, while traffic injuries increased from **71,016 in 2023** to **76,362 in 2024** — an increase of **7.5%**.  
To better understand and prevent such incidents, we analyzed U.S. accident data to uncover the **primary factors contributing to accidents**, such as **weather, lighting, road conditions, and timing**.

---

## 🧠 Objectives
- Identify **main causes** and **patterns** of car accidents.  
- Analyze **when**, **where**, and **under what conditions** accidents occur most frequently.  
- Develop **interactive dashboards** to visualize findings.  
- Propose **data-driven recommendations** for safety improvements.  
- Explore how these insights can be **applied to Egyptian roads**.

---

## 📊 Dataset Overview
- **Source:** [Kaggle – U.S. Car Accidents Dataset](https://www.kaggle.com/sobhanmoosavi/us-accidents)  
- **Time Range:** February 2016 → March 2023  
- **Coverage:** 49 U.S. states  
- **Records:** ~7.7 million accident entries  

---

## 🧹 Data Cleaning
Data cleaning and preparation were done using:
- **SQL** – to remove duplicates and handle missing values  
- **Python** – for feature engineering and validation  
- **Power Query** – to build dimensional tables and transformations  

**Main steps:**
1. Removed irrelevant or duplicate records  
2. Handled missing values  
3. Created new calculated columns  
4. Built dimensional tables  

---

## 🧩 Data Modeling
The data was modeled using a **star schema** for efficient querying and reporting in **Power BI**.  
Dimensions include:
- Time  
- Location  
- Weather  
- Road Conditions  
- Severity  

---

## 🧮 DAX Measures
Key DAX calculations were used for:
- Accident Severity Index (ASI)  
- Year-over-Year (YoY) comparisons  
- Conditional calculations (e.g., severity by weather type)  
- Averages and ratios for trend analysis  

---

## 📈 Sample Visuals
- 🗺️ **Map:** Geographic distribution of accidents  
- 📊 **Bar Chart:** Accidents by weather condition  
- 🔵 **Bubble Chart:** Road features vs. severity index  
- 📋 **Tables & KPIs:** State-level performance and accident trends  

---

## 📊 Key Findings
- **California** has the highest number of accidents, followed by **Florida** and **Georgia**  
- Accidents peak in **December, January, and November**  
- **Tuesdays** record the highest number of accidents  
- Most accidents occur under **fair weather conditions** — indicating strong human/behavioral influence  
- **Junctions** and **no-crossing areas** have higher severity  

---

## 💡 Recommendations
1. **Focus on high-risk states and seasons** – e.g., California and winter months  
2. **Raise awareness** through campaigns in December–January and on Tuesdays  
3. **Improve infrastructure** in junctions and high-risk areas  
4. **Enhance real-time alerts** during high-risk periods  

---

## 🛠️ Tools & Technologies
- SQL Server  
- Python (Pandas, NumPy)  
- Power BI  
- Power Query  
- Excel  

---

## 🧾 Dashboard Preview
*(Add Power BI screenshots or report link here if available)*

---

## 📢 Conclusion
This project demonstrates how data analytics can uncover actionable insights to **reduce traffic accidents**, **enhance road safety**, and **support data-informed decision making**.  
Future work includes integrating **Egyptian accident data** for localized analysis and recommendations.

---
