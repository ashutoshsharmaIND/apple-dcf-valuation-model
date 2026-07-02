# 📊 Advanced Corporate Valuation: Apple Inc. (NASDAQ: AAPL) 5-Year Unlevered DCF Model

An institutional-grade **5-Year Unlevered Discounted Cash Flow (DCF) Model** and **Two-Dimensional Sensitivity Analysis** built to evaluate the intrinsic value of Apple Inc. utilizing fiscal performance drivers.

## 📌 Project Overview & Core Thesis
This financial engineering case study bridges raw accounting disclosures with forward-looking equity valuation. Operating under a conservative steady-state organic revenue CAGR of **6.0%** and a stable **32.28% EBIT margin**, the baseline operations anchor an intrinsic share value of **$144.35**. 

The variance between the model's baseline valuation floor and the active public trading premium indicates that the market heavily values non-linear upside driven by **Apple Intelligence ecosystem monetization**, **Services margin expansion**, and strategic share retirement via Apple's newly authorized **$100 Billion stock buyback program**.

## 🛠️ Model Architecture & Technical Specifications

### 1. Cost of Capital (WACC) Configuration
The discount rate was generated via the **Capital Asset Pricing Model (CAPM)**:
* **Risk-Free Rate ($R_f$):** 4.20% (Anchored by the US 10-Year Treasury Yield)
* **Asset Beta ($\beta$):** 1.10 (Systematic equity risk covariance multiplier)
* **Equity Risk Premium (ERP):** 5.00%
* **Cost of Equity ($K_e$):** 9.70%
* **Capital Weights:** 85% Equity / 15% Debt
* **Blended Corporate WACC:** **8.78%**
* **Perpetual Growth Rate ($g$):** 2.50% (Disciplined macroeconomic ceiling)

### 2. Enterprise-to-Equity Valuation Bridge
* **Cumulative PV of 5-Year Explicit Cash Flows:** $525,971M
* **Present Value of Terminal Value:** $1,629,134M
* **Implied Enterprise Value:** $2,155,105M
* **Balance Sheet Adjustments:** +$45,570M Cash / -$74,400M Total Debt
* **Implied Equity Value:** $2,126,275M
* **Diluted Shares Outstanding:** 14,730M
* **Intrinsic Value Per Share:** **$144.35**

---

## 📂 Repository Contents
* `Apple_Stock_Valuation_Model_Report.pdf`: Full, presentation-ready publication report complete with analytical breakdown text.
* `Apple_Valuation_Model_Template.xlsx`: Dynamic, formula-linked Excel spreadsheet template with working cell links.

## 📈 Sensitivity Analysis Preview
The model includes a fully automated 2D Excel Data Table stress-testing the stock price across varied WACC parameters (7.2% to 11.2%) and Revenue growth rates (4.0% to 8.0%), allowing instant scenario testing for market shifts.
