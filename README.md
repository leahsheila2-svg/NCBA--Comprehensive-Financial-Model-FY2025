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
a. Overview
The IS tab presents NCBA Group's consolidated P&L statement, comprising two years of historical financial performance (FY2024A–FY2025A) and five years of forward projections (FY2026E–FY2030E). Historical figures are sourced from the Group's audited financial statements, while forecast periods are driven by assumptions contained within the Assumptions tab.
The schedule is structured to create a transparent linkage between operating drivers and earnings outcomes. Revenue, expenses, impairments, taxation and profitability metrics are forecast using explicit assumptions, allowing users to trace every projected output back to a defined model input.

b. FY2025 Performance Highlights, 

NCBA delivered a strong FY2025 performance, reporting PBT of KES 27.9 bn, representing 11% year-on-year growth and marking the fourth consecutive year of double digit earnings expansion.
Key highlights included: NII increased 22% YoY to KES 57.7 bn, Interest Expense declined 41% YoY from KES 41.5 bn to KES 24.4 bn, NOI expanded despite softer asset yields.
Credit impairment charges increased to KES 6.9 billion, reflecting continued pressure within selected corporate and SME segments, Profitability remained resilient despite elevated provisioning requirements.

c. The NII Story
The most important driver of FY2025 earnings was the significant improvement in funding economics.
While Interest Income declined by approximately 6% YoY, reflecting lower asset yields as market rates normalized, Interest Expense fell by approximately 41% YoY, creating a substantial positive spread effect.
As a result: Net Interest Income increased by KES 10.3 bn, NII Growth reached 22% YoY, Net Interest Margin (NIM) expanded materially
The Group benefited from a lower cost of deposits and improved liability management
This asymmetric repricing of liabilities vs assets demonstrates the strength of NCBA's deposit franchise. Funding costs adjusted downward more rapidly than earning asset yields, allowing margin expansion despite a moderating interest rate environment.
From a modeling perspective, this dynamic underpins the projected NII growth assumptions applied throughout FY2026E–FY2030E.

d. Credit Quality Watch
Credit quality remains the most significant earnings risk within the forecast period.
FY2025 credit impairment losses increased 37% YoY to approximately KES 6.9 billion, reflecting persistent stress within portions of the corporate and SME lending portfolio.
Key risk indicators include (Credit Metric FY2025): Credit Impairment Losses	KES 6.9 bn, Growth in Impairment Charges	37% YoY, Impairment / NOI 9.6%,Forecast Impairment Assumption	9.6%.
To maintain prudence, the model assumes Credit Impairment Expense remains at 9.6% of Net Operating Income throughout the forecast period.
This assumption reflects: Continued normalization of the macroeconomic environment, Stable but elevated Stage 3 loan balances, Conservative provisioning practices and Ongoing risks within SME and corporate lending segments.
Should asset quality deteriorate beyond current expectations, impairment costs would represent the most significant downside risk to projected earnings and valuation.
The model's Sensitivity Analysis tab quantifies the impact of varying impairment assumptions on Profit Before Tax, Profit After Tax, Earnings Per Share, and valuation outputs.
d. Key Outputs
The Income Statement serves as the primary driver for: EPS, ROE, ROA, Dividend Capacity, Free Cash Flow to Equity (FCFE),DCF, Relative Valuation (P/E, P/BV),Investor Return Metrics (IRR, MOIC, ROI)
Every valuation output within the model ultimately traces back to the operating assumptions and earnings projections generated within this schedule.

    Tab 4: Balance Sheet

The BS tab presents NCBA Group's consolidated Statement of Financial Position for FY2024A and FY2025A, together with forecast projections through FY2030E. The balance sheet serves as the structural foundation of the model, linking asset growth, funding strategy, liquidity management and capital adequacy to earnings generation and shareholder value creation.
Within the model, loan growth assumptions drive earning asset expansion and future Net Interest Income (NII), while deposit growth assumptions determine funding capacity and funding costs. Retained earnings generated through the Income Statement flow directly into Shareholders' Equity, supporting dividend capacity, capital strength and long-term growth.

