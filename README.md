# Yield Inversion — Paper 2

This repo reuses the Paper 1 FRED pipeline to pull 10Y, 2Y, 3M and compute spreads (10Y–2Y, 10Y–3M). Use it to reproduce Paper 2 figures with fresh data.

## Quickstart
1) Copy `.env.example` → `.env`, paste your FRED key:

2) Install:
```bash
pip install -r requirements.txt


python api_pull.py



