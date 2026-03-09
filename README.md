# 📊 Financial Planning & Analysis (FP&A) Dashboard - Condominium Management

**Read the full Business Case on Medium:** [Read the Article](https://medium.com/@guilhermeoyakawalmeida/elevating-financial-visibility-building-an-fp-a-dashboard-for-condominium-management-5736d0c14df3)

**Interact with the Live Dashboard:** [Open Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTYwZDc4NzYtMGFjMy00MDhlLWEwY2ItNGNkZDJlNzMwMDM3IiwidCI6ImRlNTM3NmEzLTdhOTEtNGM1NS1hOGQ5LTI0YjhkMTVlNWViMSJ9)

## 🏢 Business Problem
Managing a condominium's finances involves balancing predictable revenues with volatile operational expenses (maintenance, payroll, utilities). 

This consultancy project was developed for a real B2B client whose operation relied on fragmented, traditional spreadsheets (Daily Ledgers, static Chart of Accounts, and disconnected annual budgets). The lack of an integrated system prevented the leadership from tracking real-time cash flow and effectively comparing 2024 actuals against the 2025 budget. 

**The goal:** Transition from retroactive accounting to proactive financial forecasting using Business Intelligence.

## 🛠️ The Solution: Power BI Command Center
I designed an end-to-end automated FP&A ecosystem in Power BI. The solution unifies daily cash flow tracking with strategic budget variance analysis.

### 1. Data Architecture (Star Schema)
To ensure performance and scalability, the data was modeled using a classic Star Schema:
* **Fact Tables:** Daily Ledger transactions (`Livro Diário`) and Strategic Budgets (`Previsão 2024 x 2025`).
* **Dimension Tables:** A centralized Chart of Accounts (`Plano de Contas`) to categorize all inflows and outflows.
* **Date Dimension:** A dynamic `dCalendario` table to act as the central bridge, allowing seamless time-intelligence calculations and comparative analysis between 2024 operational data and 2025 forecasts.

### 2. Business Logic & DAX
All calculations were centralized in a dedicated Measures Table, logically grouped into:
* **Actuals:** Real-time cash flow, operational expenses, and revenues.
* **Budgets:** Extraction of targeted financial goals for 2024 and 2025.
* **Variances:** Dynamic calculations mapping **Actual vs. Budget** to instantly highlight areas of overspending.

## 📈 Visual Diagnosis & Dashboards

### A. Operational View (Real-Time Cash Flow)
Provides day-to-day visibility. Leadership can filter expenses by category and pinpoint cost drivers without opening a single spreadsheet.

![overview](https://github.com/user-attachments/assets/1c293c32-878a-4f07-a442-a6f2a56a76c1)


### B. Strategic View (Actual vs. Budget Variance)
Focuses on capital allocation. Plots the 2024 actual expenditures against the forecasted 2025 budget, highlighting financial gaps and enabling data-driven budget meetings.

![Forecasting](https://github.com/user-attachments/assets/ccaae49f-4787-4490-b207-71f7bd706cd0)


## 💡 Executive ROI
* **Eliminated Manual Reporting:** Automated the consolidation of daily ledgers and annual budgets.
* **Increased Visibility:** Provided leadership with real-time tracking of every euro spent.
* **Strategic Allocation:** Enabled proactive financial decisions for the 2025 fiscal year based on historical variances.

---
**Author:** Guilherme Oyakawa de Almeida  
**Connect with me on LinkedIn:** [Guilherme Oyakawa de Almeida](https://www.linkedin.com/in/guilherme-oyakawa-almeida/)
