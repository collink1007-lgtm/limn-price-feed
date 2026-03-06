# Real DexScreener Price Feed

> Part of the Tessera Sovereign Realification Initiative

## Overview
Replace hardcoded prices with live DexScreener API polling

## Current State
**HARDCODED** — Hardcoded values instead of dynamic configuration

## Target State
Real-time price feed from DexScreener with OHLCV candle data and volume tracking

## Category
**Market Data**

## Approval
- **Proposal ID:** RF-C01-003
- **Votes:** 27/30 APPROVE (90.0%)
- **Threshold:** 2/3 majority (20 votes)
- **Status:** ✅ APPROVED

## Primary Files to Modify
- server/real-limn-data.ts

## Integration Points
- LIMN Token: BvBuBkxUQxhpiRdvoJfTRxi6JcRF7daNcSjfBnNDpump
- Community Wallet: 31D8imP7kmNhnvxaBBxjFhocwq9XDG9FBfgsDQuCwxVj
- Tessera Sovereign Ecosystem

## Getting Started
```bash
npm install
cp .env.example .env
npm run dev
```

## License
MIT — Tessera Sovereign Project
