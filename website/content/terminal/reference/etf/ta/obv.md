---
title: obv
description: On Balance Volume (OBV) is a crucial aspect in volume analysis and technical
  trading. This page gives an in-depth explanation on OBV describing its impact, its
  interpretation, and usage in predicting price moves and market trends.
keywords:
- On Balance Volume
- OBV
- Volume Analysis
- Technical Analysis
- Market Trend
- Price Move
- Financial Trading
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="etf/ta/obv - Reference | OpenBB Terminal Docs" />

The On Balance Volume (OBV) is a cumulative total of the up and down volume. When the close is higher than the previous close, the volume is added to the running total, and when the close is lower than the previous close, the volume is subtracted from the running total. To interpret the OBV, look for the OBV to move with the price or precede price moves. If the price moves before the OBV, then it is a non-confirmed move. A series of rising peaks, or falling troughs, in the OBV indicates a strong trend. If the OBV is flat, then the market is not trending.

### Usage

```python
obv
```

---

## Parameters

This command has no parameters


![obv](https://user-images.githubusercontent.com/46355364/154311359-edb78587-744f-4e2c-b247-8b9fbf09b01f.png)

---
