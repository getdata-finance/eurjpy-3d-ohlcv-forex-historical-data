# EURJPY 3d OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-6_723_rows-blue)](https://getdata.finance/datasets/eurjpy) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurjpy)

### -> [**Download the full EURJPY dataset on getdata.finance**](https://getdata.finance/datasets/eurjpy)

**EURJPY 3d OHLCV forex historical data** — ultra high-quality 3d OHLCV for **EURJPY**. 24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3d OHLCV** for **EURJPY** (Forex)
- **24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurjpy) · **6,723** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `EURJPY_3d.csv` (76 rows, `2026-04-17` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/eurjpy)** — **6,723** `1m` rows (~1.18 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `1971-01-02` -> `2026-07-30`.

## Download sample

**[EURJPY_3d.csv](https://github.com/getdata-finance/eurjpy-3d-ohlcv-forex-historical-data/blob/main/EURJPY_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eurjpy-3d-ohlcv-forex-historical-data/main/EURJPY_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/eurjpy-3d-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eurjpy-3d-ohlcv-forex-historical-data/](https://getdata-finance.github.io/eurjpy-3d-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eurjpy](https://getdata.finance/datasets/eurjpy)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eurjpy))** |
|---|--:|---|
| Instrument | EURJPY · Forex | EURJPY · Forex |
| Timeframes | `3d` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 76 | **6,723** |
| Size | 0.01 MB | ~1.18 MB |
| Period | `2026-04-17` -> `2026-07-31` | `1971-01-02` -> `2026-07-30` |
| File | `EURJPY_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eurjpy) |
| Coverage report | — | [EURJPY coverage](https://getdata.finance/coverage/eurjpy) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eurjpy)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/eurjpy) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EURJPY_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-04-17T00:00:00+00:00 | 207.411 | 207.94 | 206.303 | 206.551 | 476214 |
| 2026-04-20T00:00:00+00:00 | 206.551 | 207.5 | 206.44 | 207.376 | 395702 |
| 2026-04-21T00:00:00+00:00 | 207.376 | 207.573 | 207.199 | 207.29 | 378857 |
| 2026-04-22T00:00:00+00:00 | 207.29 | 207.534 | 206.835 | 206.835 | 361235 |
| 2026-04-23T00:00:00+00:00 | 206.835 | 207.173 | 206.641 | 206.756 | 881568 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-27T00:00:00+00:00 | 208.287 | 208.674 | 208.043 | 208.046 | 359853 |
| 2026-07-28T00:00:00+00:00 | 208.046 | 208.622 | 207.977 | 208.472 | 368966 |
| 2026-07-29T00:00:00+00:00 | 208.472 | 209.409 | 208.119 | 209.263 | 468118 |
| 2026-07-30T00:00:00+00:00 | 209.263 | 209.372 | 204.036 | 205.815 | 678611 |
| 2026-07-31T00:00:00+00:00 | 205.815 | 207.099 | 205.675 | 206.692 | 242319 |

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

df = pd.read_csv('EURJPY_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EURJPY_3d.csv', parse_dates=['datetime'])
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

df = pd.read_csv('EURJPY_3d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **EURJPY** archive on **[getdata.finance](https://getdata.finance/datasets/eurjpy)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **6,723** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full EURJPY dataset on getdata.finance](https://getdata.finance/datasets/eurjpy)**

---
*GetData · EURJPY 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eurjpy) · 2026-08-05 UTC*
