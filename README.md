# solar-challenge-week0

## Overview
Solar Data Discovery — Week 0. This repo contains code for environment setup, EDA, cleaning, and a Streamlit dashboard prototype.

## Quick start (local)
1. Clone:
   git clone https://github.com/<your-username>/solar-challenge-week0.git
   cd solar-challenge-week0

2. Create virtualenv and activate:
   - Linux / macOS:
     python3 -m venv .venv
     source .venv/bin/activate
   - Windows (PowerShell):
     python -m venv .venv
     .\.venv\Scripts\Activate.ps1

3. Install:
   pip install --upgrade pip
   pip install -r requirements.txt

4. Run notebooks with Jupyter:
   jupyter lab

5. Run the Streamlit app (from repo root):
   streamlit run app/main.py

## Branching
- setup-task: initial setup and CI
- eda-benin, eda-sierra-leone, eda-togo: per-country EDA
- compare-countries: merged EDA and comparisons
- dashboard-dev: Streamlit app development

## Notes
- data/ is ignored — DO NOT commit raw CSVs.
- Export cleaned CSVs to `data/` locally for the app to read.