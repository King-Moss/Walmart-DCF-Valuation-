# Walmart Inc. (WMT) — DCF Valuation

**Ticker:** WMT | **Exchange:** NYSE | **Valuation Date:** 8 July 2026
**Data Source:** FactSet Fundamentals | **Methodology:** Discounted Cash Flow (FCFF)

---

## Company Overview

Walmart is the largest retailer on earth by revenue, with over 10,500 stores across 19 countries and an e-commerce operation that has quietly become one of the largest in the US. The business runs on three segments: Walmart US (the core), Walmart International, and Sam's Club. What makes the company analytically interesting right now is not the stores — it is what is happening above and around them. Walmart has spent the past four years building a data and advertising infrastructure that sits on top of its retail operations, and that layer is growing faster and at far higher margins than the underlying business. The fiscal year 2026 data used in this model captures the early stages of that transition.

---

## Investment Thesis

Walmart is undergoing a structural margin shift that the headline revenue figures obscure. The retail business — large, slow, and competitively well-defended — provides the cash flow base. But the more interesting story is the build-out of Walmart Connect (its retail media network), the Walmart+ membership programme, and the monetisation of its first-party transaction data. These businesses carry margins that are structurally different from selling groceries.

Retail media is the clearest example. Walmart Connect generated over $4.4B in advertising revenue in FY2026, growing north of 24% year-on-year. For context, that business has EBIT margins that run 60-70%, sitting inside a company whose overall EBIT margin is 4.2%. As advertising scales, it mechanically pulls group margins upward without requiring proportional SG&A growth. The same logic applies to Walmart+: once a member is acquired, the incremental cost of serving them is low, but the behavioural data they generate increases Walmart's ability to monetise advertising and personalise promotions.

The AI angle is not speculative — it is already showing up in the cost structure. Walmart has been deploying large language models across store operations, supplier negotiations, and customer-facing search. The company's internal AI tools, built partly on partnerships with Microsoft and internally developed models, are being used to automate planogram compliance (store shelf arrangement), detect spoilage in fresh produce, and optimise last-mile delivery routing. These are not pilot programmes — they are operating at scale across thousands of locations. The efficiency gains compress labour cost per unit of revenue over time, which is the mechanism through which EBIT margins recover toward and beyond the FY2022 peak of 4.97% even as capex remains elevated.

The capex surge (from $10.3B in FY2021 to $26.6B in FY2026) is the single biggest source of near-term FCF compression and the biggest risk to the thesis. The model assumes that capex as a percentage of revenue reverts toward historical averages as the current investment cycle matures. If Walmart continues investing at FY2026 intensity beyond the forecast window, the terminal value assumption breaks down. That risk is explicit and quantified in the sensitivity analysis.

The bear case is straightforward: Amazon continues gaining share in grocery, Walmart's advertising revenue growth decelerates as the market matures, and the capex cycle never normalises. Under those conditions, and using a WACC of 8.0% with a TGR of 3.5%, the model yields an implied price of approximately $55 — a significant downside to the current market price. The optimistic case, by contrast, prices the stock at $155.73, implying 39.2% upside at a WACC of 6.5% and a TGR of 4.5%.

The base case sits closer to fair value: WACC of 7.0%, TGR of 4.0%, base revenue growth trajectory. At those inputs the model implies a price in the mid-$70s, which suggests the market is already pricing in a meaningful portion of the advertising and membership optionality — but not all of it.

---

## Historical Financial Performance

All figures in USD billions unless stated.

| Metric | FY2021 | FY2022 | FY2023 | FY2024 | FY2025 | FY2026 |
|---|---|---|---|---|---|---|
| Revenue | 559.2 | 572.8 | 611.3 | 648.1 | 681.0 | 713.2 |
| Revenue Growth | 6.7% | 2.4% | 6.7% | 6.0% | 5.1% | 4.7% |
| EBIT | 26.9 | 28.4 | 24.5 | 27.0 | 29.4 | 29.8 |
| EBIT Margin | 4.8% | 5.0% | 4.0% | 4.2% | 4.3% | 4.2% |
| D&A | 11.2 | 10.7 | 10.9 | 11.9 | 13.0 | 14.2 |
| Capex | 10.3 | 13.1 | 16.9 | 20.6 | 23.8 | 26.6 |
| NOPAT | 20.1 | 23.7 | 18.8 | 21.4 | 23.2 | 22.6 |
| Net Operating Cash Flow | 36.1 | 24.2 | 28.8 | 35.7 | 36.4 | 41.6 |

