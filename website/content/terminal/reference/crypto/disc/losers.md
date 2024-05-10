---
title: losers
description: The 'losers' documentation page provides a Python based solution for
  identifying cryptocurrencies with the largest drop in value over a given time period.
  Control the analysis with options for the time interval, record limits, and sorting.
  This tool is essential for in-depth market analysis and monitoring market trends.
keywords:
- Market Analysis
- Cryptocurrency
- Crypto Losers
- Market Trends
- Price Drop
- Time Interval
- Record Limit
- Sort Options
- Python Script
- Crypto Coin Symbol
- Market Cap Rank
- Volume
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="crypto/disc/losers - Reference | OpenBB Terminal Docs" />

Shows Largest Losers - coins which price dropped the most in given period You can use parameter --interval to set which timeframe are you interested in: {14d,1h,1y,200d,24h,30d,7d} You can look on only N number of records with --limit, You can sort by {Symbol,Name,Price [$],Market Cap,Market Cap Rank,Volume [$]} with --sort.

### Usage

```python
losers [-i {14d,1h,1y,200d,24h,30d,7d}] [-l LIMIT] [-s SORTBY [SORTBY ...]]
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| interval | time period, one from {14d,1h,1y,200d,24h,30d,7d} | 1h | True | 14d, 1h, 1y, 200d, 24h, 30d, 7d |
| limit | Number of records to display | 15 | True | None |
| sortby | Sort by given column. Default: Market Cap Rank | Market Cap | True | Symbol, Name, Price [$], Market Cap, Market Cap Rank, Volume [$] |


---

## Examples

```python
2022 Feb 15, 06:43 (🦋) /crypto/disc/ $ losers
┌────────┬─────────────────┬───────────┬────────────────┬─────────────────┬────────────┬───────────────┐
│ Symbol │ Name            │ Price [$] │ Market Cap [$] │ Market Cap Rank │ Volume [$] │ Change 1h [%] │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ cro    │ Crypto.com Coin │ 0.50      │ 12.5B          │ 15              │ 200.8M     │ -1.21         │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ sol    │ Solana          │ 102.75    │ 32.7B          │ 8               │ 1.8B       │ -0.76         │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ doge   │ Dogecoin        │ 0.15      │ 19.9B          │ 12              │ 604.3M     │ -0.50         │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ AVAX   │ Avalanche       │ 88.66     │ 21.7B          │ 10              │ 899.9M     │ -0.38         │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ ada    │ Cardano         │ 1.09      │ 34.9B          │ 7               │ 1B         │ -0.31         │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ shib   │ Shiba Inu       │ 0.00      │ 17.2B          │ 14              │ 1.1B       │ -0.26         │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ eth    │ Ethereum        │ 3100.92   │ 370.6B         │ 2               │ 14.4B      │ -0.24         │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ dot    │ Polkadot        │ 19.79     │ 21.4B          │ 11              │ 672.9M     │ -0.12         │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ busd   │ Binance USD     │ 1.00      │ 17.6B          │ 13              │ 3B         │ -0.06         │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ bnb    │ Binance Coin    │ 429.57    │ 72.2B          │ 4               │ 1.8B       │ 0.05          │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ usdt   │ Tether          │ 1.00      │ 78.5B          │ 3               │ 43.3B      │ 0.08          │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ luna   │ Terra           │ 56.47     │ 22.4B          │ 9               │ 1B         │ 0.08          │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ btc    │ Bitcoin         │ 44275.00  │ 838.8B         │ 1               │ 20.6B      │ 0.11          │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ usdc   │ USD Coin        │ 1.00      │ 52.6B          │ 5               │ 3B         │ 0.12          │
├────────┼─────────────────┼───────────┼────────────────┼─────────────────┼────────────┼───────────────┤
│ xrp    │ XRP             │ 0.84      │ 39.9B          │ 6               │ 3.2B       │ 0.29          │
└────────┴─────────────────┴───────────┴────────────────┴─────────────────┴────────────┴───────────────┘
```
---