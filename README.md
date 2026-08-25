# Cboe Global Markets Valuation

## Project Overview

This project presents a comprehensive equity valuation of Cboe Global Markets. It combines deterministic discounted cash flow methods, relative valuation and stochastic risk analysis.

The model uses Cboe's FY2023–FY2025 financial statements to forecast operating performance and cash flows from 2026 to 2030. It then estimates the company's equity value using several valuation approaches.

The project was completed as part of the Company Valuation coursework at HfWU Nürtingen-Geislingen.

## Valuation Methods

The analysis includes:

* Discounted cash flow valuation using the WACC approach
* Adjusted Present Value valuation
* Total Cash Flow approach
* Equity approach
* Bottom-up beta estimation based on comparable companies
* Trading multiples valuation
* Football field valuation summary
* Monte Carlo simulation with 10,000 trials
* Risk-premium valuation under imperfect capital markets
* Certainty-equivalent valuation

## Financial Forecast

The operating model forecasts Cboe's financial performance from 2026 to 2030.

The main forecast drivers include:

* Net revenue growth
* Operating expenses as a percentage of net revenue
* Depreciation and amortisation
* Effective tax rate
* Capital expenditure
* Operating net working capital

The model derives free cash flow forecasts from these operating assumptions and applies different discounting approaches to estimate enterprise and equity value.

## Monte Carlo Risk Analysis

The stochastic model performs 10,000 simulations of Cboe's future cash flows.

Revenue growth and EBIT margin are treated as stochastic variables based on their historical means and standard deviations. Tax rate, depreciation and amortisation, capital expenditure and net working capital are held at their historical average values.

The simulated cash-flow distributions are used to estimate:

* Expected total cash flows
* Cash-flow volatility
* Percentile outcomes
* Risk-adjusted costs of equity
* Risk premiums
* Certainty-equivalent cash flows

## Key Results

* DCF equity-value range: approximately **$24.4–$24.8 billion**
* Central DCF estimate: approximately **$24.6 billion**
* Risk-adjusted equity-value estimate: approximately **$23.5 billion**
* Risk-adjusted value per share: approximately **$223**

The risk-adjusted valuation is more conservative because it explicitly incorporates uncertainty in operating performance and the effects of imperfect capital markets.

## Repository Files

### `Cboe_Valuation_Model.xlsm`

Contains:

* Historical financial statements
* Forecast assumptions
* Operating and free-cash-flow forecasts
* Cost of equity and bottom-up beta
* WACC, APV, Total Cash Flow and Equity valuations
* Trading multiples
* Football field valuation summary

### `Cboe_Risk_Adjusted_Valuation.xlsm`

Contains:

* Forecasting assumptions
* Monte Carlo inputs
* 10,000 simulated cash-flow paths
* Statistical simulation output
* Risk analysis
* Risk-premium valuation
* Certainty-equivalent valuation
* Final valuation comparison

## Tools and Data

* Microsoft Excel
* Cboe Global Markets annual reports
* Financial-statement analysis
* Comparable-company analysis
* Monte Carlo simulation

## Disclaimer

This project was developed for personal purposes. The assumptions and valuation results reflect the information available at the time of the analysis and do not constitute investment advice.
