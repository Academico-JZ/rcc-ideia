# Domain Documentation

## Layout

This repository uses a single-context documentation layout:

- `CONTEXT.md` at the repository root for domain context shared across the project.
- `docs/adr/` for architecture decision records.

## Consumer Rules

- Read `CONTEXT.md` before making product or architecture decisions that depend on domain rules.
- Read relevant files under `docs/adr/` before changing an established architectural decision.
- Keep domain terminology, constraints, and invariants in `CONTEXT.md` rather than duplicating them in feature notes.
- Record significant architectural choices as ADRs under `docs/adr/`.
