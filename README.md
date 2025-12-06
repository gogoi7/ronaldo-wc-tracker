# Ronaldo WC Tracker

## Project Goal
Predict which FIFA World Cup 2026 match gives me the best chance of seeing Cristiano Ronaldo in an exciting, high-stakes game (SUIIIIIIII 😀) – on a grad-student budget (cries in poor grad student money).

## The Problem
- I'm a CR7 fan based in Dallas with limited funds and way too much attachment to one man’s shot map.
- Portugal is in Group K with Colombia, Uzbekistan, and the winner of Inter-Confederation Playoff 1.
- I need to decide whether to buy a “safe” group-stage ticket or YOLO a knockout match.
- The decision needs to balance:
  - Probability Portugal advances
  - Probability Ronaldo actually plays and scores (SEWYYYYYY)
  - Match excitement level (later rounds, tougher opponents, higher stakes)
  - Cost and logistics from Dallas (cries in flight prices)

## Approach
- Use historical and current data on Portugal, opponents, and Ronaldo’s minutes/goals to estimate match-level probabilities.
- Run Monte Carlo simulations (thousands of alternate Ronaldo timelines) for the group and knockout stages.
- Define a “Ronaldo excitement per dollar” score for each potential match to recommend which games a broke Dallas fan should target.

## Skills I'm Learning
- Data collection and cleaning with pandas and APIs
- Probabilistic modeling and Monte Carlo simulations
- Basic forecasting and scenario analysis
- Data visualization of match odds, progression paths, and ticket “value”
- Git/GitHub workflow for a reproducible analysis
- SQL for organizing match, team, and player-level data

## Current Status
🚧 **In Progress** – Setting up project structure and data model, and identifying data sources for matches, teams, and player stats.

Next steps:
- Finalize schema for matches, teams, players, and simulations (SQL + pandas).
- Connect to data sources (FIFA and reputable football stats providers).
- Implement first-pass Monte Carlo for Group K and likely Portugal knockout routes.
- Build visualizations for:
  - Portugal’s probability of reaching each round
  - Expected Ronaldo minutes/goals by round
  - Recommended match choices for a Dallas-based fan with a limited budget

## Tools
- Python 3.13.x
- pandas, matplotlib, seaborn
- Jupyter notebooks
- SQL (e.g., SQLite or Postgres)