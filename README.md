# Yield Inversion — Paper 2: FRED API Pipeline

Minimal, reproducible pipeline to pull 10Y, 2Y, and 3M Treasury yields from FRED and compute common inversion spreads.

What this repo does
Pulls 10Y, 2Y, 3M from FRED (with your key) and writes treasury_yields.csv + standard spreads (10Y–2Y, 10Y–3M).
Use this to reproduce figures in this paper. Run python api_pull.py anytime to refresh with the latest data.

## Quickstart

**Requirements**
- Python 3.10+
- A free FRED API key: https://fredaccount.stlouisfed.org/apikey

**1) Clone**
```bash
git clone https://github.com/syk-hub/yield-inversion-paper-1.git
cd yield-inversion-paper-1


