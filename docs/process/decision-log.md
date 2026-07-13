# Decision Log

Append-only. Every ratified ruling, dated. [PROPOSED] entries listed at
bottom until David signs off.

## Ratified

- **2026-07-12 — Engine**: Godot 4.
- **2026-07-12 — Pipeline**: Phases 0 Establish / 1 Refine / 2 Validate;
  ideas travel individually; feasibility failures loop back to Phase 0;
  names and Phase 2 definition ratified.
- **2026-07-12 — Authority**: phases close only on David's explicit sign-off.
- **2026-07-12 — Milestone reveal rule**: milestones invisible until earned;
  on trigger, reveal name + condition (no next-tier progress shown).
- **2026-07-12 — Milestone families**: (1) general world milestones —
  accrual counters (e.g., kills by enemy type) paying incremental typed
  bonuses; (2) class milestones — mastery conditions (e.g., perfect blocks
  vs enemy type) paying rule-breaking perks scoped to proven content.
- **2026-07-12 — Anti-farm strategy**: content distribution (subtype
  concentrated per dungeon; supertype thresholds exceed any single source)
  plus weighted/limited kill credit (basis TBD). Tiers exist for general
  milestones; structure TBD.
- **2026-07-12 — Static dungeons are finite**: enemy populations never
  respawn. "Finite" = one permanent commit per dungeon.
- **2026-07-12 — Dynamic dungeon split**: some dynamic dungeons grant
  general-milestone credit, some do not; the two natures are visibly
  distinct on sight. Provisional labels: Incursions (credit) / Rifts
  (no kill credit). Names placeholder pending story premise.
- **2026-07-12 — Static dungeon transaction model**:
  - The overworld **entrance zone** is bound to its dungeon; all kills/
    rewards from entrance zone onward stage into the attempt. **No XP or
    rewards unless the dungeon is completed** (universal, including
    pristine-state entrance kills).
  - A visible **accumulator** shows staged rewards from the entrance zone
    onward; leaving triggers a forfeit warning. Forfeited kills are not
    recompensed on re-entry; zone repopulates per state on area reload.
  - **Single-use mid-dungeon checkpoint**: commits staged progress once.
  - **Invasion trigger**: checkpoint used + attempt ends before completion
    (leaving OR dying) → rival faction permanently occupies cleared space;
    checkpoint permanently disabled; dungeon becomes **do-or-die**
    (complete or gain nothing).
  - Post-checkpoint death: post-checkpoint gains lost + invasion occurs.
  - **Occupation force**: newly spawned, bounded, permanent; does NOT
    deplete the rival's own dungeon; never replenishes.
- **2026-07-12 — Boss dialogue**: every static dungeon final boss has
  dialogue; invaded/contested state withholds dialogue (boss attacks).
- **2026-07-12 — Compartmentalization**: worldbuilding, static dungeon
  system, and XP/reward transaction split from the milestone card into
  separate pipeline items.

## Proposed (awaiting David)

- Accumulator displays XP/loot only; hidden milestone counters ride the
  same transaction but are never itemized.
- Contested state is stable: failed do-or-die attempts cause no further
  escalation.
- Death before any checkpoint use: full void, dungeon stays pristine,
  checkpoint intact.
- Faction conflict implemented as authored state machines (scripted
  states), not simulation.
- Phase 1 placement of "static dungeon system" and "XP & reward
  transaction" cards.
- General milestone thresholds sit at ~60-70% of world kill budget
  (never require extermination).
- Quit-mid-attempt rule: suspend-save vs quit-counts-as-leaving (OPEN,
  no recommendation ratified).
