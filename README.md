# NCBA: Comprehensive Financial Model- FY2025. 
- This repository contains a fully integrated financial model for NCBA Group PLC built from FY2025 audited financial statements, covering forecasting, valuation, investment return analysis and scenario based sensitivity testing.

Item Detail Company: NSE Ticket NCBA 
- CurrencyKenya Shilling KES '000'.
-  Model Base YearFY2025 (Year ended 31 December 2025)
-  Projection Horizon FY2026E – FY2030E (5 years)
-  Valuation Methods: DCF (FCFE), P/E, P/B, EV/EBITDA, Dividend Yield.
-  Data Source: NCBA Group Annual Report & Financial Statements. 

# Model Architecture
The model is built across 10 integrated worksheets, where each section flows logically into the next. Core assumptions are centralized in a dedicated Assumptions tab, allowing the entire model to update dynamically through scenario changes.

Assumptions──►Income Statement──►Balance Sheet──►Cash Flow Statement──►DCF Valuation|Multiples Valuation──►Returns & MOIC──►Sensitivity Analysis──►Summary & Recommendation. 
                      
                      Tab 1:Instructions
The Instructions tab acts as the starting point of the model, that provides an overview of the workbook structure, navigation guidance and the color coding system applied throughout the model. It is designed to help quick understand how the workbook is organized and how the different sections interact with one another.

                       Tab 2: Assumptions
The Assumptions tab serves as the central input hub for the entire model. Key forecasting and valuation drivers including growth rates, operating margins, discount rates, valuation multiples and pricing assumptions are consolidated in one location to maintain consistency across the workbook. All major outputs are dynamically linked to this sheet, allowing the model to update automatically whenever assumptions are adjusted. This structure supports efficient scenario analysis, improves flexibility, and minimizes hardcoded inputs throughout the model.

 A. Company Information: 
Input Value Note Current Stock Price (KES)39.50 NSE 
indicative priceShares Outstanding (mn)1,647.52 (NCBA AR FY2025, Note 20)
Market Capitalisation:  KES 65.1 bn Calculated (Current Stock X 1,647 = 65.1bn). 

B. Revenue & Growth Assumptions:
5 year net interest income (NII) growth progressively steps up from 8% in FY2026E to 10% in FY2030E, reflecting normalization of the interest rate environment following CBK monetary easing. Non-interest income growth remains more moderate at 5–7%, as digital fee income streams mature and growth stabilizes. Operating expenses grow at 10% in FY2026E, driven by continued investment in headcount and technology, before tapering to 7% as efficiency gains and cost discipline take effect. Credit impairment ratios remain stable at 9.6% of net operating income across the projection period.

C. WACC Calculation
The discount rate is derived using the Capital Asset Pricing Model (CAPM):
- Cost of Equity = Rf + β × ERP
               = 12.5% + 0.95 × 5.5%
               = 17.7%
- WACC = Ke × (1 - d) + Kd × (1 - t) × d
     = 17.7% × 94.4% + 11.0% × 83.9% × 5.6%
     ≈ 14.0%
- Risk-Free Rate (10-yr KE T-bill)12.5%  Kenya sovereign yield.
- Equity Risk Premium 5.5% Emerging market premium.
- Beta 0.95 Banking sector estimate.
- Cost of Debt (pre-tax) 11.0% Senior unsecured approximation.
- Debt/Capital Ratio5.6% FY2025 (borrowings/total capital).
- WACC 14.0% Key sensitivity driver.
The terminal growth rate is set at 4.5%, anchored to Kenya's long-run nominal GDP growth trajectory as referenced in the NCBA Directors' Report.


