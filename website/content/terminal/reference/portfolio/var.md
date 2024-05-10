---
title: var
description: Learn how to calculate the Value at Risk (VaR) of your portfolio using
  different parameters and statistical methods. This guide provides examples and an
  explanation of all the options.
keywords:
- Value at Risk
- VaR
- portfolio
- portfolio return
- Cornish-Fisher-Expansion
- student-t distribution
- percentile
- VaR calculations
- Historical VaR
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="portfolio/var - Reference | OpenBB Terminal Docs" />

Provides value at risk (short: VaR) of the selected portfolio.

### Usage

```python
var [-m] [-a] [-s] [-p PERCENTILE]
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| use_mean | If one should use the mean of the portfolio return | True | True | None |
| adjusted | If the VaR should be adjusted for skew and kurtosis (Cornish-Fisher-Expansion) | False | True | None |
| student_t | If one should use the student-t distribution | False | True | None |
| percentile | Percentile used for VaR calculations, for example input 99.9 equals a 99.9 Percent VaR | 99.9 | True | None |


---

## Examples

```python
2022 Feb 25, 03:09 (🦋) /portfolio/ $ var
       Portfolio Value at Risk
┏━━━━━━━┳━━━━━━━━━┳━━━━━━━━━━━━━━━━━┓
┃       ┃ VaR:    ┃ Historical VaR: ┃
┡━━━━━━━╇━━━━━━━━━╇━━━━━━━━━━━━━━━━━┩
│ 90.0% │ -0.0148 │ -0.0135         │
├───────┼─────────┼─────────────────┤
│ 95.0% │ -0.0189 │ -0.0197         │
├───────┼─────────┼─────────────────┤
│ 99.0% │ -0.0267 │ -0.0258         │
├───────┼─────────┼─────────────────┤
│ 99.9% │ -0.0353 │ -0.0276         │
└───────┴─────────┴─────────────────┘
```
---
