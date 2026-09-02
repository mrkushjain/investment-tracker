# Investment Tracker

US Stocks Capital Gains Tracker for Indian ITR filing — FY 2026-27.

**Live dashboard:** https://mrkushjain.github.io/investment-tracker/

## What it tracks

- **Kanchan Handa** — SLAB (Schwab RSU) + AMZN (IndMoney, 218.97 shares, 23 lots)
- **Kush Jain** — CRM (E\*TRADE ESPP + RSU) + AMZN (IndMoney, 69.09 shares, 11 lots)

## Features

- LTCG / STCG classification per Indian tax rules (>24 months = LTCG @ 12.5%)
- INR conversion using SBI TTBR on transaction date
- Tax estimate box (LTCG @ 12.5%, STCG @ 30% slab)
- Section 54F property purchase tracker (LTCG proceeds only)
- Live TradingView price widgets (SLAB, MSFT, CRM, AMZN)
- Per-person tabs (Kanchan / Kush / Combined)
- CSV export for ITR filing

## Data

All lot data lives in [`stocks.csv`](stocks.csv). The dashboard reads from `localStorage` (seeded from the SEED array in `index.html` on first load).

> Tax estimates are indicative only — consult a CA for ITR filing.