Two things stand out in this historical data. First, EBIT margins troughed in FY2023 at 4.0% and have since recovered, but have not yet regained the FY2022 peak. The recovery is happening while capex is still rising, which means the underlying business is generating margin improvement faster than the investment cycle is consuming it — a positive signal. Second, net operating cash flow jumped to $41.6B in FY2026, the highest in the series, while free cash flow (after the heavy capex spend) remains compressed. The divergence between operating and free cash flow is entirely explained by the investment cycle.

---

## Forecast Assumptions

The model uses a 5-year explicit forecast period (FY2027-FY2031). Revenue growth, EBIT margin, D&A, capex, and working capital changes are each forecast as a rolling 5-year average of historical ratios, updated annually. The three scenarios scale the base revenue growth rate using a multiplier.

| Assumption | Pessimistic | Base | Optimistic (active) |
|---|---|---|---|
| Revenue growth multiplier | 0.8x rolling avg | 1.0x rolling avg | 1.2x rolling avg |
| WACC | 8.0% | 7.0% | 6.5% |
| Terminal Growth Rate | 3.5% | 4.0% | 4.5% |

The multiplier scales the 5-year trailing average revenue growth rate. A value of 0.8 means the pessimistic case assumes 80% of the base growth rate; 1.2 means the optimistic case assumes 120%.

**Revenue Forecast (Optimistic Case, FY2027-FY2031)**

| FY2027E | FY2028E | FY2029E | FY2030E | FY2031E |
|---|---|---|---|---|
| $749.7B | $793.8B | $840.9B | $892.7B | $951.9B |

**EBIT Margin Forecast:** Held broadly flat at ~4.3-4.4% across the forecast period, reflecting continued investment pressure offset by the mix-shift toward higher-margin businesses.

---

## WACC

| Component | Value | Source |
|---|---|---|
| Risk-free rate (Rf) | 4.47% | US 10-Year Treasury (CNBC) |
| Equity beta | 0.60 | Stock Analysis |
| Market risk premium (MRP) | 4.46% | Damodaran |
| Cost of equity (Re) | 7.15% | CAPM: Rf + β × MRP |
| Cost of debt (Rd) | 4.00% | Walmart annual report |
| Effective tax rate | ~20.6% | 5-year historical average |
| After-tax cost of debt | ~3.18% | Rd × (1 - t) |
| Equity weight (E/V) | 96.3% | Market cap / (Market cap + Debt) |
| Debt weight (D/V) | 3.7% | Debt / (Market cap + Debt) |
| **WACC (computed)** | **7.00%** | Weighted average |

Walmart's low beta (0.60) reflects its defensive, non-discretionary revenue mix. The near-all-equity capital structure (96.3% equity by market value) means the WACC is almost entirely driven by the cost of equity, making it relatively insensitive to changes in the cost of debt.

---

## Discounted Cash Flow Valuation

**FCFF = NOPAT + D&A - Capex - Change in Working Capital**

Mid-year convention applied to all discount periods.

| | FY2027E | FY2028E | FY2029E | FY2030E | FY2031E |
|---|---|---|---|---|---|
| NOPAT ($B) | 26.1 | 26.6 | 28.7 | 30.6 | 32.7 |
| D&A ($B) | 14.9 | 15.8 | 16.7 | 17.8 | 19.0 |
| Capex ($B) | 16.4 | 17.9 | 19.9 | 21.7 | 23.1 |
| Change in WC ($B) | 0.5 | (1.3) | (0.9) | (0.6) | (0.7) |
| **FCFF ($B)** | **24.2** | **25.8** | **26.4** | **27.3** | **29.3** |
| Discounted FCFF ($B) | 23.4 | 23.5 | 22.6 | 21.9 | 22.0 |

