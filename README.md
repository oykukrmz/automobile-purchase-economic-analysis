# automobile-purchase-economic-analysis
Comparative economic analysis of 4 vehicle alternatives using PW and AW methods in Excel.
# Engineering Economy: Automobile Purchasing Decision Analysis 🚗💰

## Project Overview
This project applies Engineering Economy principles to evaluate the most economically feasible personal automobile option among four different alternatives. [cite_start]The study utilizes **Present Worth (PW)** and **Annual Worth (AW)** analysis techniques to determine the "total cost of ownership" over a 10-year planning horizon[cite: 23, 33].

## 🎯 Objective
[cite_start]To identify the most cost-effective vehicle by analyzing initial investment, fuel consumption, maintenance, insurance costs, and salvage values, using a Minimum Attractive Rate of Return (MARR) of **9%**[cite: 20, 30].

## 🔍 Methodology
[cite_start]The analysis compares the following vehicle alternatives[cite: 25]:
1. **Renault Megane 1.3 TCe** (Gasoline)
2. **Toyota Corolla 1.8 Hybrid** (Hybrid)
3. **Citroen C4 1.2 PureTech** (Gasoline)
4. **Skoda Fabia Monte Carlo 1.5 TSI** (Gasoline)

### Technical Approach
* [cite_start]**Data Collection:** Official WLTP fuel consumption data and market prices (Dec 2025) were used[cite: 61, 65].
* [cite_start]**Financial Modeling:** Performed in **MS Excel** using built-in financial functions to ensure precision[cite: 101].
    * [cite_start]`PV` (Present Value / BD): Used to discount future costs[cite: 99].
    * [cite_start]`PMT` (Payment / DEVRESEL_ÖDEME): Used to calculate Annual Worth[cite: 100].
* **Analysis Types:**
    * **Present Worth (PW):** All costs discounted to $t=0$.
    * **Annual Worth (AW):** All costs converted to an equivalent uniform annual series.

## 📊 Results & Conclusion
[cite_start]Based on the analysis, the **Citroen C4 1.2 PureTech** was identified as the most economically suitable option[cite: 358].

| Vehicle Model | Present Worth (PW) | Annual Worth (AW) |
| :--- | :--- | :--- |
| **Citroen C4 1.2 PureTech** | **-1,693,860 TL** | **-263,937 TL** |
| Renault Megane 1.3 TCe | -1,888,393 TL | -298,863 TL |
| Toyota Corolla 1.8 Hybrid | -1,920,750 TL | -299,291 TL |
| Skoda Fabia 1.5 TSI | -2,645,413 TL | -412,112 TL |

[cite_start]*(Values sourced from project analysis )*

## 🛠 Tools Used
* **Microsoft Excel:** For financial functions and simulation.
* **Engineering Economy Principles:** Time value of money, Depreciation, Cash Flow Analysis.

## 📄 Files in this Repo
* `Analysis_Calculations.xlsx`: The Excel file containing the PW/AW models and cash flow diagrams.
* `Project_Report.pdf`: Detailed academic report including academic rationale and sensitivity analysis.

---
**Authors:** [Öykü Kırmızı] & Project Team
