---
title: es
description: Documentation page for using the Expected Shortfall (ES) function in
  Python. Provides detailed examples, parameter usage, and options for calculations.
keywords:
- Expected Shortfall
- stock
- distribution
- percentile
- ES
- calculations
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="stocks/qa/es - Reference | OpenBB Terminal Docs" />

Provides Expected Shortfall (short: ES) of the selected stock.

### Usage

```python
es [-m] [-d {laplace,student_t,logistic,normal}] [-p PERCENTILE]
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| use_mean | If one should use the mean of the stocks return | False | True | None |
| distributions | Distribution used for the calculations | normal | True | laplace, student_t, logistic, normal |
| percentile | Percentile for calculations, i.e. input 99.9 equals a 99.9 Percent Expected Shortfall | 99.9 | True | None |


---

## Examples

```python
2022 Feb 25, 06:50 (🦋) /stocks/qa/ $ es
      TSLA Expected Shortfall
┏━━━━━━━┳━━━━━━━━━┳━━━━━━━━━━━━━━━━┓
┃       ┃ ES:     ┃ Historical ES: ┃
┡━━━━━━━╇━━━━━━━━━╇━━━━━━━━━━━━━━━━┩
│ 90.0% │ -0.0752 │ -0.0705        │
├───────┼─────────┼────────────────┤
│ 95.0% │ -0.0885 │ -0.0932        │
├───────┼─────────┼────────────────┤
│ 99.0% │ -0.1144 │ -0.1561        │
├───────┼─────────┼────────────────┤
│ 99.9% │ -0.1444 │ -0.2106        │
└───────┴─────────┴────────────────┘
```
---
