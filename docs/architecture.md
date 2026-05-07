# Architecture

basedbid is structured as programmable token launch infrastructure.

The system is designed around five core layers:

1. Interface layer
2. Board layer
3. Launch layer
4. Fee Builder layer
5. Governance layer

---

## 1. Interface layer

The interface layer is how users and developers interact with basedbid.

This can include:

- the basedbid web app;
- partner integrations;
- developer tooling;
- the OpenBid SDK;
- future APIs or automation interfaces.

The goal of this layer is to make token launches, Board creation, pool setup, and fee configuration accessible without requiring every user to interact directly with lower-level infrastructure.

---

## 2. Board layer

The Board layer defines programmable launch environments.

A Board can represent a KOL, community, incubator, launch agency, DAO, or builder group.

Boards can define:

- launch permissions;
- allowed launch types;
- branding;
- default fee behavior;
- market cap preferences;
- DEX preferences;
- publishing rules;
- governance settings.

This layer turns distribution into infrastructure.

---

## 3. Launch layer

The launch layer supports the core launch products.

### Pools

Pools are Liquidity Bonding Pools with configurable launch parameters and project-controlled economics.

### Flash Tokens

Flash Tokens are instant token launches designed to reduce capital requirements and time-to-market.

Both launch types can be connected to Boards and Fee Builder logic.

---

## 4. Fee Builder layer

The Fee Builder layer defines how trading fees are allocated.

Fees can be routed across categories such as:

- creator revenue;
- KOL incentives;
- rewards;
- marketing;
- buybacks;
- liquidity;
- treasuries;
- custom wallets.

This makes launch economics programmable instead of fixed to a single destination.

---

## 5. Governance layer

The governance layer defines who can update economic parameters over time.

A launch may begin with creator-controlled settings and later transition to:

- multisig control;
- DAO control;
- token-holder governance;
- community takeover structures.

This is designed to let projects evolve without needing to relaunch their entire token economy.

---

## System flow

1. A creator, KOL, community, or partner enters through the interface layer.
2. They create or select a Board.
3. They launch a Pool or Flash Token.
4. Fee Builder rules define who earns from trading activity.
5. Governance controls whether and how the configuration can evolve.
6. The launch continues operating under the configured rules.

---

## Public and private components

| Component | Public in this repo? | Notes |
|---|---:|---|
| Product documentation | Yes | Public submission materials |
| Architecture overview | Yes | High-level system design |
| Demo materials | Yes | Judge-facing demo support |
| OpenBid SDK | Separate repo | Fully open-source technical companion |
| Production smart contracts | No | Private implementation |
| Backend services | No | Private implementation |
| Admin tooling | No | Private implementation |
| Deployment infrastructure | No | Private implementation |

---

## OpenBid SDK

The OpenBid SDK is maintained separately:

https://github.com/basedbid-public/openbid

It is the public, open-source developer companion for interacting with basedbid.

This repository remains the public Colosseum submission hub.
