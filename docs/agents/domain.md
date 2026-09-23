# Domain docs

This repository uses a single-context layout:

- `CONTEXT.md` at the repository root: domain vocabulary.
- `docs/adr/`: architecture decision records.

## Before exploring

Read `CONTEXT.md` and ADRs relevant to the area being explored.

If these documents do not exist, proceed silently. The domain-modeling
skill creates them lazily when terms or decisions are resolved.

## Use the domain vocabulary

Use the terms defined in `CONTEXT.md` in issue titles, proposals,
hypotheses, and tests. Respect any explicitly discouraged synonyms.

If a needed concept is missing, reconsider the wording or note the
gap for domain-modeling.

## Surface ADR conflicts

Explicitly identify any existing ADR that a proposal contradicts,
and explain why reopening the decision may be warranted.
