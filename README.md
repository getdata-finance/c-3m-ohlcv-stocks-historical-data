# C 3m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-176_173_rows-blue)](https://getdata.finance/datasets/c) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/c)

### -> [**Download the full C dataset on getdata.finance**](https://getdata.finance/datasets/c)

**C 3m OHLCV stocks historical data** — ultra high-quality 3m OHLCV for **Citigroup**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3m OHLCV** for **Citigroup** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/c) · **176,173** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `C_3m.csv` (16,279 rows, `2026-03-10` -> `2026-09-08`, 1.56 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/c)** — **176,173** `3m` rows (full `1m`: 526,299), **11 timeframes**, `2021-04-06` -> `2026-09-08`.

## Download sample

**[C_3m.csv](https://github.com/getdata-finance/c-3m-ohlcv-stocks-historical-data/blob/main/C_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/c-3m-ohlcv-stocks-historical-data/main/C_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/c-3m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/c-3m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/c-3m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/c](https://getdata.finance/datasets/c)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/c))** |
|---|--:|---|
| Instrument | Citigroup · US stocks | Citigroup · US stocks |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 16,279 | **176,173** |
| Size | 1.56 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/c) |
| Period | `2026-03-10` -> `2026-09-08` | `2021-04-06` -> `2026-09-08` |
| File | `C_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/c) |
| Coverage report | — | [C coverage](https://getdata.finance/coverage/c) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/c)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/c) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`C_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-10T18:33:00+00:00 | 115.56 | 115.58 | 114.92 | 115 | 366 |
| 2026-03-10T18:36:00+00:00 | 115 | 115.4 | 114.95 | 115.18 | 404 |
| 2026-03-10T18:39:00+00:00 | 115.18 | 115.26 | 114.9 | 115.02 | 299 |
| 2026-03-10T18:42:00+00:00 | 115.02 | 115.19 | 114.96 | 114.96 | 298 |
| 2026-03-10T18:45:00+00:00 | 114.96 | 115.27 | 114.94 | 115.15 | 337 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-08T19:45:00+00:00 | 136.99 | 137.05 | 136.95 | 137.03 | 105 |
| 2026-09-08T19:48:00+00:00 | 137.03 | 137.05 | 136.66 | 136.68 | 175 |
| 2026-09-08T19:51:00+00:00 | 136.68 | 136.79 | 136.6 | 136.66 | 176 |
| 2026-09-08T19:54:00+00:00 | 136.66 | 136.67 | 136.49 | 136.54 | 211 |
| 2026-09-08T19:57:00+00:00 | 136.54 | 136.67 | 136.4 | 136.65 | 364 |

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
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **C** archive on **[getdata.finance](https://getdata.finance/datasets/c)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **176,173** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full C dataset on getdata.finance](https://getdata.finance/datasets/c)**

---
*GetData · C 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/c)*
