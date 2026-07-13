# Static Dungeon System

Status: [PHASE 1 — Refine, placement PROPOSED]

## Identity
Handcrafted, finite, permanent-world dungeons. Tiered by stage count
(Den 2-3 / Lair 3-4 / Depths 5-6 — tier card still Phase 0). Entrance
guarded in the overworld; discovery via organic signposting (unusual
enemy density), never map markers.

## State machine [RATIFIED]
PRISTINE -> (checkpoint used, then leave or die) -> CONTESTED -> (full
clear) -> CLEARED. Full clear from PRISTINE also -> CLEARED. Death
before checkpoint use: full void, remains PRISTINE [PROPOSED default].
Failed CONTESTED attempts: no further escalation [PROPOSED default].

## Rules [RATIFIED]
- **Entrance zone**: overworld region bound to the dungeon; everything
  done there is recorded against the dungeon's attempt. On area load,
  the game reads dungeon state and populates entrance + interior
  accordingly.
- **Transaction**: no XP/rewards unless completed. Visible accumulator
  from entrance zone onward; forfeit warning on leaving; no
  recompensation for forfeited kills.
- **Checkpoint**: single-use, mid-dungeon, commits staged progress.
- **Invasion**: checkpoint used + attempt ends early (leave or die) →
  rival faction permanently occupies cleared sections (new bounded
  spawns, no replenishment, does not drain rival's own den);
  checkpoint disabled forever; dungeon becomes do-or-die.
- **Boss dialogue**: final boss has dialogue in pristine state;
  contested state withholds it (boss attacks outright).

## Open
- Quit-mid-attempt rule (suspend-save vs void).
- Post-clear lifecycle (Phase 0 card; reoccupation partially answers).
- Session length at Depths tier under do-or-die.

## Dependencies
Faction system, enemy taxonomy, save system (frontier + faction state),
XP transaction, boss dialogue system.
