# Project: Untitled Action-Adventure (working)

3D action-adventure built in **Godot 4** by David + Claude. Core hook: a hidden
milestone system that silently tracks player behavior and rewards emergent
playstyles with unexpected perks (inspired by Solo Leveling).

## How this repo works with Claude

- These docs are the **single source of truth**. Chat sessions are working
  sessions against them; Claude's cross-chat memory holds summaries only.
- **Session start:** upload this folder/zip to Claude, or point Claude at the
  GitHub repo (Claude can read raw GitHub content directly).
- **Session end:** Claude returns updated files; David commits.
- Every doc carries status labels: `[RATIFIED]` (David signed off),
  `[PROPOSED]` (Claude suggestion awaiting sign-off), `[OPEN]` (undecided).
- All phase advancement and ratification authority belongs to **David only**.

## Layout

    docs/process/   pipeline definition, idea board, decision log
    docs/world/     world & region content
    docs/systems/   mechanical system specs (one file per pipeline card)

## Process quick reference

Ideas travel individually through: **Phase 0 Establish → Phase 1 Refine →
Phase 2 Validate → Greenlit** (feasibility failures return to Phase 0).
