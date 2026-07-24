# Apple Stock Analysis 🍎📈

Exploratory data analysis of Apple Inc. (AAPL) historical stock price data, built in a Jupyter Notebook with Pandas, Matplotlib, and Seaborn.

## Steps performed

1. **Load & clean data** — read CSV into a DataFrame, parse `Date` column (`pd.to_datetime`, UTC/timezone handling), sort chronologically.
2. **Feature extraction** — derive `Year` and `Month` columns from `Date` for grouping.
3. **Closing Price Trend Over Time** — line chart of `Close` price across the full date range.
4. **Average Closing Price by Month** — group by `Month`, ordered Jan–Dec, plotted as a bar chart (`coolwarm` palette).
5. **Apple Daily Price Range (High vs Low)** — filled area chart between `Low` and `High`, with `Close` overlaid.
6. **Average Closing Price per Year** — yearly grouped bar chart (`viridis` palette).
7. **Distribution of Daily Closing Prices** — histogram + KDE of `Close` values.
8. **Daily Percentage Change in Closing Price** — `pct_change()` on `Close` plotted over time, with a zero reference line.

## Screenshots

Chart outputs saved in [`screenshots/`](screenshots/).

## Tech stack

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Viewing the analysis

Open `Apple_stocks.html` in a browser — full notebook with code cells, charts, and output.

## Notes

Raw CSV dataset not included in repo. To reproduce, supply your own AAPL historical price CSV with `Date, Open, High, Low, Close, Volume` columns and point `pd.read_csv(...)` at it.
