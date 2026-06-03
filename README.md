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

C. WACC Calculation:
The discount rate is derived using the Capital Asset Pricing Model (CAPM):
- Cost of Equity = Rf + β × ERP
               = 12.5% + 0.95 × 5.5%
               = 17.7%
- WACC = Ke × (1 - d) + Kd × (1 - t) × d
     = 17.7% × 94.4% + 11.0% × 83.9% × 5.6%
     ≈ 14.0%
The terminal growth rate is set at 4.5%, anchored to Kenya's long-run nominal GDP growth trajectory as referenced in the NCBA Directors' Report.

      Tab 3: Income Statement (P&L)
a. Overview:
The IS tab presents a consolidated P&L statement, comprising two years of historical financial performance (FY2024A–FY2025A) and five years of forward projections (FY2026E–FY2030E). Historical figures are sourced from NCBA Group's audited annual reports, while forecast periods are driven by assumptions contained within the Assumptions tab.
The schedule is structured to provide a transparent linkage between operating drivers and earnings outcomes. Revenue, expenses, impairments, taxation, and profitability metrics are projected using explicit growth assumptions, allowing users to trace every forecast output back to a defined modeling input.

b. FY2025 Performance Review:
NCBA delivered a strong FY2025 financial performance, reporting PBT of KES 27.9 bn, representing approximately 11% year-on-year growth. The improvement was primarily supported by expansion in net interest margins and a significant reduction in funding costs as the interest rate environment normalized.

- Key highlights included:
The NII increased to approximately KES 57.7 bn, driven by improved asset yields and lower deposit pricing pressures.
Interest Expense declined materially following the moderation of funding costs after the CBK tightening cycle.
Non-Interest Income remained resilient, supported by transaction banking, digital channels, foreign exchange income and lending related fees.
Operating Expenses increased moderately as the Group continued investing in technology infrastructure, digital transformation, risk management and human capital.
Credit Impairment Charges remained manageable, reflecting stable asset quality and prudent risk management practices.
The Group maintained healthy profitability ratios while preserving strong capital adequacy and liquidity positions.

c. Forecast Methodology
The forecast period (FY2026E–FY2030E) is built using a driver based approach:
- Revenue: Net Interest Income is projected using growth assumptions ranging from 8% to 10% annually,
Reflecting: Continued loan book expansion, gradual normalization of the interest rate environment, Stable net interest margins and Growth in customer deposits.
- Non-Interest Income is projected to grow between 5% and 7% annually, reflecting the maturation of digital banking revenues and a more normalized growth profile for fee-based income streams.
- Operating Expenses
Operating expenses are forecast using growth rates that decline from 10% to 7% over the projection horizon.
This reflects: Ongoing investments in technology and digital transformation, Inflationary pressures on staff and administrative costs, and Gradual realization of operational efficiencies and cost discipline.
- Credit Impairment
Credit impairment charges are modeled as a fixed percentage of operating income throughout the forecast period. This approach reflects management's historical provisioning discipline and assumes no significant deterioration in asset quality.
-Taxation
The effective tax rate is held broadly consistent with historical averages, unless otherwise adjusted within the assumptions schedule.

-- Key Outputs
The Income Statement serves as the primary driver for:
 Earnings Per Share (EPS)
 Return on Equity (ROE)
 Return on Assets (ROA)
 Free Cash Flow calculations
 Dividend capacity analysis
 DCF and Relative Valuation outputs
As a result, all valuation outputs within the model ultimately originate from the operating assumptions embedded within this schedule.

