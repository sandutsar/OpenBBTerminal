---
title: sidtc
description: The sidtc page provides a command line interface to print short interest
  and days to cover for stocks. Provides options to limit the number of tickers displayed
  and sorting by specific fields.
keywords:
- sidtc
- short interest
- days to cover
- Stockgrid
- stock market
- financial data
- stock analysis
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="stocks/dps/sidtc - Reference | OpenBB Terminal Docs" />

Print short interest and days to cover. [Source: Stockgrid]

### Usage

```python
sidtc [-l LIMIT] [-s {float,dtc,si}]
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| limit | Limit of tickers to display. | 10 | True | None |
| sort_field | Field for which to sort by, where 'float': Float Short %%, 'dtc': Days to Cover, 'si': Short Interest | float | True | float, dtc, si |


---

## Examples

```python
2022 Feb 15, 11:07 (🦋) /stocks/dps/ $ sidtc
                      Data for: 2022-01-31
┌────────┬───────────────┬───────────────┬─────────────────────┐
│ Ticker │ Float Short % │ Days to Cover │ Short Interest [1M] │
├────────┼───────────────┼───────────────┼─────────────────────┤
│ VIEW   │ 40.70         │ 14.92         │ 21.46               │
├────────┼───────────────┼───────────────┼─────────────────────┤
│ HRTX   │ 34.06         │ 14.92         │ 34.64               │
├────────┼───────────────┼───────────────┼─────────────────────┤
│ IRBT   │ 24.47         │ 13.85         │ 6.47                │
├────────┼───────────────┼───────────────┼─────────────────────┤
│ ZYXI   │ 24.13         │ 14.43         │ 4.77                │
├────────┼───────────────┼───────────────┼─────────────────────┤
│ TDUP   │ 22.94         │ 14.14         │ 11.93               │
├────────┼───────────────┼───────────────┼─────────────────────┤
│ GOGO   │ 22.44         │ 25.02         │ 17.84               │
├────────┼───────────────┼───────────────┼─────────────────────┤
│ SATS   │ 19.49         │ 23.27         │ 7.14                │
├────────┼───────────────┼───────────────┼─────────────────────┤
│ RLAY   │ 19.32         │ 20.15         │ 14.88               │
├────────┼───────────────┼───────────────┼─────────────────────┤
│ OMER   │ 18.89         │ 13.36         │ 11.32               │
├────────┼───────────────┼───────────────┼─────────────────────┤
│ AXDX   │ 18.75         │ 19.71         │ 7.00                │
└────────┴───────────────┴───────────────┴─────────────────────┘
```
---
