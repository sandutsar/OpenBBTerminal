---
title: normality
description: The page provides comprehensive instructions on how to use the 'normality'
  function in stock market data analysis. It offers examples of how the function can
  be used to calculate different statistics, including Kurtosis, Skewness, Jarque-Bera,
  Shapiro-Wilk, and Kolmogorov-Smirnov, thereby assisting in deciding whether the
  data has a Gaussian distribution.
keywords:
- normality tests
- stock market
- statistics
- Kurtosis
- Skewness
- Jarque-Bera
- Shapiro-Wilk
- Kolmogorov-Smirnov
- data analysis
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="crypto/qa/normality - Reference | OpenBB Terminal Docs" />

Normality tests

### Usage

```python
normality
```

---

## Parameters

This command has no parameters



---

## Examples

```python
2022 Feb 16, 11:11 (🦋) /stocks/qa/ $ normality
            Normality Statistics
┏━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━┳━━━━━━━━━┓
┃                    ┃ Statistic ┃ p-value ┃
┡━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━╇━━━━━━━━━┩
│ Kurtosis           │ 10.2422   │ 0.0000  │
├────────────────────┼───────────┼─────────┤
│ Skewness           │ -0.2238   │ 0.8229  │
├────────────────────┼───────────┼─────────┤
│ Jarque-Bera        │ 1155.1958 │ 0.0000  │
├────────────────────┼───────────┼─────────┤
│ Shapiro-Wilk       │ 0.9265    │ 0.0000  │
├────────────────────┼───────────┼─────────┤
│ Kolmogorov-Smirnov │ 0.4680    │ 0.0000  │
└────────────────────┴───────────┴─────────┘
```
---
