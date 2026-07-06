# US2000 1m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_686_846_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full US2000 dataset on ork.ad**](https://ork.ad/)

**US2000 1m OHLCV Stock index historical data** — ultra high-quality 1m OHLCV for **Russell 2000**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Russell 2000** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **2,686,846** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `US2000_1m.csv` (177,313 rows, `2026-01-04` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **2,686,846** `1m` rows (~140.65 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2018-10-26` → `2026-07-03`.

## Download sample

**[US2000_1m.csv](https://github.com/ork-ad/us2000-1m-ohlcv-index-historical-data/blob/main/US2000_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/us2000-1m-ohlcv-index-historical-data/main/US2000_1m.csv)) · [GitHub Releases](https://github.com/ork-ad/us2000-1m-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/us2000-1m-ohlcv-index-historical-data/](https://ork-ad.github.io/us2000-1m-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Russell 2000 · Stock index | Russell 2000 · Stock index |
| Timeframes | `1m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1m rows | 177,313 | **2,686,846** |
| Size | 9.4 MB | ~140.65 MB |
| Period | `2026-01-04` → `2026-07-03` | `2018-10-26` → `2026-07-03` |
| File | `US2000_1m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`1m` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`US2000_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-01-04T23:00:00Z | 2508.4 | 2513.48 | 2508.4 | 2511.19 | 294 |
| 2026-01-04T23:01:00Z | 2511.19 | 2512.74 | 2509.58 | 2511.59 | 118 |
| 2026-01-04T23:02:00Z | 2511.59 | 2512.7 | 2511.58 | 2512.69 | 57 |
| 2026-01-04T23:03:00Z | 2512.69 | 2513.1 | 2512.7 | 2512.9 | 36 |
| 2026-01-04T23:04:00Z | 2512.9 | 2512.9 | 2511.38 | 2511.84 | 101 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-03T16:55:00Z | 3005.9 | 3006.2 | 3005.8 | 3006.11 | 31 |
| 2026-07-03T16:56:00Z | 3006.11 | 3006.72 | 3006.1 | 3006.7 | 29 |
| 2026-07-03T16:57:00Z | 3006.7 | 3006.72 | 3006.55 | 3006.61 | 34 |
| 2026-07-03T16:58:00Z | 3006.61 | 3006.72 | 3006.47 | 3006.65 | 29 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('US2000_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('US2000_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('US2000_1m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **US2000** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **2,686,846** rows at `1m`, plus all other timeframes in the same ZIP.

**[→ Get the full US2000 dataset on ork.ad](https://ork.ad/)**

---
*GetData · US2000 1m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*