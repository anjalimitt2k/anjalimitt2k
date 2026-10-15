# hi, I'm Anjali

I'm a senior at Berkeley studying data science and econ (done in December 2026).

## what's here

**[lure](https://github.com/anjalimitt2k/lure)** — AI agents are starting to be able to spend people's money, and to buy anything they have to read the product page, which the seller controls. I wanted to know if you can hide instructions in a product page and trick the agent into paying the wrong person. So I built a fake marketplace, six kinds of attacks, a few defenses, and ran both a scripted agent and Claude Haiku through it. What I found: a text filter that catches 100% of the scams it was trained on misses 8–17% of them once you just reword the same scam. A simpler defense that never reads the page, and instead checks "does this payment match what the user actually asked for," didn't miss any. Basically, don't trust a filter to spot the trick, check the outcome instead. Everything reruns offline with no API key. Lots of tests (329, I counted).

**[caiso-day-ahead-forecast](https://github.com/anjalimitt2k/caiso-day-ahead-forecast)** — day-ahead electricity load and price forecasting for the California grid, scored against CAISO's own forecast, not a naive baseline. A GitHub Action wakes up every morning, posts tomorrow's forecast before the market clears, and grades yesterday's. I beat the naive stuff and a zero-shot foundation model. I do not beat CAISO on load, and I decided that was worth publishing anyway. [Live scoreboard](https://anjalimitt2k.github.io/caiso-day-ahead-forecast/)

This account is pretty new, it's for just what I've built since summer 2026 to build up my skills :)

## stuff I use

Python (pandas, scikit-learn, LightGBM), SQL, a bit of R, the Claude API, Kafka/Spark/dbt/Airflow, GitHub Actions for anything that should run without me.

## find me

[LinkedIn](https://www.linkedin.com/in/anjalimittapally/) · anjali.mitt2k@gmail.com
