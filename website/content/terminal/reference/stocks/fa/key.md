---
title: key
description: This documentation provides users with key metrics data about a company
  using Alpha Vantage API. It presents data fields like Market capitalization, EBITDA,
  EPS, PE ratio, and more.
keywords:
- Alpha Vantage API
- Market capitalization
- EBITDA
- EPS
- PE ratio
- PEG ratio
- Price to book ratio
- Return on equity TTM
- Payout ratio
- Price to sales ratio TTM
- Dividend yield
- 50 day moving average
- Analyst target price
- Beta
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="stocks/fa/key - Reference | OpenBB Terminal Docs" />

Gives main key metrics about the company (it's a subset of the Overview data from Alpha Vantage API). The following fields are expected: Market capitalization, EBITDA, EPS, PE ratio, PEG ratio, Price to book ratio, Return on equity TTM, Payout ratio, Price to sales ratio TTM, Dividend yield, 50 day moving average, Analyst target price, Beta [Source: Alpha Vantage API]

### Usage

```python
key
```

---

## Parameters

This command has no parameters



---

## Examples

```python
2022 Feb 16, 06:54 (🦋) /stocks/fa/ $ key
            AAPL Key Metrics
┏━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━┓
┃                          ┃           ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━┩
│ Market capitalization    │ 2.820 T   │
├──────────────────────────┼───────────┤
│ EBITDA                   │ 128.218 B │
├──────────────────────────┼───────────┤
│ EPS                      │ 6.01      │
├──────────────────────────┼───────────┤
│ PE ratio                 │ 28.73     │
├──────────────────────────┼───────────┤
│ PEG ratio                │ 3.28      │
├──────────────────────────┼───────────┤
│ Price to book ratio      │ 38.31     │
├──────────────────────────┼───────────┤
│ Return on equity TTM     │ 1.456     │
├──────────────────────────┼───────────┤
│ Price to sales ratio TTM │ 7.45      │
├──────────────────────────┼───────────┤
│ Dividend yield           │ 0.0052    │
├──────────────────────────┼───────────┤
│ 50 day moving average    │ 172.3     │
├──────────────────────────┼───────────┤
│ Analyst target price     │ 192.52    │
├──────────────────────────┼───────────┤
│ Beta                     │ 1.188     │
└──────────────────────────┴───────────┘
```
---
