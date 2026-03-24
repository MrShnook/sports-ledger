# SportsLedger — Venture Context

## What It Is

Expense tracker and financial planner for youth sports families — track fees, travel, equipment, budgets, tax deductions. $4.99-9.99/mo.

## The Problem

Youth sports families spend $5,000–$25,000+ per child per year on club fees, tournaments, travel, equipment, and private training — and most have NO idea what they're actually spending. Costs have doubled in 5–10 years. Parents use spreadsheets (60–70%), generic budgeting apps like YNAB (20–30%), or literally nothing (10–20%). There is **no purpose-built expense tracker for youth sports families.**

The pain is visceral: Reddit threads with 500+ comments titled "Youth sports costing us $25k/year—worth it?" and "Travel sports expenses out of control." Parents report quitting entire programs when they finally add up the real numbers. Many describe "CC statement horror" at year-end when they see the totals for the first time.

## Who Has This Problem

**Primary:** Youth sports parents (ages 30-50) with kids in competitive/travel programs
- 16–24 million participating families in the US
- Average family: $1,700–$3,400/year (national average), but travel/competitive families: $8,000–$25,000+
- 10% of median household income goes to youth sports for active families
- Costs rising 8–10% CAGR — the problem is getting worse, not better

**Demographics:** Mostly dual-income households, suburban, kids aged 6-17. Highest spenders: hockey, travel baseball, competitive soccer (MLS Next/ECNL), competitive dance/gymnastics.

## Why We Noticed

Matt's son William is on MLS Next in Phoenix. We ARE the customer. First beta test = our own family's expenses. Authenticity and domain knowledge baked in.

## Market Signal

- **$40–54B total youth sports spending** in the US annually
- **Reddit pain validation:** Strong. r/Parenting, r/youthsports, r/hockeyparents have active threads about expense shock
- **No dedicated competitor exists.** TeamSnap tracks team-side fees. YNAB is generic budgeting. Nothing is purpose-built for the family side.
- Community advice: "Track early to negotiate or switch to rec" — our tool enables this

## Competitive Landscape

| Competitor | Price | What It Does | Gap |
|-----------|-------|-------------|-----|
| TeamSnap | $10-15/mo (team) | Team scheduling, fee collection | Team-side only. Parents see what they owe, not what they've spent. |
| SportsEngine | Free-$15/mo | Registration, scheduling | Organization-side, not family-side |
| YNAB | $14.99/mo | General budgeting | Not sport-specific. No categories for "tournament fees" vs "equipment." Manual setup. |
| Mint/Rocket Money | Free | Auto-categorize CC transactions | Sports expenses lumped under "Entertainment" or "Shopping." No granularity. |
| Spreadsheets | Free | Whatever parents build | Most popular but manual, no receipt scanning, no benchmarks, no forecasting |

**Nobody owns the family-side youth sports finance niche.**

## Our Angle — Killer Features

1. **Sport-specific categories** pre-built (club dues, tournament fees, travel, hotels, gas, equipment, uniforms, private training, camps)
2. **Multi-child / multi-sport** tracking with per-child totals
3. **"True Cost Calculator"** — before you commit to a team, estimate the real season cost (the feature parents actually NEED — "your club fee is $2,500 but the true annual cost is $12,000")
4. **Receipt scanning AI** — snap a photo, auto-categorize
5. **Benchmarks** — "families in Phoenix spend an average of $X on travel soccer" (crowdsourced over time = moat)
6. **Tax season export** — flag potential deductions, export-ready for accountants
7. **Budget alerts** — "you've spent $800 on tournaments this month, 40% over budget"
8. **Season forecasting** — project costs for upcoming season based on schedule

## Pricing Strategy

- **Free tier:** Basic tracking, 1 child, manual entry, annual totals
- **Pro ($4.99/mo / $49.99/yr):** Receipt scanning, multi-child, benchmarks, tax export, forecasting
- **Family ($9.99/mo / $99.99/yr):** Everything + family sharing, historical trends, budget coaching
- **Break-even:** ~200 paid subscribers at $5/mo = $1K MRR

## MVP Scope (Smallest Valuable Thing)

- Web app (Next.js, mobile-responsive)
- Onboarding: pick sport(s), child name(s), season dates
- Manual expense entry with pre-built sport categories
- Dashboard: total spend, by-category breakdown, by-child breakdown
- Season-to-date vs budget comparison
- Basic CSV export

**Build time:** 1–2 weeks for MVP
**Tech stack:** Next.js + Supabase + Vercel (our standard stack)

## Stage

**Current:** Researching (transitioned from idea 2026-03-19)
**Scout verdict:** 🟢 BUILD
**Scout brief:** `~/.openclaw/workspace/ventures/sports-ledger-scout-brief.md`

## Domain Expertise

Matt's son William plays on MLS Next in Phoenix. The family lives the youth sports expense problem daily. This is authentic.

---
*Last updated: 2026-03-24*