- FY2025 Balance Sheet Highlights
NCBA closed FY2025 with a significantly stronger liquidity position, improved capital base and a more conservative funding structure.

a. Liquidity Strength: Balances held with the CBK increased by KES 20.1 bN, reflecting management's deliberate decision to maintain elevated liquidity buffers amid a challenging credit environment.
As a result: Liquidity Metric	FY2024 vs FY2025 Cash & CBK Balances / Total Assets	6.6%, 8.9%.
The increase in liquid assets enhanced the Group's ability to absorb market shocks, meet regulatory liquidity requirements, and maintain flexibility for future lending opportunities.
Interpretation:
The rise in liquidity suggests a cautious balance sheet posture. While excess liquidity can temporarily suppress returns on assets, it strengthens resilience and positions the Group to capitalize on future credit demand as economic conditions improve.

b.Loan Growth Deceleration
Net loans and advances grew by approximately 4.4% YoY, materially below both historical growth rates and nominal GDP growth expectations.
Loan Growth Metric	FY2025: Net Loan Growth	4.4%
Management maintained a disciplined underwriting approach amid elevated non-performing loan (NPL) risks and persistent pressure within segments of the corporate and SME lending portfolios.
The model assumes loan growth gradually recovers to approximately 6% annually from FY2026E onward, reflecting improving macroeconomic conditions and a normalization of the credit cycle.
Interpretation:
Lower loan growth indicates management's prioritization of asset quality over volume expansion. Although this moderates short-term revenue growth, it supports long-term profitability by reducing future credit losses.

c. Funding Structure and Deleveraging
Borrowings declined by KES 2.6 bn, representing approximately 26% year-on-year contraction.
Funding Metric	FY2025, Borrowings Growth	-26%
This reduction reflects lower dependence on wholesale funding and a greater reliance on customer deposits as the primary funding source.
Interpretation:
A deposit funded balance sheet generally provides lower and more stable funding costs than wholesale borrowings. This funding mix improvement contributed significantly to the expansion in Net Interest Margin observed during FY2025.

d. Capital Accumulation
Shareholders' Equity increased by KES 17.7 bn, representing approximately 16.1% YoY growth despite dividend distributions of KES 9.5 billion.
Capital Metric	FY2024	FY2025, Shareholders' Equity Growth	—	16.1%,Dividend Paid	—	KES 9.5 bn. 
The increase was primarily driven by retained earnings generated from the Group's strong profitability performance.
Interpretation:
Growing equity enhances loss absorption capacity, supports regulatory capital requirements and provides additional capacity for future asset growth without requiring external capital raising.

- Key Balance Sheet Ratios
a. Equity to Assets Ratio: Ratio	FY2024 vs FY2025, Equity / Total Assets	8.7%, 9.6%. 
Interpretation:
The increase indicates strengthening capitalization and a larger buffer against unexpected credit losses. A higher equity ratio generally improves financial stability and investor confidence.
b.Loan-to-Deposit Ratio (LDR): Ratio	FY2024 vs FY2025, Net Loans / Customer Deposits	68.5%,66.4%. 
Interpretation:
The decline reflects a more conservative lending posture and stronger deposit accumulation. While lower LDR levels may slightly dampen profitability, they improve liquidity and reduce funding risk.
c. Leverage Ratio: Ratio	FY2024 vs FY2025, Total Assets / Equity	11.5x, 10.4x
Interpretation:
The reduction in leverage indicates a strengthening balance sheet and lower financial risk profile. Lower leverage provides greater resilience during periods of economic stress.
d. Liquid Assets Ratio: Ratio	FY2024 vs FY2025, Liquid Assets / Total Assets	6.6%, 8.9%. 
Interpretation:
The increase reflects management's decision to prioritize liquidity preservation amid elevated credit uncertainty. This provides a stronger cushion against unexpected deposit withdrawals or market disruptions.
- Forecast Methodology
The balance sheet forecast is driven by a series of operating assumptions that are linked dynamically to the Income Statement and Valuation schedules.
The projected balance sheet remains fully integrated with the Income Statement, Cash Flow Statement, DCF Valuation, Relative Valuation and Investor Returns schedules, ensuring consistency across all model outputs.
- Takeaway: 
FY2025 reflects a deliberate shift toward balance sheet resilience rather than aggressive growth. Higher liquidity, stronger capitalization, reduced wholesale funding dependence and conservative loan growth collectively position NCBA to benefit from an eventual recovery in credit demand while maintaining adequate protection against credit deterioration. The model assumes that this stronger starting position supports sustainable earnings growth throughout the FY2026E–FY2030E forecast horizon.

      Tab 5: Cash Flow Statement
