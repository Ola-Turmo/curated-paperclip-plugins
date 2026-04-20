---
name: portfolio-repo-universe
description: Use for Parallel Company AI work when deciding which Paperclip repos, plugins, tools, and overlays belong in a company, how to compose them safely, which ones are live versus reference-only, and how to turn the repo universe into a governed operating system instead of a random plugin pile.
---

# Portfolio Repo Universe

Use this skill for portfolio-level repo selection and company composition work.

## Read First

Read:

1. `README.md`

## What This Repo Owns

This repo is the curated universe of Paperclip-related building blocks:

- core control-plane repos
- plugin layer
- department overlays
- personal overlays
- tools and execution surfaces
- observability and integration bridges

## Working Rules

- Use the whole repo universe deliberately, not indiscriminately.
- Prefer one governed control plane with company boundaries over duplicated installs.
- Separate `live now`, `fix first`, and `reference only`.
- Treat repo selection as architecture, not shopping.

## Default Workflow

1. Start from the company mission and operating loop.
2. Choose the smallest repo set that gives the company real leverage.
3. Distinguish platform layer, operator layer, execution layer, and company/domain layer.
4. Avoid mirroring every repo into every company unless the use case actually needs it.
5. Preserve company boundaries and approval discipline.

## Expected Outcomes

Good work with this repo should leave:

- cleaner company composition
- fewer accidental dependencies
- better plugin activation order
- a more reusable portfolio operating system
