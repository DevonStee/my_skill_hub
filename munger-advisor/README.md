# Munger Advisor Skill Package

This directory contains a long-lived skill package for Munger-shaped decision support.

## Purpose

The goal is not to imitate Charlie Munger’s voice. The goal is to preserve a durable judgment style:

- avoid stupidity first
- inspect incentives before trusting intentions
- compare against the best alternative, including doing nothing
- protect survival before optimizing upside
- prefer quality that compounds over fragile cheapness

## Package Layout

- `SKILL.md` — root entrypoint; discovery, activation, identity, invariants
- `core/` — highest-level defaults
- `modules/` — adaptive protocol pieces that can evolve independently
- `references/` — model libraries by domain
- `references/charlie-munger-lecture.md` — long-form primary-source reference for Munger’s own explanations and emphases
- `support/` — optional aids, examples, and pressure tests

## Recommended Use

Start with `SKILL.md`, then load only the files that materially improve the judgment.

A common pattern is:

- `core/munger-principles.md`
- one helpful module
- one helpful domain reference

Use `references/charlie-munger-lecture.md` selectively as a primary-source supplement, not as the default first read.

## Design Principles

- **Identity-first** — preserve judgment defaults more than exact wording
- **Invariant-driven** — protect the core rules even if the protocol evolves
- **Intent-first** — express what the skill should accomplish, not a brittle sequence
- **Adaptive depth** — use more or less structure based on stakes and uncertainty
- **Modular growth** — add capabilities as modules, not by bloating `SKILL.md`
- **No cosplay** — Munger defaults, not Munger mannerisms

## When Editing

- Keep `SKILL.md` short and durable
- Put new procedural detail in `modules/`
- Put new model content in `references/`
- Put examples and tests in `support/`
- Prefer clearer structure over more text
- If a section mainly patches a current-model weakness, simplify or delete it

## Anti-Goals

Do not turn this package into:

- a giant checklist
- a quote collection
- a roleplay prompt
- a generic “decision framework” with no personality

## Maintenance Rule

If a new addition does not make the skill more durable, more legible, or more Munger-like in judgment, it probably does not belong here.