The Cash Flow Statement tab presents the consolidated Statement of Cash Flows for FY2024A and FY2025A together with forecast projections through FY2030E. The statement is prepared using the indirect method and reconciles reported accounting profits to actual cash generation.
The cash flow statement often provides a clearer picture of financial health than the income statement. While earnings can be influenced by provisioning assumptions, fair value movements, accrued interest and accounting estimates, cash flow reveals the true liquidity generating capacity of the franchise.
a. FY2025 Cash Flow Performance: 
FY2025 represented a transformational year for the group cash generation profile, with the Group delivering a substantial recovery in operating cash flows while maintaining a strong liquidity position.

- Cash Flow Summary

| Section                            | FY2024 (KES '000) | FY2025 (KES '000) |       Change |
| ---------------------------------- | ----------------: | ----------------: | -----------: |
| Net Cash from Operating Activities |      (14,457,339) |        38,231,821 |  +52,689,160 |
| Net Cash from Investing Activities |        15,164,656 |       (9,882,207) | (25,046,863) |
| Net Cash from Financing Activities |       (4,525,206) |      (12,759,638) |  (8,234,432) |
| Net Change in Cash                 |       (3,817,889) |        15,589,976 |  +19,407,865 |
| Closing Cash Balance               |        87,178,442 |       102,533,397 |       +17.6% |

The Group generated a net increase in cash of KES 15.6 billion during FY2025, lifting closing cash balances above KES 102 billion and materially strengthening liquidity.

b.  The KES 52.7 Billion Operating Cash Flow Turnaround
The most significant development in FY2025 was the dramatic reversal in operating cash flow generation.
Operating cash flow improved from a negative KES 14.5 billion in FY2024 to a positive KES 38.2 billion in FY2025, representing a turnaround of approximately KES 52.7 billion.
-Key Drivers
**1. Working Capital Reversal**
The principal driver was a sharp improvement in working capital dynamics.

| Working Capital Movement   |    FY2024 |  FY2025 |
| -------------------------- | --------: | ------: |
| Net Working Capital Impact | (43.5 bn) | +8.4 bn |

