---
title: basic
description: The page provides extensive information on how to use the 'basic' function
  in the cryptocurrency realm to extract key details of a coin such as its name, symbol,
  rank, type, description, platform, proof_type, tags, contract and parent. Contains
  usage instructions and examples.
keywords:
- crypto
- coin information
- python crypto commands
- cryptocurrency
- bitcoin
- function usage
- crypto function
- basic
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="crypto/dd/basic - Reference | OpenBB Terminal Docs" />

Get basic information for coin. Like: name, symbol, rank, type, description, platform, proof_type, contract, tags, parent

### Usage

```python
basic
```

---

## Parameters

This command has no parameters



---

## Examples

```python
2022 Feb 15, 07:10 (🦋) /crypto/dd/ $ basic
                                    Basic Coin Information
┌─────────────┬───────────────────────────────────────────────────────────────────────────────┐
│ Metric      │ Value                                                                         │
├─────────────┼───────────────────────────────────────────────────────────────────────────────┤
│ id          │ btc-bitcoin                                                                   │
├─────────────┼───────────────────────────────────────────────────────────────────────────────┤
│ name        │ Bitcoin                                                                       │
├─────────────┼───────────────────────────────────────────────────────────────────────────────┤
│ symbol      │ BTC                                                                           │
├─────────────┼───────────────────────────────────────────────────────────────────────────────┤
│ rank        │ 1                                                                             │
├─────────────┼───────────────────────────────────────────────────────────────────────────────┤
│ type        │ coin                                                                          │
├─────────────┼───────────────────────────────────────────────────────────────────────────────┤
│ description │ Bitcoin is a cryptocurrency and worldwide payment system. It is the first     │
│             │ decentralized digital currency, as the system works without a central bank or │
│             │ single administrator.                                                         │
├─────────────┼───────────────────────────────────────────────────────────────────────────────┤
│ platform    │ bnb-binance-coin                                                              │
├─────────────┼───────────────────────────────────────────────────────────────────────────────┤
│ proof_type  │ Proof of Work                                                                 │
├─────────────┼───────────────────────────────────────────────────────────────────────────────┤
│ contract    │ 0x719bd7b3d60f0b194fdbe4570aeda1b3712b4986                                    │
├─────────────┼───────────────────────────────────────────────────────────────────────────────┤
│ tags        │ Segwit, Cryptocurrency, Proof Of Work, Payments, Sha256, Mining, Lightning    │
│             │ Network                                                                       │
├─────────────┼───────────────────────────────────────────────────────────────────────────────┤
│ parent      │ bnb-binance-coin                                                              │
└─────────────┴───────────────────────────────────────────────────────────────────────────────┘
```
---
