# Alpha7Ωmega Crypto Intelligence

Public source for the **Alpha7Ωmega** command desk — a live perp / DEX / on-chain radar.

Live: [alpha7omega.grok.me](https://alpha7omega.grok.me)

Research desk, not a broker. Perps can liquidate. DeepHeat is a score, not a fill. CLIFF is inventory math, not a signal you have to take.

## What this is

Stamp-indexed Binance USDT-M tape → Sunday book vs Wednesday tape → isolated short / trail / do-not-fade calls.

- **Desk** — NOW book, circled tape, GI ledger, DeepHeat longs / 24h fades
- **Super matrix** — Sunday 6 Sep vs Wednesday 9 Sep 2026 (66h), alerts that fire on live quotes
- **Hunt / Shorts** — CLIFF mismatch (perp OI vs DEX pool), fade rules
- **Map** — bubble field / galaxy / squeeze
- **BTC seat** — 48h volume-at-price + live depth ±1.2% of mid
- **Flow** — DeFiLlama TVL / DEX / fees, whale map
- **Terra** — native LUNC / LUNA LCD metrics vs meme impostors
- **Mint / Privacy / Intel** — listings, ZEC sleeve, CT / news diary

## Stack

React 19 · TanStack Start / Router / Query · Vite · Tailwind v4 · Zustand

Market rails: Gate.io futures, CoinGecko (with Gate fallback), DexScreener, DeFiLlama, Terra LCD (columbus-5 / phoenix-1).

## Run

```bash
npm install
npm run dev
```

Dev server binds `0.0.0.0:8080`.

```bash
npm run typecheck
npm run build
```

## Desk rules (Wed 9 Sep 2026, 09:50 SAST stamp)

| Stance | Names |
|---|---|
| Short / fade | FF isolated (stop 0.152), USELESS re-fade on 0.320 / 0.312, IOST dust |
| Trail only | MARSCOIN — T1 0.150 hit, cover 0.155 |
| Do not fade as P&D | VVV (Venice AI), RAY, ATOM, DOT, ZEC, LIT (Lighter), BTC, ETH, SOL |
| Too late | SOPH, FORM, COLLECT, CYS, STAR, AKE, XAN, HEMI |

Isolated. Never 38×. Percent is a liar — sort by quote volume first.

## License

Source published by [AlphaOmegaAI2032](https://github.com/AlphaOmegaAI2032). All rights reserved unless a later license is added.
