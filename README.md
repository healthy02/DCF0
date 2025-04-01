# DCF0
Discounted Cash Flow (DCF) Analysis Model for Zydus Lifesciences Corporation
## Overview
This repository contains a comprehensive Discounted Cash Flow (DCF) analysis model tailored for valuing Zydus Lifesciences Corporation. The model evaluates the intrinsic value of Zydus Lifesciences' stock by forecasting future cash flows and discounting them to their present value. The analysis provides insights into whether the stock is overvalued or undervalued compared to its market price.

## Key Features
DCF Valuation: Calculates the intrinsic value of Zydus Lifesciences' stock using a two-stage DCF model.

Sensitivity Analysis: Assesses how changes in key assumptions (e.g., growth rates, discount rates) impact valuation.

Customizable Parameters: Allows users to adjust inputs such as revenue growth, operating margins, and terminal growth rates.

Comprehensive Outputs: Includes present value, firm value, equity value, and per-share valuation.

## Model Highlights
### 1. Present Value Calculation
The model projects future cash flows based on assumptions about revenue growth and operating performance. These cash flows are discounted using a selected discount rate (typically the Weighted Average Cost of Capital or WACC). For Zydus Lifesciences:

Present Value of forecasted cash flows: ₹517.8 billion

Discount Rate: 13% (based on risk-free rate and equity risk premium).

### 2. DCF Value Calculation
The DCF value is derived by adjusting the present value for:

Cash & Equivalents: ₹15.9 billion

Investments: ₹31.5 billion

Debt: ₹1.8 billion

Minority Interests: ₹23.3 billion
This results in an equity value of ₹540.1 billion, divided by 1 billion shares outstanding to yield a DCF value per share of ₹536.76.

### 3. Sensitivity Analysis
The model includes sensitivity analysis to visualize valuation changes under different scenarios:

Growth Stage Rate: 20% (capped based on historical performance)

Terminal Growth Rate: 4%.

### Getting Started
Download the DCF model template from this repository.

Input financial data for Zydus Lifesciences into the designated fields:
Revenue growth rate
Operating margins
Discount rate (WACC)
Terminal growth rate

Review calculated outputs in the summary section.

### How to Use
Input Assumptions: Adjust parameters like revenue growth, discount rate, and terminal growth rate in the input sheet.

Run Analysis: The model will automatically calculate:

Present Value of Cash Flows
Terminal Value
Equity Value per Share

Interpret Results:

Compare the calculated intrinsic value with the current market price.
Use sensitivity analysis to understand risks and opportunities.

Example Output
For Zydus Lifesciences:

Intrinsic Value (DCF): ₹536.76 per share
Market Price (as of March 2025): ₹886.40 per share
Conclusion: The stock is overvalued by approximately 39%.

Customization Options
You can customize the following parameters to reflect your assumptions:

Discount Rate (WACC)
Growth Stage Duration (default: 10 years)
Terminal Growth Rate (default: 4%)
Free Cash Flow Projections

### Known Issues
The model assumes constant growth rates during terminal stages, which may not reflect real-world complexities.
Also, You may use this formula for the Sensitivity Analysis in Google Sheets, define a new function and use this to calculate, with only 2 inputs 'w' and 'g' which represent the different values of WACC and growth rate respectively.

((DCF!$M$4*(1+g)/(w-g))/(1+w)^DCF!$M$6 + DCF!$I$4/(1+w)^DCF!$I$6 + DCF!$J$4/(1+w)^DCF!$J$6 + DCF!$K$4/(1+w)^DCF!$K$6 + DCF!$L$4/(1+w)^DCF!$L$6 + DCF!$M$4/(1+w)^DCF!$M$6 + DCF!$C$16 - DCF!$C$17 - DCF!$C$18) / DCF!$C$20

Sensitivity analysis does not account for macroeconomic shocks, black swan events or industry-specific risks.

### Contributors
This DCF analysis model was developed using publicly available financial data from sources such as Screener and Moneycontrol.