During FY2024, significant cash was tied up in balance sheet expansion and high yielding assets accumulated during the elevated interest rate environment.
As the operating environment stabilized in FY2025, these pressures reversed, generating a substantial cash inflow.
**2. Strong Interest Collections**
Interest receipts reached approximately KES 74.3 bn, demonstrating the underlying cash generating strength of the Group's loan portfolio and investment assets.
**3. Improved Deposit Dynamics**
Customer deposits continued to provide stable and relatively low cost funding, reinforcing liquidity generation and supporting the Group's operating cash conversion.
-Interpretation
The FY2025 operating cash flow performance confirms that earnings growth was supported by genuine cash generation rather than accounting adjustments.
This is a critical indicator of earnings quality and strengthens confidence in the sustainability of future dividend distributions and shareholder returns.
c. Investing Activities Analysis
Net investing cash flow moved from a KES 15.2 bn inflow in FY2024 to a KES 9.9 bn outflow in FY2025.
The outflow reflects:
* Increased investment in earning assets;
* Reallocation of liquidity into longer duration securities
* Capital expenditure supporting digital transformation initiatives
* Continued investment in technology infrastructure.
Interpretation:
While investing outflows reduced short term free cash flow, they represent investments intended to support future earnings growth and operational efficiency.
Management's willingness to reinvest cash generation into productive assets suggests confidence in the medium term operating outlook.
d. Financing Activities Analysis
Financing cash outflows increased to KES 12.8 billion during FY2025.
The primary drivers included:
* Dividend payments of KES 9.5 billion
* Repayment of wholesale borrowings
* Balance sheet deleveraging initiatives
* Optimization of the Group's funding structure.
Interpretation
The financing profile demonstrates a disciplined capital allocation strategy, balancing shareholder distributions with ongoing balance sheet strengthening.
e. Free Cash Flow Analysis
One of the most important outputs within the model is Free Cash Flow (FCF), which measures the cash available to shareholders after supporting ongoing investment requirements.

### FY2025 Free Cash Flow

Operating Cash Flow:           KES 38,231,821 '000

Less: Capital Expenditure:     KES (1,562,921) '000

────────────────────────────────────────

Free Cash Flow:               KES 36,668,900 '000

### Free Cash Flow Metrics

| Metric           |      FY2025 |
| ---------------- | ----------: |
| Free Cash Flow   | KES 36.7 bn |
| FCF Yield        |       56.4% |
| FCF / Net Profit |      156.8% |

Interpretation
The Group converted substantially more cash than it reported in accounting profits. An FCF conversion ratio above 100% is generally considered a hallmark of high-quality earnings and indicates:
* Strong cash collection performance
* Limited earnings manipulation risk
* Efficient working capital management
* Sustainable shareholder distributions.
The FY2025 conversion ratio of approximately 157% highlights the strength of NCBA's underlying cash generating franchise.

- Dividend Sustainability Analysis
The cash flow statement also provides the clearest assessment of dividend sustainability.

- FY2025 Dividend Coverage

| Metric         |       FY2025 |
| -------------- | -----------: |
| Dividends Paid |  KES 9.47 bn |
| Free Cash Flow | KES 36.67 bn |
| Dividend Cover |        3.87x |

Interpretation: the organization generated almost four times the cash required to fund shareholder distributions.
A dividend coverage ratio approaching 4x indicates:

* Significant headroom for future dividend growth.
* Low risk of dividend cuts under current conditions.
* Strong alignment between earnings and cash generation.
* Capacity to maintain distributions even during periods of elevated credit losses.
The model assumes a 50% payout ratio throughout the forecast period, with dividend coverage remaining comfortably above 3.0x under the Base Case scenario.

- Cash Flow Quality Ratios

The following ratios are monitored throughout the model to assess cash generation quality:

| Ratio                            | FY2025 | Interpretation                   |
| -------------------------------- | ------ | -------------------------------- |
| Operating Cash Flow / Net Profit | 163.5% | Exceptional cash conversion      |
| Free Cash Flow / Net Profit      | 156.8% | Strong earnings quality          |
| Dividend Coverage Ratio          | 3.87x  | Highly sustainable dividend      |
| Cash Growth Rate                 | 17.6%  | Strengthening liquidity position |
| Operating Cash Flow Margin       | 37.7%  | Robust operating efficiency      |

- Forecast Methodology

Projected cash flows are linked directly to assumptions contained within the Assumptions tab and integrated with the Income Statement and Balance Sheet forecasts.

Key forecast drivers include:
* Loan growth assumptions
* Deposit growth assumptions
* Net Interest Income projections
* Credit impairment forecasts
* Capital expenditure requirements
* Dividend payout ratios
* Working capital assumptions.
The cash flow schedule serves as the foundation for the model's Free Cash Flow to Equity (FCFE) calculations, Dividend Sustainability Analysis, Discounted Cash Flow (DCF) valuation and investor return metrics.

