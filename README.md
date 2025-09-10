# 📊 Loan Default Overview – Power BI Project
I analyzed a Loan Default Dataset using Power BI to identify factors influencing repayment. The project visualized borrower details like income, credit score, DTI, and loan purpose. Insights showed patterns in defaults, helping banks refine lending policies and make data-driven loan approval decisions.

## Introduction
The **Loan Default Overview** project analyzes borrower data to uncover patterns in loan approvals, repayments, and defaults.  
Built in **Power BI** with **15 KPIs across 3 pages**, the report helps **bank officials identify risks and make informed lending decisions**.  

---

## Work Done
- **Data Cleaning & Transformation** using Power Query  
- Built **calculated columns & measures** with **DAX** (e.g., `SUMX`, `MEDIANX`, `CALCULATE`, `FILTER`)  
- Integrated multiple **data sources** (borrower demographics, financials, loan details)  
- Designed **interactive dashboards** with slicers & drill-through for deep insights  

---

## Dataset
Key attributes used:  
- **Loan Amount, Credit Score, Income, Age, Employment Type, Loan Purpose, Mortgage, Dependents, Default Status, Loan Date**, etc.  

---

## Report Pages & Highlights
### Page 1 – Loan Purpose & Amounts  
- Loan Amount by Purpose (`SUMX + FILTER`)  
- Line chart with data validation  
📸 *[Screenshot](https://github.com/SudattaRoy13/Loan-Default-Overview/blob/main/Loan%20Overview.png)*  

### Page 2 – Applicant Demographics  
- Median Loan Amount by Credit Score (`MEDIANX`)  
- Segmentation by Age Group, Mortgage & Dependents  
📸 *[Screenshot](https://github.com/SudattaRoy13/Loan-Default-Overview/blob/main/Applicant%20Demographics.png)*  

### Page 3 – Financial Risk Metrics  
- YOY Loan Amount Change (`DIVIDE + CALCULATE`)  
- YOY Default Loans Change (`COUNTROWS + FILTER`)  
📸 *[[Screenshot](https://github.com/SudattaRoy13/Loan-Default-Overview/blob/main/Financial%20Risk%20Metrix.png)]()*  

---

## ✅ Key Insights
- Borrowing patterns vary strongly by **purpose & demographics**.  
- **YOY analysis** highlights loan growth vs defaults.  
- Supports **risk assessment & strategic loan approvals**.  

---

## How to Use
1. [Download the `.pbix` file.](https://github.com/SudattaRoy13/Loan-Default-Overview/blob/main/Loan%20Default%20%26%20Credit%20Score.pbix)
2. Open in **Power BI Desktop**.  
3. Explore **3 interactive pages of KPIs & visuals**.  

---

## Author
**Sudatta Roy**  
*Data Analyst | Power BI Enthusiast*  
🔗 [LinkedIn](www.linkedin.com/in/sudatta-roy-261540262) | [GitHub](https://github.com/SudattaRoy13)
