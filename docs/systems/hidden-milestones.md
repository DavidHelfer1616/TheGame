# Hidden Milestone System

Status: [PHASE 1 — Refine] — the project's core hook.

## Purpose
The game silently tracks player behavior against unstated conditions and
rewards emergent playstyles with unexpected perks. Discovery-driven
replayability; "the game noticed that" moments.

## Settled [RATIFIED]
- **Two families**:
  1. **General world milestones** — accrual counters (kills by enemy
     type at supertype and subtype level) paying incremental typed
     bonuses (e.g., +5% damage vs beasts). Tiers exist; structure TBD.
  2. **Class milestones** — mastery conditions (e.g., N perfect blocks
     vs an enemy type) paying **rule-breaking perks** scoped to the
     proven content (e.g., all blocks vs that type count as perfect).
- **Reveal rule**: invisible until earned; on trigger, reveal name +
  condition. No next-tier progress shown.
- **Anti-farm**: content distribution (finite static world; subtype
  concentration) + weighted/limited kill credit.
- Milestone counters ride inside the XP/reward transaction (see
  xp-reward-transaction.md): staged in dungeons, committed on clear.

## Candidate principle [PROPOSED]
General milestones track what you've done TO the world (only real kills
count — Incursions yes, Rifts no). Class milestones track what you've
BECOME (mastery counts everywhere, including Rifts, and persists per
the transaction rules TBD).

## Open
- **Weighting basis**: point-weighted kills vs tier-gated counting
  (only kills at/near player tier register). Affects honesty of
  revealed condition text.
- **Tier structure** for general milestones (thresholds, growth curve,
  whether higher tiers upgrade bonus quality, caps).
- Perk **stacking rules** across families and with gear.
- **Journal/codex UI** (earned entries only; no empty-slot spoilers).
- Accumulator-hides-counters rule [PROPOSED, awaiting sign-off].
- Parked condition categories (non-combat): avoidance/mercy,
  exploration, economy, risk, social, ritual/oddity — on the table,
  not active.

## Dependencies
Enemy taxonomy (Phase 0), class system (Phase 0), combat system
perfect-timing mechanics (Phase 0), XP transaction (Phase 1),
save system (Phase 0).
