
# FIFA World Cup Data Analysis (1930–2014)
> 84 years · 852 matches · 3 key patterns uncovered using Python + Claude AI

---

## What this project is
A full exploratory data analysis of every FIFA World Cup match from 1930 to 2014. I used Python to clean and process the data, Claude AI to surface patterns and generate narrative insights, and built two interactive visualisations and a presentation summarising the findings.

---

## Key findings
### 1. Football has become dramatically more defensive
Goals per game has nearly halved over 84 years. The 1950s averaged over 5 goals per match — today it's under 2.5. Tactical evolution, not coincidence.
### 2. Home advantage is real — but only in group stages
Teams playing on home soil won 36% more often overall. But in knockout rounds, that gap almost entirely disappears. Pressure neutralises familiarity.
### 3. Brazil leads goals scored, Germany leads under pressure
Brazil tops the all-time goals table across all World Cups. But Germany has the highest goals-per-match ratio specifically in knockout stages — the rounds that decide champions.

---

## Project structure

fifa-worldcup-analysis/
│
├── data/
│   └── worldcups_matches.csv       # Raw dataset (1930–2014, 852 matches)
│
├── notebooks/
│   └── analysis.ipynb              # Full EDA notebook
│
├── charts/
│   ├── goals_per_game_trend.png    # Goals per game over time (line chart)
│   └── top_scoring_teams.png       # All-time top scoring teams (bar chart)
│
├── presentation/
│   └── FIFA_Analysis_Report.pptx  # Full slide deck
│
├── analyze.py                      # Main analysis script
└── README.md

## Tools used
### | Tool | Purpose |

| Python 3.11 | Data cleaning, processing, analysis |
| Pandas | Data manipulation and aggregation |
| Matplotlib / Seaborn | Chart generation |
| Claude AI (Anthropic) | Pattern recognition, narrative insight generation |
| PowerPoint (pptxgenjs) | Automated presentation build |

---

## Dataset

- **Source:** [FIFA World Cup Dataset — GitHub] https://github.com/rohanmistry231/Practice-Datasets-for-Excel/blob/main/FIFA%20World%20Cup/WorldCupPlayers.xlsx
- **Coverage:** All 852 World Cup matches, 1930–2014
- **Fields:** Match date, teams, scores, stage, venue, attendance, referee

---

## What I learned

- How to clean and reshape messy historical sports data with Pandas
- How to use Claude AI as an analysis co-pilot — feeding it summaries and getting structured business-style insights back
- How to automate a full reporting pipeline from raw CSV to a presentation-ready slide deck
- That football analytics is genuinely fascinating — the defensive shift post-1960s is one of the clearest long-term trends in any sport

---

## Author

**[Puru Tiwari]**
Aspiring Data Engineer | Learning in public
Connect with me on [LinkedIn](www.linkedin.com/in/puru-tiwari-314aab135)

---
