---
title: ath
description: This documentation is about the All Time High (ATH) function for a crypto
  coin or token. A user can load coin data and see the highest price (in USD or BTC)
  that coin has ever reached.
keywords:
- all time high
- crypto coin
- load coin data
- highest price
- price in USD
- price in BTC
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="crypto/dd/ath - Reference | OpenBB Terminal Docs" />

All time high data for loaded coin

### Usage

```python
ath [--vs {usd,btc}]
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| vs | currency | usd | True | usd, btc |


---

## Examples

```python
2022 Feb 15, 07:04 (🦋) /crypto/dd/ $ ath
                            Coin Highs
┌─────────────────────────────────────┬──────────────────────────┐
│ Metric                              │ Value                    │
├─────────────────────────────────────┼──────────────────────────┤
│ Current Price USD                   │ 44302                    │
├─────────────────────────────────────┼──────────────────────────┤
│ All Time High USD                   │ 69045                    │
├─────────────────────────────────────┼──────────────────────────┤
│ All Time High Date USD              │ 2021-11-10T14:24:11.849Z │
├─────────────────────────────────────┼──────────────────────────┤
│ All Time High Change Percentage USD │ -35.75                   │
└─────────────────────────────────────┴──────────────────────────┘
```
---
