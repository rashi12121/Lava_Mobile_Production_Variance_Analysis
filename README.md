# 📱 Lava Mobile Production Variance Analysis

## 🧩 Project Overview
**Lava** is a mobile manufacturing company. In 2019, the company set production targets for their new models: **Z60**, **X41**, and **A44**. To meet these targets, the management allocated production budgets across different regions, factories, models, and months.

This project focuses on performing a **variance analysis** to compare **budgeted vs. actual production** and identify which regions, models, and quarters met or missed their targets. The goal is to uncover trends and insights to support better production planning.

---

## 🗃️ Database Info
Three datasets were used for this analysis:

1. **Budget Sheet** – Contains the budgeted production quantities by region, model, and month.
2. **Actual Sheet** – Includes actual units produced per batch along with batch-level details.
3. **Abbreviation Sheet** – Decodes abbreviations used for regions, models, and factory codes in the dataset.

---

## ❓ Questions to Answer

1. **Region-wise Variance Analysis**  
   Which regions met or missed their production targets for different mobile models?

2. **Model-wise Variance Analysis**  
   How did each mobile model perform across the year in terms of production vs. budget?

3. **Quarter-wise Performance**  
   In which quarter did the company exceed or fall short of its production goals?

---

## 📈 EDA & Visualization
The entire analysis and visualizations were performed using **Google Sheets**. Key visualizations include:

- Region-wise and model-wise bar charts
- Monthly production comparison line charts
- Quarterly variance summaries
- Conditional formatting to highlight positive/negative variances

---



🖼️ **Dashboard:**  
![ Analysis Dashboard](https://github.com/rashi12121/Lava_Mobile_Production_Variance_Analysis/blob/main/Lava_Mobile_Production_Variance_Analysis.png)





---

## 🔍 Key Insights

- **Model Insight**:  
  - The best performing model is **A44**, which showed the **lowest production variance** compared to other models.

- **Region Insight**:  
  - The **South** region performed best overall, even though **all regions** had lower actual production than their respective budgets.

- **Quarter Insight**:  
  - The company had a **positive variance in Q4**, while all other quarters showed **negative variance**.

---

## 🛠️ Tools Used

- **Google Sheets**
  - Data cleaning and transformation
  - Variance calculations using formulas (`SUMIF`, `VLOOKUP`, etc.)
  - Charts and graphs for insights
  - Conditional formatting for visual cues

---

📌 *This project provides a clear overview of Lava’s production performance across different dimensions and can help the company improve planning and execution strategies going forward.*

