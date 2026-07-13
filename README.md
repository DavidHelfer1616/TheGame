# TheGame (working title)

3D action-adventure built in **Godot 4** by David + Claude. Core hook: a
hidden milestone system that silently tracks player behavior and rewards
emergent playstyles with unexpected perks (inspired by Solo Leveling).

Repo: https://github.com/DavidHelfer1616/TheGame (public, single source
of truth for design and, later, code).

## Orientation for any new Claude session

Read in this order before doing anything:
1. `docs/process/decision-log.md` — every ratified ruling + pending
   proposals. This is project law.
2. `docs/process/pipeline.md` — the phase process and current idea board.
3. The relevant `docs/systems/` or `docs/world/` file for whatever is
   being worked on.

Non-negotiable rules:
- **All ratification and phase advancement authority belongs to David.**
  Claude proposes; David signs off. Never mark anything ratified or
  advance a phase without his explicit approval.
- Status labels everywhere: `[RATIFIED]` / `[PROPOSED]` / `[OPEN]`.
- New ideas surfacing mid-discussion get pinned to Phase 0 in
  `pipeline.md` immediately.
- David prefers objective trade-off analysis over validation; skip the
  praise, surface the costs.
- Docs are updated in the same session as the decisions they record;
  Claude handles commits/pushes desktop-side with David's approval.

## Layout

    docs/process/   pipeline definition, idea board, decision log
    docs/world/     world & region content
    docs/systems/   mechanical system specs (one file per pipeline card)

The Godot project will live beside `docs/` in this repo when production
begins.