-Takeaway: FY2025 marks a significant inflection point in NCBA's cash generation profile. The Group delivered record operating cash flow, strengthened liquidity, reduced funding risk, maintained strong dividend coverage and generated free cash flow well in excess of reported earnings.
From an investor's perspective, the most compelling aspect of the FY2025 results is not simply the growth in profits but the fact that those profits translated into substantial and measurable cash generation. This provides a strong foundation for future dividends, capital accumulation, and long-term shareholder value creation.


    Tab 6:  DCF Valuation
The DCF Valuation tab estimates NCBA Group's intrinsic equity value using the Free Cash Flow to Equity (FCFE) methodology. The objective is to determine what the business is worth today based on the future cash flows expected to accrue to shareholders.
Unlike market based valuation techniques such as P/E or P/B multiples, which derive value from comparable companies, the DCF approach attempts to estimate intrinsic value directly from the company's future earnings power and cash generation capacity.
The valuation is fully integrated with the forecast Income Statement, Balance Sheet and Cash Flow Statement schedules, ensuring that every valuation output is linked to an underlying operational assumption.

- Why FCFE?
Valuing financial institutions requires a different framework from industrial or non financial businesses.
Banks are fundamentally different because:
* Customer deposits are the primary source of funding.
* Deposits are operating liabilities rather than discretionary financing decisions.
* Interest expense is an operating cost rather than a financing cost.
* Leverage is an integral component of the business model.
As a result, separating operating activities from financing activities becomes impractical.
The FCFE approach therefore provides a cleaner and more theoretically sound valuation framework because it focuses exclusively on the cash flows available to ordinary shareholders.

-FCFE Methodology
The model calculates FCFE using the following framework:
1. FCFE = PAT + D&A - Capex - Delta NWC
Where:
* **PAT** = Profit After Tax
* **D&A** = Depreciation & Amortisation
* **Capex** = Capital Expenditure
* **ΔNWC** = Change in Net Working Capital
The resulting cash flow represents the cash theoretically distributable to shareholders without impairing the ongoing operations of the business.

-Key Valuation Assumptions
| Assumption                     | Value             |
| ------------------------------ | ----------------- |
| Forecast Period                | 5 Years           |
| Discount Rate (Cost of Equity) | 14.0%             |
| Terminal Growth Rate           | 4.5%              |
| Projection Horizon             | FY2026E – FY2030E |
| Valuation Method               | FCFE DCF          |
| Currency                       | KES Millions      |

The 14.0% discount rate reflects the return required by equity investors given Kenya's risk profile, inflation expectations and the inherent risk associated with banking sector earnings.

The terminal growth rate of 4.5% approximates long term nominal GDP growth and inflation expectations within NCBA's core East African markets.

-Five Year FCFE Forecast
The valuation begins with explicit forecasts of cash available to shareholders.

| (KES mn)         | FY2026E | FY2027E | FY2028E | FY2029E | FY2030E |
| ---------------- | ------: | ------: | ------: | ------: | ------: |
| Net Profit (PAT) |  25,464 |  27,756 |  30,254 |  33,279 |  36,607 |
| Add: D&A         |     693 |     728 |     764 |     802 |     842 |
| Less: Capex      | (1,610) | (1,658) | (1,708) | (1,759) | (1,812) |
| Less: ΔNWC       |   (137) |   (145) |   (153) |   (161) |   (170) |
| FCFE             |  24,410 |  26,681 |  29,157 |  32,161 |  35,467 |

The forecast implies a compound annual FCFE growth rate exceeding 9%, broadly aligned with projected earnings growth and supported by gradual loan book expansion, stable margins and disciplined cost management.

-Discounting Future Cash Flows

Each forecast cash flow is discounted back to present value using the 14.0% cost of equity.

