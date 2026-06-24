# Financial Modeling Portfolio

A set of self-directed equity valuation models built to investment-banking standards. Each model is a fully integrated three-statement operating model paired with a discounted-cash-flow (DCF) valuation, built from primary-source SEC filings.

The goal of this portfolio is to demonstrate hands-on modeling fluency — statement linkage, projection logic, DCF construction, and the judgment behind the assumptions — rather than to publish price targets.

---

## Models

| Company | Ticker | Type | Status |
|---|---|---|---|
| Airbnb, Inc. | ABNB | 3-Statement + Unlevered DCF | Complete |
| Chevron Corporation | CVX | 3-Statement + Unlevered DCF | In progress |
| Palantir Technologies | PLTR | 3-Statement + Unlevered DCF | In progress |
| Salesforce, Inc. | CRM | 3-Statement + Unlevered DCF | In progress |
| Uber Technologies | UBER | 3-Statement + Unlevered DCF | In progress |
| Restaurant Brands Intl. | QSR | 3-Statement + Unlevered DCF | In progress |

---

## Featured model - Airbnb, Inc. (ABNB)

**File:** `Airbnb_3-Statement_Model_and_DCF.xlsx`

A fully linked operating model with historicals tied to the FY2023 and FY2024 Forms 10-K and a five-year projection (FY2025–FY2029), feeding an unlevered DCF with a WACC build and a two-way sensitivity table.

### What it contains
- **Drivers tab** - every assumption isolated as an input (revenue growth, cost ratios, tax rate, working-capital and capex intensity, DCF parameters), so the model is fully driver-driven.
- **Income Statement, Balance Sheet, Cash Flow** - integrated and cross-linked. Net income, depreciation, capex, and ending cash wire across the three statements; the balance sheet balances to zero in every year.
- **DCF** - unlevered free cash flow, CAPM-based cost of equity, WACC, Gordon-growth terminal value, enterprise-to-equity bridge, and a WACC × terminal-growth sensitivity grid.

### Approach and key analytical choices
- **Asset-light marketplace.** Capex and D&A run well below 1% of revenue, so the valuation is driven by operating margin rather than reinvestment - reflected in the projection structure.
- **Deferred-revenue float.** Unearned fees scale with revenue, so growth is a *source* of cash rather than a use; the business runs on negative working capital.
- **Customer-funds pass-through.** Funds receivable and funds payable are held equal and net to zero, rather than being treated as operating working capital.
- **Net-cash position.** With cash and investments well above debt, net cash is added back in the equity bridge rather than subtracted.
- **Circularity handled deliberately.** Interest is computed on opening balances, avoiding a circular reference and the need for a revolver, with the trade-off stated explicitly.

### Reading the model
- **Blue** = hardcoded input / assumption
- **Black** = calculation within the sheet
- **Green** = link pulling from another sheet
- Negatives shown in parentheses; the Balance Sheet includes a live balance-check row.

### Data sources
Airbnb, Inc. Forms 10-K (FY2024 and FY2025 comparatives) and FY2023/FY2024 earnings releases, via SEC EDGAR (CIK 0001559720). All figures in US$ millions except per-share data.

---

*Built independently as part of a self-directed effort to develop investment-banking and valuation modeling skills. Models are for demonstration and educational purposes and are not investment advice.*
