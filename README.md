# Investory Archetypes

Coding sample inspired by a behavioral finance experiment on retail investor overtrading.

What’s here
- `src/simulate.py` — generate synthetic trade-level panel (sessions × participants).
- `src/features.py` — compute behavioral features per participant (trades/min, reaction time, switching rate, strike distance, etc.).
- `src/models.py` — K-Means archetypes + Logit/Probit to predict excessive trading.
- `src/viz.py` — quick plots (optional).
- `src/main.py` — one-click pipeline (simulate → features → models → outputs/).


## Quick start
```bash
# create & activate a virtual env (optional)
python -m venv .venv
source .venv/bin/activate   # on Windows: .venv\Scripts\activate

pip install -r requirements.txt
python -m src.main
