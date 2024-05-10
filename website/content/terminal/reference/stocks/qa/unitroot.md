---
title: unitroot
description: This documentation page provides a detailed guide on how to use 'unitroot',
  a python function for executing unit root tests including ADF and KPSS. It includes
  parameters details, their choices, and usage examples.
keywords:
- unitroot
- ADF
- KPSS
- stationarity
- root test
- fuller_reg
- kpss_reg
- regression
- stock
- statistics
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="stocks/qa/unitroot - Reference | OpenBB Terminal Docs" />

Unit root test / stationarity (ADF, KPSS)

### Usage

```python
unitroot [-r {c,ct,ctt,nc}] [-k {c,ct}]
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| fuller_reg | Type of regression. Can be ‘c’,’ct’,’ctt’,’nc’ 'c' - Constant and t - trend order | c | True | c, ct, ctt, nc |
| kpss_reg | Type of regression. Can be ‘c’,’ct' | c | True | c, ct |


---

## Examples

```python
2022 Feb 16, 11:16 (🦋) /stocks/qa/ $ unitroot
         Unit Root Calculation
┏━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━┳━━━━━━━━┓
┃                ┃ ADF        ┃ KPSS   ┃
┡━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━╇━━━━━━━━┩
│ Test Statistic │ -28.9536   │ 0.2928 │
├────────────────┼────────────┼────────┤
│ P-Value        │ 0.0000     │ 0.1000 │
├────────────────┼────────────┼────────┤
│ NLags          │ 0.0000     │ 3      │
├────────────────┼────────────┼────────┤
│ Nobs           │ 759.0000   │        │
├────────────────┼────────────┼────────┤
│ ICBest         │ -3339.2013 │        │
└────────────────┴────────────┴────────┘
```
---