| Year    | FCFE (KES mn) | Discount Factor | Present Value |
| ------- | ------------: | --------------: | ------------: |
| FY2026E |        24,410 |          0.8772 |        21,410 |
| FY2027E |        26,681 |          0.7695 |        20,531 |
| FY2028E |        29,157 |          0.6750 |        19,681 |
| FY2029E |        32,161 |          0.5921 |        19,041 |
| FY2030E |        35,467 |          0.5194 |        18,418 |

- Present Value of Explicit Forecast Period
Total PV of Forecast FCFE:
**KES 99.1 billion**
This represents approximately one third of total intrinsic value.

- Terminal Value Analysis

Because banks are expected to operate indefinitely, a terminal value is required to capture cash flows generated beyond the explicit forecast period.

The model applies the Gordon Growth Method:

TV=FCFE{2031}}{r-g}
Where:

* r = Cost of Equity (14.0%)
* g = Terminal Growth Rate (4.5%)

-Terminal FCFE
Terminal FCFE = FY2030 FCFE × (1 + g)
35,467 × 1.045 = 37,063 KES mn
-Terminal Value:
37,063 ÷ (14.0% − 4.5%) = KES 390.1 billion
- Present Value of Terminal Value
Discounted back to FY2025:
PV(Terminal Value)
= KES 202.6 billion

-Valuation Bridge
The DCF valuation bridge converts forecast cash flows into equity value.

| Component                | Value (KES mn) |
| ------------------------ | -------------: |
| PV of Explicit FCFE      |         99,081 |
| PV of Terminal Value     |        202,562 |
| Enterprise Value         |        301,643 |
| Less: Borrowings         |        (7,565) |
| Add: Cash & CBK Balances |         63,774 |
| Equity Value             |        357,852 |

-Intrinsic Value Per Share

| Metric               |         Value |
| -------------------- | ------------: |
| Equity Value         |  KES 357.9 bn |
| Shares Outstanding   |   1,647.52 mn |
| DCF Value per Share  | KES 217 – 221 |
| Current Market Price |     KES 39.50 |
| Implied Upside       |   450% – 460% |

Interpretation
The model indicates a substantial disconnect between market price and intrinsic value.
The implied valuation suggests the market may be:
* Applying a significantly higher required return
* Pricing in future credit deterioration
* Discounting macroeconomic and regulatory risks
* Underestimating the long term earnings power of the franchise.

- Interpretation

Approximately two thirds of intrinsic value is derived from the terminal value calculation.
This is common for mature financial institutions and highlights the importance of carefully selecting:
* Long-term growth assumptions;
* Cost of equity assumptions;
* Sustainable profitability assumptions; and
* Capital allocation expectations.

 -Sensitivity Analysis
The valuation is most sensitive to three variables:

1. Cost of Equity (WACC Proxy)

A 1% increase in the discount rate reduces fair value by approximately 15–18%.

Higher required returns materially compress the present value of future cash flows.

 2. Terminal Growth Rate

A 0.5% reduction in terminal growth lowers intrinsic value by approximately 8–10%.

This reflects the large contribution of terminal value to overall equity value.

3. Earnings Growth

The valuation remains highly sensitive to:
* Net Interest Income growth
* Loan growth assumptions
* Credit impairment charges
* Cost-to-income ratio improvements.

- Key Valuation Ratios

| Metric                      |    Value |
| --------------------------- | -------: |
| Price / Intrinsic Value     |    0.18x |
| Margin of Safety            |     ~82% |
| Implied Upside              | 450–460% |
| Terminal Value Contribution |      67% |
| Cost of Equity              |    14.0% |
| Terminal Growth Rate        |     4.5% |

-Takeaway
The DCF analysis suggests that NCBA's intrinsic value substantially exceeds its current market valuation. Strong free cash flow generation, a growing capital base, resilient profitability and a well funded deposit franchise collectively support a significantly higher valuation than that implied by the prevailing share price.




