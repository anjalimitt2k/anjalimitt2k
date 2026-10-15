# Anjali Mittapally

Data Science & Economics at UC Berkeley, graduating December 2026. Right now
I'm a Data/AI engineering intern at CrossGen AI, where I build forecasting
agents, RAG pipelines and the evaluation harnesses that decide whether any of
it is good enough to show a client.

I like problems where the answer is a measurement rather than an opinion, and
where there is an incumbent baseline that is genuinely hard to beat. Both of
the projects below are built around that: pick the strongest thing already in
production, score against it under the same rules, and publish the result
whether or not it flatters me.

## Projects

**[lure](https://github.com/anjalimitt2k/lure)** · Can an AI shopping agent be
talked into paying the wrong party? A benchmark with six injection attack
classes, five defenses, and a scripted agent plus a real one (Claude Haiku
5.5). The finding: a content classifier that scores 0.00 miss rate on the
injections it was trained on leaks to 0.08 to 0.17 when the same fraud goals
are rephrased, while outcome-level guardrails hold at zero. Everything
regenerates offline, byte-identically, with no API key. 329 tests.

**[caiso-day-ahead-forecast](https://github.com/anjalimitt2k/caiso-day-ahead-forecast)**
· A day-ahead load and price forecaster for the California grid, scored
against CAISO's own published forecast under walk-forward validation over 798
days. A GitHub Action issues tomorrow's forecast every morning before the
market clears and grades yesterday's, so the track record is live and
timestamped. I beat the naive baselines and a zero-shot foundation model; I do
not beat CAISO on load, and the README says so.
[Live scoreboard.](https://anjalimitt2k.github.io/caiso-day-ahead-forecast/)

This account is new. It holds the projects I've built since mid-2026; an
earlier streaming fraud-detection pipeline (Kafka, Spark Structured Streaming,
dbt, Airflow, Delta Lake) is on my resume and not yet migrated here.

## Tools I actually use

Python (pandas, scikit-learn, LightGBM), SQL, R (tidyverse), Claude API and
agent tooling, Kafka / Spark / dbt / Airflow, Git and GitHub Actions.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/anjalimittapally/) · anjali.mitt2k@gmail.com
