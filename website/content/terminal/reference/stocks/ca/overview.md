---
title: overview
description: This overview provides a snapshot of similar companies using the 'overview'
  command, including critical data such as stock price, market cap, P/E ratio, and
  more. Data sourced from Finviz.
keywords:
- stock screener
- finviz
- company data
- stock market
- financial data
- stock information
- company overview
- market cap
- PE ratio
- stock price
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="stocks/ca/overview - Reference | OpenBB Terminal Docs" />

Prints screener data of similar companies. [Source: Finviz]

### Usage

```python
overview
```

---

## Parameters

This command has no parameters



---

## Examples

```python
2022 Feb 15, 08:41 (🦋) /stocks/ca/ $ overview
                                                                          Stock Screener
┌────────┬───────────────────────┬────────────────────────┬────────────────────────────────┬─────────┬──────────────────┬────────┬─────────┬────────┬─────────────┐
│ Ticker │ Company               │ Sector                 │ Industry                       │ Country │ Market Cap       │ P/E    │ Price   │ Change │ Volume      │
├────────┼───────────────────────┼────────────────────────┼────────────────────────────────┼─────────┼──────────────────┼────────┼─────────┼────────┼─────────────┤
│ AAPL   │ Apple Inc.            │ Technology             │ Consumer Electronics           │ USA     │ 2812900000000.00 │ 28.04  │ 168.88  │ 0.00   │ 86185528.00 │
├────────┼───────────────────────┼────────────────────────┼────────────────────────────────┼─────────┼──────────────────┼────────┼─────────┼────────┼─────────────┤
│ GOOGL  │ Alphabet Inc.         │ Communication Services │ Internet Content & Information │ USA     │ 1849330000000.00 │ 24.15  │ 2710.52 │ 0.01   │ 1715054.00  │
├────────┼───────────────────────┼────────────────────────┼────────────────────────────────┼─────────┼──────────────────┼────────┼─────────┼────────┼─────────────┤
│ MSFT   │ Microsoft Corporation │ Technology             │ Software - Infrastructure      │ USA     │ 2266600000000.00 │ 31.39  │ 295.00  │ -0.00  │ 36359488.00 │
├────────┼───────────────────────┼────────────────────────┼────────────────────────────────┼─────────┼──────────────────┼────────┼─────────┼────────┼─────────────┤
│ TSLA   │ Tesla, Inc.           │ Consumer Cyclical      │ Auto Manufacturers             │ USA     │ 879490000000.00  │ 177.93 │ 875.76  │ 0.02   │ 22585472.00 │
└────────┴───────────────────────┴────────────────────────┴────────────────────────────────┴─────────┴──────────────────┴────────┴─────────┴────────┴─────────────┘
```
---
