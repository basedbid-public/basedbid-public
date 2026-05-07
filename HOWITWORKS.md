# How basedbid works

basedbid is programmable token launch infrastructure for instant launches, Liquidity Bonding Pools, and creator-owned Boards.

It is designed to let creators, KOLs, communities, incubators, and builder groups define how launches work, who can participate, and how trading fees are routed.

---

## Core idea

Most token launch systems treat launch revenue as platform-owned.

basedbid is designed around a different model:

> the protocol does not eat first. the builder eats first.

This means launch economics can be configured around creators, communities, KOLs, rewards, treasuries, buybacks, liquidity, and long-term governance.

---

## Core products

### Pools

Pools are Liquidity Bonding Pools with configurable launch parameters.

They are designed for teams that want more control over launch mechanics, market cap parameters, and fee routing.

Pools can support:

- configurable launch settings;
- custom market cap parameters;
- fee routing through Fee Builder;
- Board-level launch rules;
- long-term governance transition.

---

### Flash Tokens

Flash Tokens are instant token launches designed to reduce launch complexity and time-to-market.

They are designed for creators who want a faster path to deployment while still being able to connect launch economics to Fee Builder and Board infrastructure.

Flash Tokens can support:

- fast deployment;
- virtual liquidity;
- lower capital requirements;
- Fee Builder compatibility;
- Board-based distribution.

---

### Boards

Boards are programmable launch environments.

They can be created by:

- KOLs;
- communities;
- incubators;
- launch agencies;
- DAOs;
- builder groups.

A Board can define launch permissions, branding, allowed launch types, default fee behavior, DEX preferences, market cap parameters, and governance settings.

Boards turn distribution into infrastructure.

Instead of promoting launches for one-time payments, Board owners can support launches through a recurring on-chain revenue model.

---

### Fee Builder

Fee Builder is the programmable fee routing system.

It lets launch creators, Boards, and future governance structures define how trading fees are allocated across multiple recipients.

Fee Builder can route value to:

- creators;
- KOLs;
- rewards;
- marketing;
- buybacks;
- liquidity;
- treasuries;
- custom wallets.

This creates a more flexible economic model than fixed platform-owned launch fees.

---

## Fee Builder visual

<p align="center">
  <img width="1440" height="896" alt="basedbid Fee Builder flow" src="https://github.com/user-attachments/assets/271ed1d4-ac74-48ff-8d7f-e5e2e75e010f" />
</p>

---

## Launch flow

1. A creator, KOL, community, or partner enters through the basedbid interface.
2. They create or select a Board.
3. They launch a Pool or Flash Token.
4. Fee Builder rules define how trading activity is routed.
5. Recipients can include creators, KOLs, rewards, buybacks, liquidity, marketing, and treasuries.
6. Governance can later update rules if enabled.

---

## Why this matters

basedbid is designed to address several common problems in token launch infrastructure:

- creators often lack sustainable post-launch revenue;
- platforms often capture most of the economics;
- KOLs and marketers are often paid in tokens and may need to sell;
- tax-token models can accumulate supply and create visible sell pressure;
- static contracts are difficult to adapt after launch.

The goal is to make launches more sustainable, programmable, and aligned with the people who build and distribute them.

---

## Relationship to OpenBid

The OpenBid SDK is the open-source developer companion for basedbid:

https://github.com/basedbid-public/openbid

This repository is the public Colosseum submission hub. OpenBid is the clean, fully open-source SDK repository.

---

## Public/private boundary

The complete production basedbid implementation is private and is not included in this repository.

For more detail, see:

- [DISCLAIMER.md](./DISCLAIMER.md)
- [docs/private-code-boundary.md](./docs/private-code-boundary.md)
