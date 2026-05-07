# basedbid — Colosseum Frontier Hackathon 2026 Submission

## Project

basedbid

## One-line summary

basedbid is programmable token launch infrastructure for instant launches, Liquidity Bonding Pools, and creator-owned Boards.

## What basedbid does

basedbid lets builders, creators, KOLs, communities, and incubators launch tokens or Liquidity Bonding Pools while defining how trading fees are routed across creators, communities, KOLs, rewards, buybacks, marketing, liquidity, and treasury destinations.

boards, pools, token launches, and OpenBid support are live on mainnet.

## Core products

- **Pools** — Liquidity Bonding Pools with configurable launch parameters.
- **Flash Tokens** — instant token launches using virtual liquidity.
- **Boards** — white-label launch environments for KOLs, communities, agencies, and incubators.
- **Fee Builder** — programmable fee routing across multiple recipients.

## Why it matters

Most token launch systems are structurally misaligned:

- platforms capture most of the economics;
- creators lack sustainable post-launch revenue;
- KOLs are often paid in tokens and forced to sell;
- tax-token models can accumulate supply and create batch-selling pressure;
- static launch contracts are hard to evolve after deployment.

basedbid is designed to turn token launch distribution into programmable economic infrastructure.

## What was built for this submission

This public repository documents the basedbid system and submission materials:

- product overview
- architecture documentation
- demo flow
- weekly Colosseum updates
- metrics and traction summaries
- partnerships
- open-source SDK link
- judge-facing review guide

## Open-source technical companion

The OpenBid SDK is maintained separately for cleanliness:

https://github.com/basedbid-public/openbid

OpenBid contains the public TypeScript SDK and developer tooling for interacting with basedbid.

## What is private

The full production basedbid implementation is live but private, and is not included in this repository.

This repository should be reviewed as the public submission hub, not as a full production protocol codebase.

## Suggested review path

1. Read `README.md`
2. Read `HOWITWORKS.md`
3. Read `JUDGING.md`
4. Review `docs/`
5. Review `demo/`
6. Review `traction.md`
7. Review the OpenBid SDK repository
