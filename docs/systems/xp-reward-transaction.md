# XP & Reward Transaction System

Status: [PHASE 1 — Refine, placement PROPOSED]

## Concept
"Zones of temporary progress": designated content (currently static
dungeons, starting at their entrance zones) stages all gains — XP,
loot, milestone counters — in an attempt buffer. Commit points write
the buffer to the permanent record; failure/forfeit discards it.

## Rules [RATIFIED]
- Commit events: single-use checkpoint (once) and dungeon completion.
- Nothing is granted without completion; entrance-zone-only excursions
  earn nothing and warn on exit.
- Visible accumulator UI shows staged gains during an attempt.

## Proposed
- Accumulator itemizes XP/loot only; milestone counters stay hidden
  within the transaction (protects the hidden-milestone grammar).
- Class/mastery progress persistence through failed attempts: leaning
  "skill performed is skill kept" — UNRESOLVED.

## Open
- Dynamic dungeons will have DIFFERENT rules for skills/loot/XP
  (explicitly deferred by David).
- Loot handling detail: drop-then-void vs nothing-drops-until-commit.
