# C 3m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-172_793_rows-blue)](https://getdata.finance/datasets/c) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/c)

### -> [**Download the full C dataset on getdata.finance**](https://getdata.finance/datasets/c)

**C 3m OHLCV us stocks historical data** — ultra high-quality 3m OHLCV for **C**. US equity cash and extended sessions — institutional-style OHLCV candles for US stocks. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3m OHLCV** for **C** (US stocks)
- **US equity cash and extended sessions — institutional-style OHLCV candles for US stocks**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/c) · **172,793** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `C_3m.csv` (16,250 rows, `2026-02-02` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/c)** — **172,793** `1m` rows (~14.46 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2021-04-06` -> `2026-07-31`.

## Download sample

**[C_3m.csv](https://github.com/getdata-finance/c-3m-ohlcv-stocks-historical-data/blob/main/C_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/c-3m-ohlcv-stocks-historical-data/main/C_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/c-3m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/c-3m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/c-3m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/c](https://getdata.finance/datasets/c)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/c))** |
|---|--:|---|
| Instrument | C · US stocks | C · US stocks |
| Timeframes | `3m` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 16,250 | **172,793** |
| Size | 1.51 MB | ~14.46 MB |
| Period | `2026-02-02` -> `2026-07-31` | `2021-04-06` -> `2026-07-31` |
| File | `C_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/c) |
| Coverage report | — | [C coverage](https://getdata.finance/coverage/c) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/c)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/c) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`C_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-02T14:30:00+00:00 | 115.88 | 115.88 | 114.87 | 114.88 | 80 |
| 2026-02-02T14:33:00+00:00 | 114.88 | 116.07 | 114.87 | 115.85 | 521 |
| 2026-02-02T14:36:00+00:00 | 115.85 | 115.85 | 114.67 | 115.03 | 414 |
| 2026-02-02T14:39:00+00:00 | 115.03 | 115.52 | 115.02 | 115.32 | 374 |
| 2026-02-02T14:42:00+00:00 | 115.32 | 115.46 | 114.96 | 115.18 | 379 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T19:45:00+00:00 | 139.18 | 139.22 | 139.01 | 139.05 | 262 |
| 2026-07-31T19:48:00+00:00 | 139.05 | 139.28 | 139.01 | 139.19 | 301 |
| 2026-07-31T19:51:00+00:00 | 139.19 | 139.26 | 139.1 | 139.13 | 249 |
| 2026-07-31T19:54:00+00:00 | 139.13 | 139.16 | 138.71 | 138.74 | 382 |
| 2026-07-31T19:57:00+00:00 | 138.74 | 138.74 | 138.33 | 138.51 | 667 |

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

df = pd.read_csv('C_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('C_3m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('C_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **C** archive on **[getdata.finance](https://getdata.finance/datasets/c)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **172,793** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full C dataset on getdata.finance](https://getdata.finance/datasets/c)**

---
*GetData · C 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/c) · 2026-08-04 UTC*
