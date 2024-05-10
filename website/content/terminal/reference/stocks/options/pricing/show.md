---
title: show
description: This page provides the 'show' command, used to display stock option price
  and it's estimated chance. It comes without parameters.
keywords:
- show command
- stock options
- display prices
- no parameters
- stock price estimation
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="stocks/pricing/show /options - Reference | OpenBB Terminal Docs" />

Display prices

### Usage

```python
show
```

---

## Parameters

This command has no parameters



---

## Examples

```python
2022 Feb 16, 09:45 (🦋) /stocks/options/pricing/ $ add -p 100 -c 0.5

2022 Feb 16, 09:46 (🦋) /stocks/options/pricing/ $ add -p 200 -c 0.5

2022 Feb 16, 09:46 (🦋) /stocks/options/pricing/ $ show
Estimated price(s) of AAPL at 2022-05-20
┏━━━━━━━━┳━━━━━━━━┓
┃ Price  ┃ Chance ┃
┡━━━━━━━━╇━━━━━━━━┩
│ 100.00 │ 0.50   │
├────────┼────────┤
│ 200.00 │ 0.50   │
└────────┴────────┘
```
---
