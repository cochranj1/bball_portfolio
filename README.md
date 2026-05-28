# Basketball Analytics Portfolio

Public repository for basketball analytics projects. Work currently includes
a quantitative validation of a framework for prospect evaluation.

---

## Projects

### SPF Model — Quantifying a Framework for Evaluating NBA Prospect Potential

A quantitative model for evaluating NBA draft prospects using publicly available 
college basketball statistics. The model scores prospects across three foundational 
pillars — Skill, Physicality, and Feel — and validates that high composite scores 
disproportionately predict star and starter outcomes over rookie contract timelines.

**Key findings:**
- Top-20% SPF scorers disproportionately produces star and starter outcomes.
- Model carries statistically significant orthogonal signal relative to draft 
  consensus (residual concordance: 0.576, 95% CI: 0.535–0.593), indicating 
  systematic identification of players the market misprices using only publicly 
  available college data

**Links:**
- [Full write-up](https://belowtherim.substack.com/p/spf-score-how-positional-skill-physicality)
- [Draft class boards](https://docs.google.com/spreadsheets/d/1k9D0SUzhbhiBtCVeLGc3mii9nXjnSpd6rsh3FP96GJE/edit?gid=1412637268#gid=1412637268)
- [Notebook](SPF_Model/SPF_Model.ipynb)

**Stack:** Python, pandas, NumPy, scikit-learn, Matplotlib, Bart Torvik CBB data, DBT

---

## About

Joe Cochran — Data Scientist with a focus on basketball analytics.
