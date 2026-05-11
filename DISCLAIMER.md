# Public Repository Boundary

This repository is the public Colosseum submission hub for BasedBid. It is designed to explain the product, market, architecture, traction, demo flow, and open-source SDK surface.

## Public in this repository

- Submission narrative and judge navigation.
- Product documentation for Pools, Flash Tokens, Boards, and Fee Builder.
- Architecture notes and fee-routing explanations.
- Demo walkthroughs and deployment notes.
- Market research, traction summaries, and partnership documentation.
- Links to the OpenBid SDK.

## Public in OpenBid

OpenBid is the open-source TypeScript SDK:

https://github.com/basedbid-public/openbid

It contains developer-facing tooling for interacting with BasedBid, including Board creation, LBP creation, Flash Token creation, buy and sell flows, schemas, ABIs, and API transaction helpers.

## Private production components

The complete production BasedBid implementation is live but private. This repository does not include:

- full production smart contracts
- private backend services
- deployment infrastructure
- admin tooling
- internal routing logic
- private keys or operational secrets

## Why the split exists

The split keeps the hackathon submission reviewable while keeping production security boundaries intact. Judges can evaluate the product thesis, traction, architecture, demo materials, and public SDK without exposing sensitive production code.
