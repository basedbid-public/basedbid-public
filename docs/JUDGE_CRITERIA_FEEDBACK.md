# Judge Criteria Feedback

## One-liner pitch

Programmable launchpad infrastructure for sustainable token launches

## What is new

BasedBid is not just another launchpad. The novel wedge is the combination of:

- lifetime creator revenue after launch
- multi-recipient Fee Builder routing
- Board-owned launch distribution
- public SDK access through OpenBid
- multi-chain positioning with Solana as the high-speed launch culture layer

## Why now

Token launches have become mainstream, but the creator economics are still immature. Most platforms reward the launch venue or the first trade cycle, while the builder still needs to fund development, marketing, liquidity, rewards, and community growth after graduation.

BasedBid makes post-launch revenue programmable instead of one-time.

## Technical execution

Evidence in this repository:

- `docs/architecture.md` explains the high-level system.
- `docs/fee-routing.md` explains the Solana lifetime fee model.
- `docs/FEE_DISTRIBUTION_TECHNICAL.md` documents routing mechanics.
- `demo/` contains walkthrough and deployment material.
- OpenBid provides the public SDK surface at https://github.com/basedbid-public/openbid.

## Market potential

The market is large because the fee base is trading volume, not subscription revenue or one-time launch fees. BasedBid can grow through:

- creators launching tokens
- Board owners bringing distribution
- KOLs replacing one-time promotions with recurring revenue
- agencies and incubators creating launch environments for clients
- API and SDK integrations through OpenBid

## Unit economics

BasedBid charges a transparent protocol fee on top of creator-configured fees. The path to $1M ARR requires roughly $200M annualized routed volume at a 0.5% protocol fee, or less volume if premium Board, analytics, and enterprise services are included.

See `docs/UNIT_ECONOMICS.md` for scenarios.

## Traction and validation

Evidence in this repository:

- `CURRENT_TRACTION.md`
- `docs/TRACTION_VALIDATION.md`
- `partnerships/PARTNERSHIP_TRACKER.md`
- `partnerships/BOARDS_TRACKER.md`
- `partnerships/LOIs/`

The strongest proof point is the MLMX Board path because it validates the Board thesis: distribution partners want recurring infrastructure, not only one-time campaign payments.

## Competitive differentiation

BasedBid should not claim that no adjacent project has ever explored creator fees. The stronger, more defensible claim is:

> BasedBid is the only submission package we found that combines live launch infrastructure, Board-owned distribution, programmable multi-recipient fee routing, and an open-source SDK companion.

See `docs/COLOSSEUM_COMPETITIVE_RESEARCH.md`.

## Judge takeaway

BasedBid is a commercial infrastructure play, not a one-off demo. The product turns token launches into recurring creator revenue systems, and the public repo plus OpenBid SDK give judges a reviewable path despite production code remaining private.
