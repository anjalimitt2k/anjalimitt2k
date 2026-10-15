# hi, I'm Anjali

I'm a senior at Berkeley studying data science and econ (done in December 2026). This past summer I interned at CrossGen AI, a small applied AI studio, mostly building forecasting agents and eval harnesses and then arguing with the numbers until they made sense.

I got kind of obsessed with the idea of benchmarking stuff against a baseline that's actually hard to beat, instead of against a strawman. Both projects on here came out of that.

## what's here

**[lure](https://github.com/anjalimitt2k/lure)** — I wanted to know if you can trick an AI shopping agent into paying the wrong person by hiding instructions in a product page. So I built a fake marketplace, six kinds of attacks, a few defenses, and ran both a scripted agent and Claude Haiku through it. The part I found interesting: a text classifier that catches 100% of the injections it trained on misses 8–17% of them once you just reword the same scam. Guardrails that check the actual payment instead of reading the page didn't miss any. Everything reruns offline with no API key. Lots of tests (329, I counted).

**[caiso-day-ahead-forecast](https://github.com/anjalimitt2k/caiso-day-ahead-forecast)** — day-ahead electricity load and price forecasting for the California grid, scored against CAISO's own forecast, not a naive baseline. A GitHub Action wakes up every morning, posts tomorrow's forecast before the market clears, and grades yesterday's. I beat the naive stuff and a zero-shot foundation model. I do not beat CAISO on load, and I decided that was worth publishing anyway. [Live scoreboard](https://anjalimitt2k.github.io/caiso-day-ahead-forecast/)

This account is pretty new, it's just what I've built since summer 2026. There's an older streaming fraud-detection project (Kafka / Spark / dbt / Airflow) that's on my resume but not up here yet.

## stuff I use

Python (pandas, scikit-learn, LightGBM), SQL, a bit of R, the Claude API, Kafka/Spark/dbt/Airflow, GitHub Actions for anything that should run without me.

## find me

[LinkedIn](https://www.linkedin.com/in/anjalimittapally/) · anjali.mitt2k@gmail.com
