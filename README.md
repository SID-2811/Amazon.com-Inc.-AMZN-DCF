# Amazon Sum-of-The-Parts (SOTP) DCF Valuation

This project performs a *Sum-of-The-Parts Discounted Cash Flow (SOTP-DCF)* valuation of *Amazon (AMZN)* using segment-level forecasts, fundamental drivers, comparable company benchmarking, and terminal value approaches. The goal is to estimate Amazon’s intrinsic equity value on a per-share basis.

---

## Objective
To model Amazon by valuing key business segments separately, forecasting free cash flows, applying an appropriate discount rate (WACC), and converting enterprise value to equity value using a fully diluted share count.

---

## Segments Analyzed
- AWS (Cloud)
- North America Retail
- International Retail
- Advertising / Other Revenue Streams

Each segment is modelled independently based on growth, margins, reinvestment needs, and competitive positioning.

---

## Data Collection
Historical financial and segment disclosures were sourced from:
- Amazon 10-K filings
- Segment reporting
- Investor presentations
- Public datasets / market research

---

## Forecast Assumptions
For each segment, the following were forecasted:
- Revenue Growth
- EBIT Margins
- Depreciation & Amortization
- Capital Expenditure (CAPEX)
- Change in Net Working Capital
- Cash Taxes

These forecasts drive annual *Free Cash Flow (FCF)* generation.

---

## Discount Rate (WACC)
Weighted Average Cost of Capital was calculated using:
- *Cost of Equity via CAPM*
- *Cost of Debt after tax*
- *Market-based capital structure*

This reflects Amazon’s risk profile and sector risk premiums.

---

## Beta Calculation
Bottom-up beta was estimated using:
- Business-model comparable companies
- Unlevering and relevering based on Amazon’s debt-to-equity

This ensures a more stable beta vs historical regression noise.

---

## Comparable Company Analysis (Comps)
Peer benchmarking used valuation multiples such as:
- EV/EBITDA
- EV/Revenue
- P/E

Comparable companies included:
- Alphabet (GOOGL)
- Microsoft (MSFT)
- Meta (META)
- Apple (APPL)
- Nvidia (NVDA)
- Walmart (WMT)

These multiples validate terminal valuation and market expectations.

---

## Terminal Value Approaches

### Perpetuity Growth Method
- Based on long-term sustainable GDP-aligned growth

### Exit Multiple Method
- Using comparable EV/EBITDA multiples at terminal year

Both methods are cross-checked for sanity.

---

## Fully Diluted Shares
Fully diluted share count was calculated by including:
- Outstanding shares
- Stock-based compensation dilution
- Restricted stock units (RSUs)
- Options (if material)

This ensures accurate per-share equity value.
