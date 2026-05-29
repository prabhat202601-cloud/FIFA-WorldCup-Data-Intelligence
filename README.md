# FIFA World Cup Data Intelligence Project
### 84 Years of Football History — Explored, Analysed, and Visualised with Claude AI

---

## Overview

This is an end-to-end data intelligence project built on the FIFA World Cup Matches dataset (1930–2014). The entire workflow — from raw data exploration to statistical hypothesis testing to interactive dashboards to a stakeholder presentation — was executed inside Claude AI using natural language, with zero manual code written.

The project was built to apply skills learned from the Claude AI Masterclass by Dr. Ryan Ahmed, covering agentic workflows, the data analysis plugin, and prompt engineering techniques.

---

## Dataset

- **Source:** Publicly available FIFA World Cup Matches dataset (GitHub)
- **Coverage:** 852 matches across 20 tournaments (1930–2014)
- **Columns:** 20 — including teams, goals (home/away/half-time/full-time), attendance, stage, city, referee, and match metadata
- **Missing values:** Only 2 rows (attendance) in the entire dataset
- **File:** `WorldCupMatches_1930-2014_Dataset.xlsx`

---

## Project Outputs

| File | Description |
|------|-------------|
| `FIFA_WorldCup_DataDashboard_1930-2014.html` | Full interactive dashboard with KPI cards, goals trend, top scoring nations, match result breakdown, and attendance analysis |
| `FIFA_WorldCup_MatchesExplorer_Interactive.html` | Purpose-built matches explorer with Chart.js visualizations — goals by year, team goals, matches per tournament |
| `FIFA_WorldCup_DataIntelligence_Report.pptx` | 9-slide stakeholder presentation covering methodology, key statistics, goals analysis, team performance, statistical findings, and insights |
| `WorldCupMatches_1930-2014_Dataset.xlsx` | Source dataset used for all analysis |

---

## Workflow

The entire project was completed in 5 phases inside Claude AI:

```
1. Upload Data          →   WorldCupMatches.xlsx loaded directly into Claude
2. /explore-data        →   Profiled shape, dtypes, nulls, distributions
3. /build-dashboard     →   4-tab interactive dashboard rendered as live HTML
4. /create-viz          →   6 charts: bar, line, Poisson fit, era comparison, attendance, teams
5. /statistical-analysis →  4 hypothesis tests with p-values, regression, and correlation
```

**Zero code written manually.** Every step was prompted in plain English inside Claude AI.

---

## Key Findings

### Goals are Declining
- Average goals per match have fallen **45%** from the 1930–54 era (4.47) to today (2.47)
- Linear regression: slope = −0.027 goals/year, **r = −0.790, p = 0.0001**
- 1954 was the highest-scoring tournament ever at **5.38 goals/match**
- 1990 was the most defensive: **2.21 goals/match** (Italy won)

### Home Advantage is Structural
- Home win rate: **57.3%** vs Away win rate: **20.4%**
- Chi-square test: **χ² = 220.25, p < 0.0001**
- The null hypothesis of equal probability is rejected at every conventional significance level

### Bigger Crowds = Fewer Goals
- Higher attendance correlates with fewer goals: **r = −0.114, p = 0.0009**
- High-stakes knockout matches draw the largest crowds and produce the most cautious football

### Half-Time Predicts Full-Time
- Half-time goal total explains **48.7% of variance** in final scorelines
- Correlation: **r = 0.698, p < 0.0001**

### Team Dominance
| Team | All-Time Goals | Win Rate |
|------|---------------|----------|
| Brazil | 225 | 65.7% (108 matches) |
| Argentina | 133 | 54.3% |
| Germany FR | 131 | 58.1% |
| Germany | 104 | **70.8%** (highest win rate) |
| Italy | 128 | 54.2% |

### Record-Breaking Matches
- **Austria 7–5 Switzerland (1954)** — Most goals in a single match (12)
- **Uruguay vs Brazil, Maracanã (1950)** — Highest attendance ever: **173,850**

---

## Tools Used

- **Claude AI** — Agentic workflow, data analysis plugin, prompt engineering
- **Chart.js** — Interactive visualizations rendered in HTML
- **PowerPoint** — Executive presentation deck
- **Excel** — Source dataset

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Statistical Hypothesis Testing (Chi-square, Linear Regression, Correlation)
- Data Visualization (bar charts, trend lines, Poisson distribution)
- Dashboard Design and Development
- Stakeholder Presentation and Data Storytelling
- Agentic AI Workflow with Claude

---

## About

Built by **Puru Tiwari**
Data Analyst | Data Engineer & AI Enthusiast | Open to Work

Connect with me on [LinkedIn](https://www.linkedin.com/in/puru-tiwari-314aab135/)

---
