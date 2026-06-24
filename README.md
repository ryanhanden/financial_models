# Financial Modeling Portfolio

A portfolio of self-directed public-company financial models built to demonstrate investment-banking, equity-research, and valuation modeling skills.

Each workbook includes EDGAR-tied historical financials, company-specific operating drivers, forecast assumptions, an integrated three-statement model, unlevered discounted cash flow valuation, WACC / terminal-growth sensitivity analysis, source mapping, and QA checks.

The purpose of this portfolio is to demonstrate hands-on modeling fluency: historical tie-out to primary-source filings, statement linkage, projection logic, DCF construction, and the judgment behind valuation assumptions. These models are for educational and demonstration purposes only and are not investment advice.

## Completed Models

| Company                              | Ticker | Model Type                  | Status   |
| ------------------------------------ | -----: | --------------------------- | -------- |
| Airbnb, Inc.                         |   ABNB | 3-Statement + Unlevered DCF | Complete |
| Uber Technologies, Inc.              |   UBER | 3-Statement + Unlevered DCF | Complete |
| Chevron Corporation                  |    CVX | 3-Statement + Unlevered DCF | Complete |
| Salesforce, Inc.                     |    CRM | 3-Statement + Unlevered DCF | Complete |
| Palantir Technologies Inc.           |   PLTR | 3-Statement + Unlevered DCF | Complete |
| Restaurant Brands International Inc. |    QSR | 3-Statement + Unlevered DCF | Complete |

## Model Files

| Company | File |
|---|---|
| Airbnb | `airbnb_model.xlsx` |
| Uber | `uber_model.xlsx` |
| Chevron | `chevron_model.xlsx` |
| Salesforce | `salesforce_model.xlsx` |
| Palantir | `palantir_model.xlsx` |
| Restaurant Brands International | `restaurant_brands_model.xlsx` |
## What Each Model Includes

Each workbook is designed to show the full modeling process from historical statements through valuation output:

* Historical income statement, balance sheet, and cash flow statement actuals tied to SEC EDGAR filings
* Company-specific operating drivers and segment detail
* Forecast assumptions separated from historical actuals
* Integrated three-statement forecast model
* Working capital, capital expenditure, depreciation, cash flow, and balance-sheet checks
* Unlevered free cash flow build
* Discounted cash flow valuation
* WACC and terminal-growth sensitivity analysis
* Source map documenting filing sources
* QA checks for historical tie-outs, balance-sheet balance, cash-flow bridge, and formula errors

## Historical Actuals vs. Forecast Assumptions

Historical actuals are sourced from company 10-K filings and treated as factual model inputs. Forecast years are assumption-driven and are clearly separated from historical hardcodes. The DCF output is not intended to represent a definitive price target; it reflects the valuation implied by the model’s stated assumptions.

## Company-Specific Focus

### Airbnb, Inc. (ABNB)

Airbnb is modeled as an asset-light travel marketplace, with emphasis on revenue growth, operating margin expansion, free cash flow generation, deferred revenue dynamics, customer-funds pass-through treatment, and net cash in the equity bridge.

### Uber Technologies, Inc. (UBER)

Uber is modeled using a segment-driven framework across Mobility, Delivery, and Freight. The model highlights revenue growth, margin expansion, free cash flow generation, and earnings-quality analysis related to large tax benefits.

### Chevron Corporation (CVX)

Chevron is modeled as an integrated energy company, with attention to upstream and downstream earnings, commodity-price sensitivity, capital intensity, dividends, buybacks, and free cash flow through the cycle.

### Salesforce, Inc. (CRM)

Salesforce is modeled as a mature enterprise software company, with emphasis on subscription revenue, professional services revenue, operating leverage, cash generation, deferred revenue, stock-based compensation, and valuation sensitivity.

### Palantir Technologies Inc. (PLTR)

Palantir is modeled as a high-growth software and analytics company, with emphasis on government versus commercial revenue, growth deceleration, margin expansion, stock-based compensation, cash conversion, and long-term DCF sensitivity.

### Restaurant Brands International Inc. (QSR)

Restaurant Brands is modeled as a global franchisor and restaurant holding company, with emphasis on system-wide sales, segment performance, royalty and franchise economics, debt, dividends, capital expenditures, and free cash flow.

## Formatting Conventions

The models generally follow standard financial modeling color conventions:

* Blue = hardcoded historical actual or assumption
* Black = formula / calculation
* Green = linked value from another sheet
* Red / check rows = QA or balance checks

## Data Sources

Primary data sources include SEC EDGAR filings, company Forms 10-K, company annual reports, and investor-relations materials. Source details are included inside each workbook.

Built independently as part of a self-directed effort to develop investment-banking, valuation, and financial modeling skills.
