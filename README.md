# Punt · XRM-001 — Cross-room play (POC)

An interactive proof-of-concept exploring a single, deliberate play that spans Punt's
three rooms — **Predict**, **Collect**, and **Play** — presented as **five switchable UX
patterns**. It's a single self-contained HTML file: no build step, no dependencies.

## View it

Open [`xrm-001-cross-room-play.html`](xrm-001-cross-room-play.html) in any modern browser.

## The concept

One play — **Call it · Land it · Score it** — threads through all three rooms:
call the fight (Predict) → land the pack (Collect) → score at the table (Play).
One entry, one combined payout, and a **cross-room bonus that only unlocks when all
three rooms are active** — the mechanic the POC is built to test.

## The five concepts

Each explores a different answer to *how the single play is represented, and what makes
moving between rooms feel intentional rather than incidental*:

| # | Concept | Pattern |
|---|---------|---------|
| V1 | The Combo Slip | Bundle-first parlay — resolve pre-committed legs room by room |
| V2 | The Run | Causal chain (gated) — each room's result fuels the next |
| V3 | The Event Deck | Live event, one score — rooms as stations on one timeline |
| V4 | The Object Thread | Entity as through-line — back the same pick across rooms |
| V5 | The Carry | Persistent play object — the play travels as fixed UI |

## Using the prototype

- **CONCEPTS** button (bottom-left) opens the switcher: the five variations, a **UX notes**
  tray (rationale + considerations per concept), and **restart**.
- The **light / dark** switch beside it toggles the editorial-mono and dark-brand skins.
- Fully responsive from mobile to desktop.

## Status

Internal POC — happy-path flows only. Hatched boxes are placeholders marking where real
imagery would sit.
