# 📊 Tata Data Visualization Virtual Internship — Forage

## 🧠 Project Overview  
This repository documents my work during the **Tata Data Visualization Virtual Internship** hosted by **Forage**. As a **Data Consultant** for a simulated online retail store, I analyzed transactional sales data to provide actionable insights for strategic decision-making by the **CEO and CMO**.

The project involved end-to-end execution:  
- Rigorous data cleaning & transformation  
- Solving key business questions  
- Building stakeholder-driven visualizations using **Power BI**

---

## 🗂 Table of Contents  
1. [Introduction](#1-introduction)  
2. [Business Problem](#2-business-problem)  
3. [Dataset](#3-dataset)  
4. [Methodology](#4-methodology)  
5. [Tools & Technologies](#5-tools--technologies)  
6. [Key Measures](#6-key-measures)  
7. [Visualization Principles](#7-visualization-principles)  
8. [Key Questions & Insights](#8-key-questions--insights)  
9. [Additional Analytical Deep Dives](#9-additional-analytical-deep-dives)  
10. [Key Accomplishments & Impact](#10-key-accomplishments--impact)  
11. [Conclusion & Recommendations](#11-conclusion--recommendations)  
12. [Project Structure](#12-project-structure)  
13. [How to View the Report](#13-how-to-view-the-report)  
14. [Skills Gained](#14-skills-gained)  
15. [Acknowledgements](#15-acknowledgements)  
16. [Contact](#16-contact)  
17. [License](#17-license)

---

## 1. Introduction  
This project simulates a consulting engagement for an online retail store. The goal was to convert raw sales data into strategic business intelligence through powerful visualizations and stakeholder-specific insights.

---

## 2. Business Problem  
The leadership team at a growing online retail company needed support in understanding:
- What’s driving revenue performance?
- Who are the most valuable customers?
- Which regions and products should we focus on for expansion?

The task: Use data to answer these and guide future business strategies.

---

## 3. Dataset  
The dataset included **541,910 rows** and **8 columns**:
- `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, `Country`

---

## 4. Methodology  
A structured process was followed:
- Data Cleaning & Preparation (Power Query)
- Business Question Alignment
- Visual Creation in Power BI
- Insight Communication for Stakeholders

### 🔧 Data Cleaning Steps:
- Handled missing values in `Description` and `CustomerID`
- Removed entries with `Quantity <= 0` or `UnitPrice <= 0`
- Extracted `InvoiceDate` and `InvoiceTime`
- Standardized and trimmed text fields
- Converted ID fields to TEXT

---

## 5. Tools & Technologies  
- **Power BI** (Power Query, DAX, Dashboard Design)  
- **Excel** (initial data checks)  
- Concepts: RFM Analysis, Visualization Pyramid Architecture

---

## 6. Key Measures  
Sample DAX:
Total Revenue = SUMX('online_retail', 'online_retail'[UnitPrice] * 'online_retail'[Quantity])
Total Quantity Sold = SUM('online_retail'[Quantity])

## 7. Visualization Principles
- One Question = One Tab: Simplified user navigation
- Explicit Naming: Clear tab labels like "Top 10 Countries"
- Stakeholder Focus: CEO vs. CMO needs were treated separately
- Clarity over Complexity: Simple, direct charts with actionable takeaways

## 8. Key Questions & Insights
🔹 Insights for the CEO
- Monthly Revenue Trend: Clear seasonal peaks identified (e.g., Nov 2011)
- Regional Performance: Top regions like Netherlands & Germany stood out
- Top Customers: Key revenue contributors identified for strategic retention

🔸 Insights for the CMO
- Top 10 Non-UK Countries: Assessed for international expansion
- Top 10 Customers: Used to guide loyalty and satisfaction strategies
- Repeat Behavior: Uncovered gaps and potential in customer re-purchases

## 9. Additional Analytical Deep Dives
📌 Customer Segmentation (RFM)
- Segments like:
- Best Customers
- Big Spenders
- Potential to become Best Customers
- Look Out Buyers

Helped identify growth and re-engagement opportunities.

🔁 Purchase Frequency
Found major drop-offs after 1–5 purchases → Retention Opportunity

🛒 Product Performance
Identified best/worst performers → Inventory Optimization Strategy

## 10. Key Accomplishments & Impact
✅ Built stakeholder-focused Power BI dashboard
✅ Cleaned and transformed 500K+ records
✅ Created strategic customer segments
✅ Delivered real business insights for decision-making

## 11. Conclusion & Recommendations
The project reinforced how data, when cleaned and visualized properly, can uncover growth opportunities.

Recommendations:
- Target promising customer segments for re-engagement
- Implement loyalty incentives for repeat purchases
- Focus on top-performing products & regions
- Reevaluate underperforming areas

## 12. Project Structure:
.
├── My Diary of Findings and Approaches.txt  
├── README.md  
└── [Visuals Folder - if applicable]  
    └── Visual screenshots / Power BI .pbix file (Not included here)

## 13. How to View the Report
The full report and dashboard were created in Power BI. Screenshots or .pbix file can be shared upon request.

## 14. Skills Gained
- Data Cleaning (Power Query)
- Data Modeling & DAX
- Data Visualization (Power BI)
- Customer Segmentation (RFM)
- Problem Solving & Critical Thinking
- Business Communication & Strategic Framing

## 15. Acknowledgements:
🙏 Thanks to
- Tata Consultancy Services (TCS) for the virtual internship
- Forage for the platform and guidance

## 16. Contact
Himanshu Kumar
📧 [Gmail](ds.himanshu.kumar@gmail.com)
🔗 [Linkedin](www.linkedin.com/in/himanshukumar3231)
💻 [GitHub](https://github.com/himanshu3231)

## 17. License
This repository is for educational and portfolio purposes only.
