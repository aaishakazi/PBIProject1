# PBIProject1
Student dropout analysis report created in Power BI using raw data 

# 🎓 Student Dropout Risk Analysis Dashboard (Power BI)

## 📌 Project Overview
This project analyzes student performance and lifestyle factors and identifies **dropout risks** using data.  
The work is done **entirely in Power BI** — from **data cleaning** to **dashboard design** — using the [UCI Student Performance dataset](https://archive.ics.uci.edu/ml/datasets/student+performance).

The final dashboard enables:
- Identifying **high-risk students**
- Understanding **key drivers** of dropout percentage
- Tracking **KPIs** like dropout %, average grades, absences
- Suggestions to reduce dropouts

---

## 🛠 Tools Used
- **Power BI Desktop**
  - Power Query for data cleaning
  - DAX for calculated columns & measures
  - Custom visuals & KPI cards
- **Dataset:** UCI Machine Learning Repository – Student Performance Data

---

## 📂 Dataset Overview
- **Demographics:** Age, parental education, family support
- **Academic performance:** G1, G2, G3 grades
- **Behavioral factors:** Absences, alcohol use, free time
- **School factors:** Study time, internet access, school support

---

## 🔄 Workflow in Power BI
1. **Data Import**
   - Loaded `student-mat.csv` into Power BI.
   
2. **Data Cleaning in Power Query**
   - Removed null/duplicate values
   - Standardized categorical values

3. **Added New Columns**
   - **Dropout Risk Score** based on grades, absences, study time
   - Bins for `studytime`, `freetime`, `Dalc` (weekday alcohol), `Walc` (weekend alcohol)
   - Unique `StudentID` for tracking
   - Label columns for parental education levels

4. **DAX Measures**
   - Dropout % = (Dropout Count / Total Students)
   - KPIs: Avg G3 Grade, Absences, Risk Score

---

## 📊 Key Insights
- Higher absences + low study time strongly correlate with dropout.
- Dropout % is higher for students **with school support** — likely because support is given to struggling students.
- Alcohol consumption has a negative effect on grades and increases dropout risk.
- Internet access reduces dropout risk when paired with high study time.

---

## 📷 Dashboard Bits Preview
<img width="400" height="210" alt="image" src="https://github.com/user-attachments/assets/4cc76d3a-e065-4545-b6af-0359f73e6cca" />
<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/701e0898-2fd5-4185-8bec-73dfc50a0aef" />
<img width="400" height="800" alt="image" src="https://github.com/user-attachments/assets/3c1d0c19-96c2-4f77-972e-9be048dbc9be" />

## 🚀 View the Dashboard
1. Download the `.pbix` file from this repository and open it in Power BI Desktop.
2. OR view it online:  
   🔗 [View Interactive Dashboard](https://app.powerbi.com/reportEmbed?reportId=390cf5ca-20a1-4bde-8711-83846f8b1094&autoAuth=true&ctid=27282fdd-4c0b-4dfb-ba91-228cd83fdf71)

---

## 📎 Dataset Source
UCI Machine Learning Repository – [Student Performance Data Set](https://archive.ics.uci.edu/ml/datasets/student+performance)

---

## 📌 Author
**Aaisha Kazi**  

- GitHub: [Aaisha Kazi](https://github.com/aaishakazi)  
