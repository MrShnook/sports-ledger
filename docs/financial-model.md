# Financial Model — SportsLedger

**Created:** 2026-03-24
**Last updated:** 2026-03-24

---

## Pricing Tiers

| Tier | Price | Key Features | Target |
|------|-------|-------------|--------|
| **Free** | $0 | 1 child, 1 sport, manual entry, basic dashboard, annual totals | Try-before-buy, rec parents |
| **Pro** | $4.99/mo ($49.99/yr) | Multi-child, multi-sport, receipt scanning, benchmarks, tax export, budget alerts | Travel/club families (primary target) |
| **Family** | $9.99/mo ($99.99/yr) | Everything + family sharing (co-parent access), historical trends, season forecasting, budget coaching insights | Multi-sport families, high spenders |

**Annual discount:** ~17% off monthly (2 months free)

---

## Unit Economics

### Per-User Costs (Estimated)

| Cost Category | Monthly Per User |
|---------------|-----------------|
| Hosting (Vercel + Supabase) | $0.10-$0.50 |
| Receipt scanning AI (GPT-4o mini) | $0.05-$0.20 (per scan, ~10 scans/mo) |
| Email (transactional) | $0.01 |
| Payment processing (Stripe 2.9% + $0.30) | $0.45 (on $5 plan) |
| **Total COGS per paid user** | **~$0.60-$1.15/mo** |

### Contribution Margin

| Tier | Revenue | COGS | Contribution | Margin |
|------|---------|------|-------------|--------|
| Pro (monthly) | $4.99 | $1.00 | $3.99 | 80% |
| Pro (annual) | $4.17/mo | $1.00 | $3.17 | 76% |
| Family (monthly) | $9.99 | $1.15 | $8.84 | 88% |
| Family (annual) | $8.33/mo | $1.15 | $7.18 | 86% |

**Blended target margin: 80%+** (SaaS healthy)

---

## Revenue Projections

### Scenario A: Organic Growth (Content + SEO + Reddit)

| Quarter | Free Users | Paid Users | MRR | ARR |
|---------|-----------|-----------|-----|-----|
| Q3 2026 (launch) | 500 | 25 | $150 | $1,800 |
| Q4 2026 | 2,000 | 100 | $600 | $7,200 |
| Q1 2027 | 5,000 | 300 | $1,800 | $21,600 |
| Q2 2027 | 10,000 | 600 | $3,600 | $43,200 |
| Q4 2027 | 25,000 | 1,500 | $9,000 | $108,000 |
| Q4 2028 | 75,000 | 5,000 | $30,000 | $360,000 |

**Assumptions:**
- 5-7% free-to-paid conversion
- 60% Pro / 40% Family split
- 3% monthly churn (paid)
- $0 paid acquisition (organic only)

### Scenario B: Accelerated (Content + Paid Ads + Partnerships)

| Quarter | Free Users | Paid Users | MRR | ARR |
|---------|-----------|-----------|-----|-----|
| Q3 2026 | 1,000 | 50 | $300 | $3,600 |
| Q4 2026 | 5,000 | 300 | $1,800 | $21,600 |
| Q1 2027 | 15,000 | 1,000 | $6,000 | $72,000 |
| Q2 2027 | 30,000 | 2,000 | $12,000 | $144,000 |
| Q4 2027 | 75,000 | 5,000 | $30,000 | $360,000 |
| Q4 2028 | 200,000 | 15,000 | $100,000 | $1,200,000 |

**Additional assumptions (Scenario B):**
- $500-$1,000/mo ad spend starting Q4 2026
- Partnership with 2-3 youth sports orgs/blogs
- CAC target: $5-10 per free user, $50-75 per paid user

---

## Break-Even Analysis

### Fixed Monthly Costs (Lean Operation)

| Category | Monthly Cost |
|----------|-------------|
| Vercel Pro | $20 |
| Supabase Pro | $25 |
| Domain + DNS | $2 |
| AI APIs (receipt scanning) | Variable (in COGS) |
| Email service (Resend) | $0 (free tier to 3K/mo) |
| **Total fixed** | **~$47/mo** |

### Break-Even
- At $4.99/mo avg: **10 paying users** covers fixed costs
- At $6/mo blended avg: **~200 paying users** = $1,200 MRR (comfortable self-sustaining)
- At 1,000 paying users: **$6,000 MRR** (meaningful side income)

**Time to break-even:** Month 2-3 post-launch (extremely low fixed costs)

---

## Key Metrics to Track

| Metric | Target | Why |
|--------|--------|-----|
| Free → Paid conversion | >5% | Validates value proposition |
| Monthly churn (paid) | <5% | Seasonal risk — may spike off-season |
| ARPU (paid) | >$6/mo | Healthy blended rate |
| LTV | >$150 | 25+ months at $6/mo avg |
| CAC (organic) | <$5 | Content + SEO + community |
| LTV:CAC | >10:1 | Healthy SaaS ratio |
| NPS | >40 | Word-of-mouth growth engine |
| Receipts scanned/user/mo | >5 | Engagement/stickiness metric |

---

## Seasonal Considerations

Youth sports spending is **cyclical:**
- **August-October:** Peak registration (fall sports start). Best acquisition window.
- **January-February:** Spring season signups. Second acquisition window.
- **June-July:** Camp season + fall tryout anxiety. Content marketing peak.
- **November-December:** Off-season for many sports. Tax prep messaging opportunity.
- **April (tax season):** "How much did you spend?" awareness moment.

**Churn risk:** Off-season months (Dec-Jan for fall sports). Mitigation: multi-sport families are always in-season; historical data review features keep users engaged.

---

## Revenue Milestones

| Milestone | Paid Users | MRR | Meaning |
|-----------|-----------|-----|---------|
| Ramen profitable | 10 | $60 | Covers hosting |
| Side hustle | 200 | $1,200 | Meaningful monthly income |
| Part-time income | 1,000 | $6,000 | Could reduce day job hours |
| Real business | 5,000 | $30,000 | Full-time viable |
| Scale candidate | 20,000 | $120,000 | Raise funding or stay bootstrapped |

---

*Model is conservative. Based on $0 upfront investment (we have the tech stack). Primary risk is distribution, not economics.*
