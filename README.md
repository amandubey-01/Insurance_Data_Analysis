# 📊 Insurance Data Analysis – Power BI Project

## 📝 Project Description

This Power BI project analyzes customer feedback and operational data from an insurance company to derive sentiment insights and improve claim handling processes. It leverages text feedback, sentiment scores, and policy interactions to visualize satisfaction levels and identify areas for improvement.

---

## Objectives

- Visualize customer satisfaction using sentiment analysis.
- Understand claim processing efficiency.
- Explore service improvement opportunities based on feedback.
- Empower stakeholders with interactive drill-throughs and filters.

---

## 🚀 Features

- **Sentiment Classification**: Feedback categorized into "Excellent", "Good", and "Need Improvement".
- **Calculated Columns & DAX**:
  - `Sentiment Category = SWITCH(TRUE(), Score > 0.75, "Excellent", Score > 0.5, "Good", "Need Improvement")`
  - Measures for average sentiment and count per category.
- **Power Query Data Cleaning**:
  - Removed nulls and duplicates.
  - Parsed and transformed text feedback.
- **Data Modeling**:
  - Star schema design with normalized relationships.
- **Drill-Through Pages**:
  - Deep dive into specific customer feedback.
- **Cross-Page Filtering**:
  - Seamless navigation with consistent context.

---

## 📁 Files Included

- `Dashboard.pbix`: Power BI report file.
- `README.md`: Documentation for project setup and overview.
- Screenshots of 3 main report pages (included in PDF format).

---

## 🧠 Tools & Technologies

- Power BI (Desktop & Service)
- DAX (Measures, Calculated Columns)
- Power Query M Language
- Data Modeling (Star Schema)

---

## 📸 Dashboard Preview

- **Page 1**: Summary KPI Cards, Sentiment Distribution, and Key Filters
- **Page 2**: Drill-Down into Individual Feedback with Scoring
- **Page 3**: Word Cloud + Categorized Feedback Table

---

## 📈 Potential Improvements

- Automate data refresh with Power BI Gateway.
- Integrate live feedback via API.
- Add machine learning-based sentiment scoring pipeline.

---

## 🔗 Live Report (if available)

[View Power BI Report](https://app.powerbi.com/groups/d44ec7e4-386b-44f6-91d2-d550e5e1985c/reports/7fdd75e6-b381-424a-b3a9-dfa685f81a84/1bb5c7871be0140a096d)

---

## 🧑‍💻 Author

**Aman Dubey**  
Aspiring Data Analyst | Power BI Developer | SQL & Python Enthusiast

---

## 🏷 Tags

`Power BI` `Sentiment Analysis` `Customer Feedback` `Insurance Analytics` `Data Modeling` `DAX` `Power Query`
