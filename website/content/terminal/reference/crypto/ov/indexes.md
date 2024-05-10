---
title: indexes
description: Our 'indexes' page offers data on crypto indexes coming from CoinGecko.
  It allows users to see details of each crypto index and offers several parameters
  for sorting and limiting the data displayed. Utilize cryptocurrency market data
  to make informed decisions regarding your crypto investments.
keywords:
- cryptocurrency
- CoinGecko
- crypto index
- market cap
- cryptocurrency market data
- crypto investment
- data sorting parameters
- limit parameter
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="crypto/ov/indexes - Reference | OpenBB Terminal Docs" />

Shows list of crypto indexes from CoinGecko. Each crypto index is made up of a selection of cryptocurrencies, grouped together and weighted by market cap. You can display only N number of indexes with --limit parameter. You can sort data by Rank, Name, Id, Market, Last, MultiAsset with --sortby and also with --reverse flag to sort descending. Displays: Rank, Name, Id, Market, Last, MultiAsset

### Usage

```python
indexes [-l LIMIT] [-s {Rank,Name,Id,Market,Last,MultiAsset}] [-r]
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| limit | display N number records | 15 | True | None |
| sortby | Sort by given column. Default: Rank | Rank | True | Rank, Name, Id, Market, Last, MultiAsset |
| reverse | Data is sorted in ascending order by default. Reverse flag will sort it in an descending way. Only works when raw data is displayed. | False | True | None |


---

## Examples

```python
2022 Feb 15, 08:13 (🦋) /crypto/ov/ $ indexes
                                       Crypto Indexes
┌──────┬─────────────────────────────┬────────┬───────────────────────┬───────┬────────────┐
│ Rank │ Name                        │ Id     │ Market                │ Last  │ MultiAsset │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 1    │ CoinFLEX (Futures) DFN      │ DFN    │ CoinFLEX (Futures)    │ nan   │ None       │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 2    │ Perpetual Protocol ZIL      │ ZIL    │ Perpetual Protocol    │ 0.11  │ None       │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 3    │ Bibox (Futures) LINK        │ LINK   │ Bibox (Futures)       │ 0.11  │ None       │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 4    │ CME Bitcoin Futures BTC     │ BTC    │ CME Group             │ 0.11  │ False      │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 5    │ Bibox (Futures) XRP         │ XRP    │ Bibox (Futures)       │ 0.11  │ None       │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 6    │ Bibox (Futures) AXS         │ AXS    │ Bibox (Futures)       │ 0.11  │ None       │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 7    │ ZBG Futures BSV             │ BSV    │ ZBG Futures           │ 0.11  │ None       │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 8    │ MEXC Global (Futures) ATLAS │ ATLAS  │ MEXC Global (Futures) │ 4.54  │ None       │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 9    │ CoinFLEX (Futures) BCHABC   │ BCHABC │ CoinFLEX (Futures)    │ 0.00  │ None       │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 10   │ Prime XBT USDC              │ USDC   │ Prime XBT             │ 0.00  │ None       │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 11   │ Poloniex Futures AXS        │ AXS    │ Poloniex Futures      │ 60.56 │ None       │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 12   │ Bibox (Futures) ETC         │ ETC    │ Bibox (Futures)       │ 60.56 │ None       │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 13   │ MyCoinStory SUN             │ SUN    │ MCS                   │ 13.41 │ None       │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 14   │ dYdX                        │ DYDX   │ FTX (Derivatives)     │ 7.57  │ None       │
├──────┼─────────────────────────────┼────────┼───────────────────────┼───────┼────────────┤
│ 15   │ Ronin                       │ RON    │ FTX (Derivatives)     │ 2.83  │ False      │
└──────┴─────────────────────────────┴────────┴───────────────────────┴───────┴────────────┘
```
---
