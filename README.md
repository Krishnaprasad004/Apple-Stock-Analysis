# Apple Stock Analysis 🍎📈

Exploratory data analysis of Apple Inc. (AAPL) historical stock price data using Python, Pandas, Matplotlib, and Seaborn.

## What's inside

The analysis (`Apple_stocks.html` — exported Jupyter Notebook) covers:

- **Data cleaning** — parsing dates, timezone handling, sorting by date
- **Closing price trend** — line chart of AAPL close price over time
- **Monthly average close price** — bar chart grouped by calendar month
- **Yearly average close price** — bar chart grouped by year
- **High/low price range** — filled area chart over time
- **Price distribution** — histogram with KDE of closing prices
- **Daily returns** — percentage change in close price over time

## Screenshots

Chart outputs are available in [`screenshots/`](screenshots/).

## Tech stack

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Viewing the analysis

Open `Apple_stocks.html` directly in a browser to view the full notebook with code, charts, and output.

## Notes

The raw CSV dataset used in the notebook isn't included in this repo. To reproduce the analysis, supply your own AAPL historical price CSV (date, open, high, low, close, volume columns) and adjust the `pd.read_csv(...)` path in the notebook.
