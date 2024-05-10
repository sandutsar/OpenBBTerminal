---
title: global
description: An overview of global statistics on the Crypto Market, providing essential
  information such as active cryptocurrencies, ICOs data, and market cap changes.
  Features a pie chart option for visualizing market cap distribution. Powered by
  CoinGecko.
keywords:
- Global Cryptocurrency
- Crypto Market Statistics
- Cryptocurrency Analysis
- ICOs Data
- Pie Chart Market Cap
- CoinGecko
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="crypto/ov/global - Reference | OpenBB Terminal Docs" />

Shows global statistics about Crypto Market

### Usage

```python
global [--pie]
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| pie | Flag to show pie chart with market cap distribution. Works only with CoinGecko source | False | True | None |


---

## Examples

```python
2022 Feb 15, 08:13 (🦋) /crypto/ov/ $ global
                 Global Statistics
┌──────────────────────────────────────┬──────────┐
│ Metric                               │ Value    │
├──────────────────────────────────────┼──────────┤
│ Active Cryptocurrencies              │ 12589.00 │
├──────────────────────────────────────┼──────────┤
│ Upcoming Icos                        │ 0.00     │
├──────────────────────────────────────┼──────────┤
│ Ongoing Icos                         │ 49.00    │
├──────────────────────────────────────┼──────────┤
│ Ended Icos                           │ 3376.00  │
├──────────────────────────────────────┼──────────┤
│ Markets                              │ 741.00   │
├──────────────────────────────────────┼──────────┤
│ Market Cap Change Percentage 24H Usd │ 5.08     │
├──────────────────────────────────────┼──────────┤
│ Btc Market Cap In Pct                │ 40.46    │
├──────────────────────────────────────┼──────────┤
│ Eth Market Cap In Pct                │ 17.95    │
├──────────────────────────────────────┼──────────┤
│ Altcoin Market Cap In Pct            │ 41.59    │
└──────────────────────────────────────┴──────────┘
```
---
