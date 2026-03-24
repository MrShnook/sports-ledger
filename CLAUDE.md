# SportsLedger

Expense tracker and financial planner for youth sports families — track fees, travel, equipment, budgets, tax deductions.

## Project Structure

- `docs/context.md` — Venture strategy and positioning
- `docs/design/design-brief.md` — Visual direction and mood
- `docs/design/design-system.md` — Design tokens (colors, fonts, spacing)
- `docs/research/` — Market research, competitive landscape, Reddit validation
- `docs/sprints/` — Sprint specs for complex builds

## Target Audience

Youth sports parents (30-50), mobile-first. Must feel trustworthy and approachable, NOT "corporate finance app." Think: the parent app you'd show your spouse at the kitchen table.

## MVP Features

1. Onboarding: pick sport(s), child name(s), season dates
2. Manual expense entry with pre-built sport categories
3. Dashboard: total spend, by-category breakdown, by-child breakdown
4. Season-to-date vs budget comparison
5. Basic CSV export

## Conventions

- Next.js App Router + TypeScript + Tailwind CSS
- Supabase for auth + database
- Follow design-system.md tokens exactly — no default Tailwind colors
- Mobile-first responsive design
- Commit messages: conventional commits (feat:, fix:, docs:, etc.)

## Before You Start

1. Read `docs/design/design-system.md` for exact tokens
2. Read the relevant sprint spec in `docs/sprints/` if working a sprint
3. Run `npm run build` before committing
