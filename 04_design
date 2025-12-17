Design – Underground Coal Mine Explosion Prediction Desktop App

Design goals
- Make it easy to load or input mine activity data (CSV/manual forms)
- Guide the user step by step: import data → configure model → run prediction → review results
- Present predictions and risk explanations clearly for engineers and safety officers

Key screens

1) Home / Project screen
- Simple landing screen with:
  - Button: Create new analysis
  - List of previous analyses (file name, date run, mine/zone)
<img width="557" height="363" alt="minset" src="https://github.com/user-attachments/assets/4ad9b1f4-25d8-4caa-9f4b-f517a411a407" />

2) Data import screen
Screenshot: `ui-data-import.png`
- Options to:
  - Select a CSV file with mine activity data
  - See required columns/fields (e.g. timestamp, zone, gas readings, airflow, temperature)
- Basic data preview table
- Simple checks/warnings if key columns are missing
<img width="557" height="274" alt="mineset2" src="https://github.com/user-attachments/assets/8591e3fc-3a61-49e2-9f5b-211d22fbb8dd" />

3) Model configuration screen
Screenshot: `ui-model-config.png`
- Let the user:
  - Choose which variables to include (e.g. gas type, temperature, CO, equipment parameters)
  - Set basic options (time window, zone filters)
- Short text explaining what the model will do in plain language
<img width="556" height="346" alt="data" src="https://github.com/user-attachments/assets/958e921f-f3a0-4c5b-9918-0306a5d2a2ce" />

4) Results / Risk overview screen
Screenshot: `ui-results-overview.png`
- Table view with one row per zone/time window:
  - Zone, time range, risk score (0–100 or Low/Medium/High)
  - Short explanation (e.g. “Rising methane + reduced airflow”)
- Simple chart area with trends for a selected zone

5) Detail view for a single analysis
Screenshot: `ui-analysis-detail.png`
- Shows:
  - Input data summary
  - Model metrics (accuracy, confusion matrix – high level)
  - Factors contributing most to risk in that analysis

Visual style
- Simple, data‑tool look (no heavy gradients)
- High contrast with clear colour coding for risk levels
- Text labels always shown with colours so it’s readable on basic monitors

