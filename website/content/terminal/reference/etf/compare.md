---
title: compare
description: A documentation page for the 'compare' function used in StockAnalysis.
  The function allows users to compare selected ETF symbols to obtain various financial
  and trading data. Parameters, usage, and examples are provided.
keywords:
- StockAnalysis
- ETF comparison
- Financial data
- Trading information
- Financial analysis tools
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="etf /compare - Reference | OpenBB Terminal Docs" />

Compare selected ETFs [Source: StockAnalysis]

### Usage

```python
compare -e NAMES
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| names | Symbols to compare | None | False | None |


---

## Examples

```python
2022 Feb 15, 04:24 (🦋) /etf/ $ compare VOO,SPY
               ETF Comparisons
┌────────────────┬────────────┬─────────────┐
│                │ VOO        │ SPY         │
├────────────────┼────────────┼─────────────┤
│ Assets         │ $283.52B   │ $407.71B    │
├────────────────┼────────────┼─────────────┤
│ NAV            │ $413.03    │ $449.25     │
├────────────────┼────────────┼─────────────┤
│ Expense Ratio  │ 0.03%      │ 0.09%       │
├────────────────┼────────────┼─────────────┤
│ PE Ratio       │ 24.90      │ 22.23       │
├────────────────┼────────────┼─────────────┤
│ Shares Out     │ 686.44M    │ 907.53M     │
├────────────────┼────────────┼─────────────┤
│ Dividend (ttm) │ $5.44      │ $5.72       │
├────────────────┼────────────┼─────────────┤
│ Dividend Yield │ 1.35%      │ 1.30%       │
├────────────────┼────────────┼─────────────┤
│ Volume         │ 10,167,584 │ 123,006,262 │
├────────────────┼────────────┼─────────────┤
│ Open           │ 404.43     │ 439.92      │
├────────────────┼────────────┼─────────────┤
│ Previous Close │ 404.94     │ 440.46      │
├────────────────┼────────────┼─────────────┤
│ 52-Week Low    │ 341.92     │ 371.88      │
├────────────────┼────────────┼─────────────┤
│ 52-Week High   │ 341.92     │ 371.88      │
├────────────────┼────────────┼─────────────┤
│ Beta           │ 0.99       │ 0.99        │
├────────────────┼────────────┼─────────────┤
│ Holdings       │ 510        │ 507         │
└────────────────┴────────────┴─────────────┘
```
---