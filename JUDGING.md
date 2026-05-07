# Judge Review Guide

This repository is designed to make the basedbid submission easy to evaluate.

## Review this first

1. `README.md` — high-level overview
2. `SUBMISSION.md` — hackathon submission summary
3. `HOWITWORKS.md` — product mechanics
4. `docs/` — deeper product and architecture notes
5. `demo/` — demo materials
6. `traction.md` — traction and progress
7. `Colosseum-Weekly-Updates/` — weekly build history
8. OpenBid SDK — open-source technical companion

## Open-source SDK

The fully open-source SDK lives here:

https://github.com/basedbid-public/openbid

The SDK demonstrates developer-facing interaction with basedbid, including Boards, LBPs, Flash Tokens, buys, sells, and supporting utilities.

## What this repo demonstrates

This repository demonstrates:

- the basedbid product model
- the launch infrastructure thesis
- the Board concept
- Fee Builder mechanics
- traction and partnerships
- hackathon progress
- public documentation
- open-source SDK direction

## What this repo does not demonstrate

This repository does not include the complete production protocol implementation, even though boards, pools, token launches, and OpenBid support are live on mainnet.

It does not demonstrate:

- audited production smart contracts
- complete backend source code
- deployment keys or infrastructure
- private routing logic
- complete security verification

## Why the code is split

The public basedbid repository is the submission and documentation hub.

The OpenBid repository is the clean, open-source SDK repository.

This separation keeps the hackathon submission easy to review while keeping developer tooling clean and independently usable.
