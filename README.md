# NCBA: Comprehensive Financial Model- FY2025. 
- This repository contains a fully integrated financial model for NCBA Group PLC built from FY2025 audited financial statements, covering forecasting, valuation, investment return analysis and scenario based sensitivity testing.

Item Detail Company: NSE Ticket NCBA 
- CurrencyKenya Shilling KES '000'.
-  Model Base YearFY2025 (Year ended 31 December 2025)
-  Projection Horizon FY2026E – FY2030E (5 years)
-  Valuation Methods: DCF (FCFE), P/E, P/B, EV/EBITDA, Dividend Yield.
-  Data Source: NCBA Group Annual Report & Financial Statements. 

-- Model Architecture
The model is built across 10 integrated worksheets, where each section flows logically into the next. Core assumptions are centralized in a dedicated Assumptions tab, allowing the entire model to update dynamically through scenario changes.

 Assumptions ──► Income Statement ──► Balance Sheet ──► Cash Flow Statement
                       │                    │                   │
                       └────────────────────┼───────────────────┘
                                            ▼
                              DCF Valuation │ Multiples Valuation
                                            ▼
                                    Returns & MOIC
                                            ▼
                               Sensitivity Analysis
                                            ▼
                             Summary & Recommendation
