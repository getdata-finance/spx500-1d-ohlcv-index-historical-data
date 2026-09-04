# SPX500 1d OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-5_466_rows-blue)](https://getdata.finance/datasets/spx500) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/spx500)

### -> [**Download the full SPX500 dataset on getdata.finance**](https://getdata.finance/datasets/spx500)

**SPX500 1d OHLCV index historical data** — ultra high-quality 1d OHLCV for **S&P 500**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1d OHLCV** for **S&P 500** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/spx500) · **5,466** `1d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1d` sample updated in sync

> **Sample on GitHub** · `SPX500_1d.csv` (732 rows, `2024-04-26` -> `2026-09-02`, 54.88 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/spx500)** — **5,466** `1d` rows (full `1m`: 5,815,518), **11 timeframes**, `2009-01-02` -> `2026-09-02`.

## Download sample

**[SPX500_1d.csv](https://github.com/getdata-finance/spx500-1d-ohlcv-index-historical-data/blob/main/SPX500_1d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/spx500-1d-ohlcv-index-historical-data/main/SPX500_1d.csv)) · [GitHub Releases](https://github.com/getdata-finance/spx500-1d-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/spx500-1d-ohlcv-index-historical-data/](https://getdata-finance.github.io/spx500-1d-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/spx500](https://getdata.finance/datasets/spx500)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/spx500))** |
|---|--:|---|
| Instrument | S&P 500 · Index | S&P 500 · Index |
| Timeframes | `1d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1d rows | 732 | **5,466** |
| Size | 54.88 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/spx500) |
| Period | `2024-04-26` -> `2026-09-02` | `2009-01-02` -> `2026-09-02` |
| File | `SPX500_1d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/spx500) |
| Coverage report | — | [SPX500 coverage](https://getdata.finance/coverage/spx500) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/spx500)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1d` sample · [getdata.finance](https://getdata.finance/datasets/spx500) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`SPX500_1d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-04-26T00:00:00+00:00 | 5090.62 | 5117.69 | 5075.92 | 5102.73 | 102240 |
| 2024-04-28T00:00:00+00:00 | 5102.73 | 5114.4 | 5102.73 | 5114.38 | 2632 |
| 2024-04-29T00:00:00+00:00 | 5114.38 | 5126.95 | 5091.43 | 5118.26 | 64724 |
| 2024-04-30T00:00:00+00:00 | 5118.26 | 5118.28 | 5023.23 | 5031.86 | 104621 |
| 2024-05-01T00:00:00+00:00 | 5031.86 | 5100.42 | 5011.86 | 5041.39 | 180920 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-28T00:00:00+00:00 | 7718.86 | 7772.43 | 7701.91 | 7713.36 | 318486 |
| 2026-08-30T00:00:00+00:00 | 7713.36 | 7715.62 | 7680.11 | 7680.35 | 15427 |
| 2026-08-31T00:00:00+00:00 | 7680.35 | 7707.62 | 7666.65 | 7695.51 | 212524 |
| 2026-09-01T00:00:00+00:00 | 7695.51 | 7700.02 | 7613.55 | 7638.97 | 233364 |
| 2026-09-02T00:00:00+00:00 | 7638.97 | 7643.84 | 7625.34 | 7629.85 | 16051 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('SPX500_1d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('SPX500_1d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('SPX500_1d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1d')
print(pf.stats())
```

## Download full data

The complete **SPX500** archive on **[getdata.finance](https://getdata.finance/datasets/spx500)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **5,466** rows at `1d`, plus all other timeframes in the same ZIP.

**[-> Get the full SPX500 dataset on getdata.finance](https://getdata.finance/datasets/spx500)**

---
*GetData · SPX500 1d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/spx500)*
