# Private Code Boundary

This document explains what is public, what is open source, and what remains private.

## Public in this repository

The `basedbid` repository includes:

- product documentation
- hackathon submission materials
- demo information
- traction and metrics summaries
- partnership notes
- weekly updates
- architecture explanations
- links to the open-source SDK

## Open source in the OpenBid repository

The OpenBid SDK is maintained separately:

https://github.com/basedbid-public/openbid

OpenBid is the public developer-facing SDK and tooling repository.

It is separate from this submission repository for cleanliness.

## Private implementation

The complete production basedbid implementation is private.

Private components may include:

- production smart contracts
- backend services
- admin systems
- deployment scripts
- private ABIs
- security-sensitive configuration
- privileged infrastructure
- internal monitoring and operational tooling

## Why this boundary exists

basedbid is presenting this repository as a public hackathon submission hub, not as a complete open-source release of the production protocol.

The goal is to let judges understand:

- what basedbid is;
- what problem it solves;
- how the architecture is intended to work;
- what has been built publicly;
- where the open-source SDK lives;
- and which parts are intentionally private.

## Verification note

Unless explicitly stated, material in this repository should not be interpreted as audited, verified, or production-complete code.
