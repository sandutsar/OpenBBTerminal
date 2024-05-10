---
title: stats
description: Documentation for 'stats' query, providing base statistics about Uniswap,
  a decentralized exchange (DEX). The page includes usage instructions and examples
  of results including metrics like totalVolumeUSD, totalLiquidityUSD, pairCount,
  txCount, and totalLiquidityETH.
keywords:
- Uniswap DEX
- DEX statistics
- crypto defi stats
- volumeUSD
- liquidityUSD
- pairCount
- txCount
- liquidityETH
- base statistics
- theGraph.com
- usage query
- Uniswap metrics
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="crypto/defi/stats - Reference | OpenBB Terminal Docs" />

Display base statistics about Uniswap DEX. [Source: https://thegraph.com/en/]

### Usage

```python
stats
```

---

## Parameters

This command has no parameters



---

## Examples

```python
2022 Feb 15, 06:33 (🦋) /crypto/defi/ $ stats
 Uniswap DEX Base Statistics
┌───────────────────┬────────┐
│ Metric            │ Value  │
├───────────────────┼────────┤
│ totalVolumeUSD    │ 393.2B │
├───────────────────┼────────┤
│ totalLiquidityUSD │ 3.3B   │
├───────────────────┼────────┤
│ pairCount         │ 63.3K  │
├───────────────────┼────────┤
│ txCount           │ 73.6M  │
├───────────────────┼────────┤
│ totalLiquidityETH │ 1.1M   │
└───────────────────┴────────┘
```
---
