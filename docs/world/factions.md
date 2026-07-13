# Factions & Conflict

Status: [PHASE 0 — Establish]

## Concept
Neighboring static dungeons can belong to rival factions. Player action
shifts the local balance (clearing space creates a vacuum the rival
fills). First instance: wolves vs goblins in the forest region.

## Leaning [PROPOSED]
- Implementation as **authored state machines** per contested dungeon
  (e.g., wolf-held → goblin-contested), not a running simulation.
  Player-indistinguishable at a fraction of the cost.

## Requirements surfaced
- Faction hostility matrix; three-way combat AI (enemies fight each
  other; player may third-party or spectate).
- Enemy taxonomy needs a faction field.

## Open
- How many factions; whether conflict exists outside dungeon contexts;
  whether the player can take sides deliberately.
