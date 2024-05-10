---
title: wf
description: The documentation page contains information regarding the withdrawal
  fees for top coins in cryptocurrency. It provides a detailed insight into the average,
  median and highest withdrawal fees for coins such as Bitcoin, Ethereum and Tether
  among others. The tool also allows to limit the number of coins while displaying
  the withdrawal fees.
keywords:
- withdrawal fees
- top coins
- cryptocurrency
- Bitcoin
- Ethereum
- Tether
- Binance Coin
- USD Coin
- XRP
- Cardano
- Solana
- Terra
- Avalanche
---

import HeadTitle from '@site/src/components/General/HeadTitle.tsx';

<HeadTitle title="crypto/ov/wf - Reference | OpenBB Terminal Docs" />

Display top coins withdrawal fees [Source: https://withdrawalfees.com/]

### Usage

```python
wf [-l LIMIT]
```

---

## Parameters

| Name | Description | Default | Optional | Choices |
| ---- | ----------- | ------- | -------- | ------- |
| limit | Limit number of coins to display withdrawal fees. Default 10 | 10 | True | None |


---

## Examples

```python
2022 Feb 15, 08:21 (🦋) /crypto/ov/ $ wf

Withdrawal fees on exchanges:
                                     Top Withdrawal Fees
┌──────────────┬──────────────┬─────────┬────────┬──────────────────────┬────────────────────┐
│ Coin         │ Lowest       │ Average │ Median │ Highest              │ Exchanges Compared │
├──────────────┼──────────────┼─────────┼────────┼──────────────────────┼────────────────────┤
│ Bitcoin      │ FREE         │ $20.01  │ $22.13 │ $66.40 (0.0015 BTC)  │ 38                 │
├──────────────┼──────────────┼─────────┼────────┼──────────────────────┼────────────────────┤
│ Ethereum     │ FREE         │ $22.54  │ $19.39 │ $74.48 (0.024 ETH)   │ 37                 │
├──────────────┼──────────────┼─────────┼────────┼──────────────────────┼────────────────────┤
│ Tether       │ FREE         │ $19.24  │ $15.55 │ $100.00 (100 USDT)   │ 30                 │
├──────────────┼──────────────┼─────────┼────────┼──────────────────────┼────────────────────┤
│ Binance Coin │ FREE         │ $4.06   │ $0.64  │ $21.38 (0.05 BNB)    │ 16                 │
├──────────────┼──────────────┼─────────┼────────┼──────────────────────┼────────────────────┤
│ USD Coin     │ FREE         │ $21.39  │ $19.98 │ $50.96 (51 USDC)     │ 27                 │
├──────────────┼──────────────┼─────────┼────────┼──────────────────────┼────────────────────┤
│ XRP          │ FREE         │ $1.79   │ $0.21  │ $30.02 (36 XRP)      │ 29                 │
├──────────────┼──────────────┼─────────┼────────┼──────────────────────┼────────────────────┤
│ Cardano      │ $0.330.3 ADA │ $6.94   │ $1.08  │ $146.63 (135.14 ADA) │ 26                 │
├──────────────┼──────────────┼─────────┼────────┼──────────────────────┼────────────────────┤
│ Solana       │ FREE         │ $1.17   │ $1.02  │ $5.00 (0.049 SOL)    │ 18                 │
├──────────────┼──────────────┼─────────┼────────┼──────────────────────┼────────────────────┤
│ Terra        │ FREE         │ $4.11   │ $1.13  │ $30.53 (0.54 LUNA)   │ 15                 │
├──────────────┼──────────────┼─────────┼────────┼──────────────────────┼────────────────────┤
│ Avalanche    │ FREE         │ $1.77   │ $0.88  │ $8.83 (0.1 AVAX)     │ 15                 │
└──────────────┴──────────────┴─────────┴────────┴──────────────────────┴────────────────────┘
```
---
