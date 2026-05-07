# Fee Builder

Fee Builder is the programmable fee routing system for basedbid launches.

It lets creators, Boards, and future governance structures define how trading fees are allocated across multiple recipients.

Instead of treating all launch revenue as a single protocol-owned stream, Fee Builder makes launch economics configurable.

---

## Visual overview

<p align="center">
  <img width="1440" height="896" alt="basedbid Fee Builder flow" src="https://github.com/user-attachments/assets/271ed1d4-ac74-48ff-8d7f-e5e2e75e010f" />
</p>

## What Fee Builder can route to

Fee Builder can support routing across recipients such as:

* creator revenue;
* KOL incentives;
* community rewards;
* user rewards;
* buybacks;
* burns;
* marketing wallets;
* liquidity allocations;
* incubator allocations;
* DAO treasuries;
* custom wallets.

---

## Why it matters

Many launch systems create misalignment:

* creators lose economics to the platform;
* KOLs are paid in tokens and may need to sell;
* tax-token models can accumulate tokens and create visible sell pressure;
* static contracts make it hard to update economics after launch.

Fee Builder is designed to make launch economics programmable and adaptable.

---

## Native or stable asset routing

Fee Builder is designed around cleaner reward routing.

Instead of forcing every stakeholder to receive project tokens, rewards can be routed in native or stable assets where supported.

This matters because token-based compensation can create sell pressure when teams, KOLs, marketers, or service providers need to realize income.

---
## Fee Builder flow

> Trade occurs  
> ↓  
> Fee logic is applied  
> ↓  
> Routing rules determine recipients  
> ↓  
> Recipients receive configured allocations  
> ↓  
> Governance can update rules over time if enabled.

---

## Supported allocation categories

| Category  | Example use                     |
| --------- | ------------------------------- |
| Creator   | Sustainable project revenue     |
| KOL       | Distribution partner incentives |
| Rewards   | User or holder rewards          |
| Marketing | Growth budget                   |
| Buyback   | Market support allocation       |
| Liquidity | Liquidity support               |
| Treasury  | DAO or multisig treasury        |
| Custom    | Any approved wallet or module   |

---

## Governance and updates

Fee Builder is designed to support evolving project needs.

A project may start with creator-controlled routing and later transition control to:

* a multisig;
* a DAO;
* token-holder governance;
* a community takeover structure.

This allows projects to adapt without needing to relaunch their entire token economy.

---

## Relationship to Boards

Boards can define default Fee Builder settings for launches created through that Board.

For example, a KOL Board might require every launch to route fees across:

* creator revenue;
* KOL incentives;
* community rewards;
* marketing;
* buybacks;
* treasury.

This makes Boards programmable distribution environments rather than simple listing pages.