Terminal value estimated using the Gordon Growth Model:

> TV = FCFF₅ × (1 + g) / (WACC - g)

**Valuation Bridge — Optimistic Case (WACC = 6.5%, TGR = 4.5%)**

| Item | Value ($B) |
|---|---|
| Sum of discounted FCFFs | 113.4 |
| Terminal Value (undiscounted) | 1,529.5 |
| Discounted Terminal Value | 1,152.1 |
| **Enterprise Value** | **1,265.5** |
| Plus: Cash | 10.7 |
| Less: Debt | (34.6) |
| **Equity Value** | **1,241.6** |
| Shares Outstanding | 7.97B |
| **Implied Share Price** | **$155.73** |

Terminal value accounts for approximately 91% of enterprise value, which is high but consistent with a mature, low-growth business where near-term FCF is compressed by a capital investment cycle. This concentration makes the TGR assumption the most consequential variable in the model.

---

## Sensitivity Analysis

Implied share price (USD) across WACC and terminal growth rate combinations — Optimistic revenue scenario.

| | TGR 2.0% | TGR 2.4% | TGR 2.8% | TGR 3.2% | TGR 3.6% |
|---|---|---|---|---|---|
| WACC 6.50% | 73.91 | 80.30 | 88.07 | 97.72 | 110.03 |
| WACC 6.75% | 69.91 | 75.57 | 82.37 | 90.70 | 101.15 |
| WACC 7.00% | 66.31 | 71.35 | 77.34 | 84.61 | 93.58 |
| WACC 7.25% | 63.05 | 67.56 | 72.89 | 79.27 | 87.04 |
| WACC 7.50% | 60.08 | 64.15 | 68.90 | 74.55 | 81.35 |
| WACC 7.75% | 57.38 | 61.05 | 65.32 | 70.35 | 76.34 |
| WACC 8.00% | 54.90 | 58.23 | 62.09 | 66.58 | 71.89 |
| WACC 8.25% | 52.61 | 55.66 | 59.15 | 63.19 | 67.93 |

Note: These figures use the optimistic revenue growth trajectory. Base and pessimistic revenue scenarios would produce lower implied prices across all WACC/TGR combinations. At the current market price of $111.85, the stock is only covered by the upper-right corner of this table — high TGR, low WACC — which requires a specific combination of sustained revenue acceleration and stable rates to hold.

---

## Key Risks

**Capex cycle extension.** The single biggest model risk. Walmart has guided for continued heavy investment through at least FY2027. If the cycle extends further, or if automation investments yield lower productivity gains than expected, FCF remains compressed and the terminal value assumption overstates normalised earnings power.

**Advertising growth deceleration.** Retail media is the margin expansion story. If Walmart Connect's growth decelerates — due to competition from Amazon Ads, Google, or a pullback in CPG advertising budgets — the margin recovery built into the forecast does not materialise.

**AI efficiency gains are uncertain.** The operational AI deployment is real but the financial impact is difficult to isolate in reported results. If labour savings from AI tools are offset by incremental technology costs or require more capex than anticipated, the margin thesis weakens.

**Terminal growth rate sensitivity.** The TV represents ~91% of EV. A 50 basis point reduction in the TGR (from 4.5% to 4.0%) reduces the implied price by approximately $30 at the optimistic WACC. The model is more sensitive to TGR than to any other single assumption.

**Consumer spending softness.** Walmart is defensive relative to most retailers, but a sustained contraction in consumer spending — particularly in general merchandise, which carries higher margins than grocery — would compress revenue growth and EBIT margins simultaneously.

---

## Disclaimer

This model was developed for educational and investment research purposes. It does not constitute investment advice or a recommendation to buy or sell any security. All assumptions are the author's own and do not represent the views of any employer or affiliated institution.
