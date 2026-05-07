# Boards

Boards are programmable launch environments for KOLs, communities, incubators, launch agencies, DAOs, and builder groups.

A Board lets a distribution owner create their own launch surface with configurable rules, branding, permissions, fee defaults, and revenue structures.

Instead of promoting token launches for one-time payments, a Board owner can turn distribution into recurring on-chain infrastructure.

---

## What a Board can define

A Board can define:

* who can launch;
* which launch types are allowed;
* default fee routing;
* market cap parameters;
* DEX preferences;
* branding;
* publishing permissions;
* reward rules;
* governance settings.

---

## Why Boards matter

Most launch infrastructure treats distribution as an external marketing function.

basedbid treats distribution as part of the infrastructure layer.

This means a KOL, agency, community, or incubator can move from:

promote once → get paid once

to:

own launch environment → support projects → earn recurring revenue

Boards create a more aligned model between:

* creators;
* launch partners;
* KOLs;
* communities;
* traders;
* treasuries.

---

## Example Board use cases

### KOL Board

A KOL creates a curated launch Board for projects they support.

The Board can route a percentage of trading fees to:

* the project creator;
* the KOL;
* community rewards;
* marketing;
* buybacks;
* treasury.

### Incubator Board

An incubator creates a Board for portfolio projects.

The Board can define launch standards, default fee routing, approved launchers, and long-term treasury allocations.

### Community Board

A DAO or community creates a Board where approved members can launch projects under shared rules.

Governance can eventually manage fee structures, permissions, and launch criteria.

### Agency Board

A launch or marketing agency creates a Board for clients.

Instead of charging only upfront retainers, the agency can participate in recurring revenue from launches it helps distribute.

---

## Board lifecycle

Create Board
↓
Set rules
↓
Approve launchers
↓
Launch token or LBP
↓
Route fees
↓
Transition governance if needed
↓
Continue earning from supported launches

---

## Relationship to Fee Builder

Boards can define default Fee Builder settings for launches created through that Board.

For example, a KOL Board might require every launch to route fees across:

* creator revenue;
* KOL incentives;
* community rewards;
* marketing;
* buybacks;
* treasury.

This makes Boards programmable distribution infrastructure rather than simple listing pages.

---

## Relationship to OpenBid

The OpenBid SDK is the open-source developer companion for interacting with basedbid.

OpenBid lives in a separate repository:

[https://github.com/basedbid-public/openbid](https://github.com/basedbid-public/openbid)

The public SDK can expose developer-facing flows such as Board creation, pool creation, Flash Token deployment, and fee configuration while keeping the full production basedbid implementation private.

---

## Public repository note

This document describes the intended product model and user-facing architecture.

The complete production implementation is private and is not included in this repository.

For more detail, see:

* [DISCLAIMER.md](../DISCLAIMER.md)
* [private-code-boundary.md](./private-code-boundary.md)
