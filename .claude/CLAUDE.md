# Recipulate — Landing Page

> **Type**: Public landing page (https://recipulate.org)
> **Real project**: `roar-gits/recipulate` (private). All product work happens there.

This working directory is a **presentation artifact**, not a project. It hosts only the public-facing description of "recipulate." Edits are limited to landing-page content, design tokens, and deploy config.

For project-level work (architecture, initiatives, integrations, users, doctrine sweeps), switch to `roar-gits/recipulate`. Do **not** rebuild `.claude/docs/` infrastructure here.

See also `.project-meta` at the working-dir root.

---

## Stack

Static HTML (no build step) → GitHub Pages via GitHub Actions on push to `main`.

## Deploy

Automatic on push to `main` via `.github/workflows/deploy.yml`.

## Credentials

Handled by `.envrc` + global doctrine — no project-level setup needed.

**Landing-page repo ≠ coming-soon page**: this repo IS the deliverable (a profile-pinnable public artifact); real product work happens at the `real_project:` path in `.project-meta`. A *coming-soon page* is a route inside an actual product project — do not apply landing-page shortcuts there. (Rehomed from global CLAUDE.md V13, 2026-07-15.)
