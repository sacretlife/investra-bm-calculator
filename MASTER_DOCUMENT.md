# Investra Business Model Calculator — Master Document
**Version:** 1.0 | **Last Updated:** 2026-07-19 | **Status:** In Review

---

## 1. SYSTEM OVERVIEW

The Investra Business Model Calculator is an interactive HTML/JS web application that allows Investra HQ, Master Franchises (MF), and Standard Franchises (F) to dynamically model financial projections. All parameters are adjustable in real time, and all calculations update automatically.

### Access Levels
| Level | Access | Login |
|---|---|---|
| Admin (Investra HQ) | Full access — all settings, all countries, all projections | Password: `InvestraHQ2026` |
| Master Franchise (MF) | Own country only — projections, partner stats | Password: `InvestraMF2026` |
| Standard Franchise (F) | Own region/city only — projections, partner stats | Password: `InvestraF2026` |
| Public Partner Link | MF or F candidate — selects country/region, views own projection | No password (public) |

### Languages
- English (default)
- Slovenščina
- Hrvatski
- Srpski
- Bosanski

---

## 2. REVENUE MODEL — 3 OPTIONS (All in Preview)

> **Status:** All 3 models are available as preview. Admin selects active model in settings.

### Model A — Flat Royalty
Simple fixed percentages. Best for Phase 1 markets and first-time partners.

**Transaction Royalty (from GMV):**
- Investra HQ: **2%**
- Master Franchise: **1.5%**
- Standard Franchise: **1%**
- Total pool: **4.5%**

**Licence Sales Cascade (who sold = who earns):**
| Scenario | HQ | MF | F | Referral |
|---|---|---|---|---|
| MF sells directly | 70% | 15% | — | — |
| F sells (under MF) | 70% | 5% | 10% | — |
| Referral brings lead | 65% | 5% | 10% | 5% (one-time) |
| MF recruits new MF/F | 85% | 15% | — | — |

**Advertising, Events, Marketing:**
| Type | MF | F | Referral |
|---|---|---|---|
| Advertising Credits | 15% | 10% | 3% |
| Event Tickets | 15% | 10% | 5% |
| Marketing / PR | 15% | 10% | 3% |
| Recruit new MF/F | 15% | — | — |

---

### Model B — Tiered Royalty ⭐ (Recommended)
Performance-based. Higher % for better performers. Motivates growth.

**Transaction Royalty — Tiered by Annual GMV:**
| GMV Tier | HQ | MF | F | Total |
|---|---|---|---|---|
| Under €1M | 2% | 1% | 0.5% | 3.5% |
| €1M – €5M | 2% | 1.5% | 1% | 4.5% |
| €5M – €20M | 2% | 2% | 1.5% | 5.5% |
| Over €20M | 2% | 2.5% | 2% | 6.5% |

**Licence Sales — Tiered by Active Licences:**
| Active Licences | MF % | F % | Referral % |
|---|---|---|---|
| Under 50 | 15% | 8% | 5% |
| 50 – 100 | 18% | 10% | 5% |
| Over 100 | 20% | 12% | 5% |

**Advertising, Events, Marketing:**
| Type | MF | F | Referral |
|---|---|---|---|
| Advertising Credits | 15–20% | 8–12% | 3–5% |
| Event Tickets | 10–15% | 5–10% | 5% |
| Marketing / PR | 10–15% | 5–10% | 3% |
| Recruit new MF/F | 15% + 5% recurring | — | — |

---

### Model C — Split Pool
Every euro split by fixed pool ratio. Maximum transparency. Best for investors.

**Transaction Royalty — Pool Split (Total: 5% of GMV):**
| Level | Pool Share | = % of GMV |
|---|---|---|
| Investra HQ | 40% | 2% |
| Master Franchise | 30% | 1.5% |
| Standard Franchise | 20% | 1% |
| Referral | 10% | 0.5% |

**Licence Revenue Pool:**
| Level | Pool Share |
|---|---|
| HQ | 60% |
| MF | 20% |
| F | 12% |
| Referral | 8% |

**Advertising & Events Pool:**
| Type | HQ | MF | F | Referral |
|---|---|---|---|---|
| Advertising Credits | 55% | 20% | 15% | 10% |
| Event Tickets | 50% | 25% | 15% | 10% |
| Marketing / PR | 55% | 20% | 15% | 10% |
| Recruit new MF/F | 85% | 15% | — | — |

---

## 3. PACKAGE PRICING (All Adjustable in Admin)

### User / Client Packages
| Package | Price | Includes |
|---|---|---|
| Free | €0/mo | Browse listings, save favourites |
| VIP | €50/mo | Priority alerts, AI match, exclusive listings |

### Agent Packages
| Package | Price | Includes |
|---|---|---|
| Starter (P1) | €49/mo | CRM, listings, commission tracker |
| Pro (P2) | €99/mo | + AI tools, cross-listing, analytics |
| Elite (P3) | €199/mo | + White-label, academy, priority support |

### Agency Packages
| Package | Price | Includes |
|---|---|---|
| Team (P1) | €199/mo | Up to 10 agents, basic white-label |
| Network (P2) | €399/mo | Up to 50 agents, full white-label |
| Enterprise (P3) | €599/mo | Unlimited agents, custom domain, API |

### Developer Packages
| Package | Price | Includes |
|---|---|---|
| Starter (P1) | €299/mo | 1 project, basic inventory sync |
| Professional (P2) | €599/mo | 5 projects, smart contract escrow |
| Enterprise (P3) | €999/mo | Unlimited, investor reporting, API |

### Affiliate Packages
| Package | Price | Commission | Includes |
|---|---|---|---|
| Starter (P1) | €0/mo | 5% per referral | Basic referral link |
| Pro (P2) | €29/mo | 10% per referral | + Advertising credits |
| Elite (P3) | €79/mo | 15% per referral | + Priority support + credits |

---

## 4. CREDIT SYSTEM

### Credit Value
- **1 Credit = €0.10** (default, adjustable in Admin)
- Display: always show both credits AND euro equivalent

### Credit Types
| Type | Validity | Source |
|---|---|---|
| Purchased Credits | 12 months (adjustable) | Bought by user |
| Promotional Credits | Custom (e.g. 30/60/90 days, adjustable) | Marketing campaigns |

### Credit Packages (Adjustable prices and discount %)
| Package | Credits | Price (€) | Discount | Value |
|---|---|---|---|---|
| Starter | 500 | €45 | 10% | €50 value |
| Pro | 1,500 | €120 | 20% | €150 value |
| Business | 5,000 | €350 | 30% | €500 value |
| Enterprise | 15,000 | €900 | 40% | €1,500 value |
| Custom | User enters amount | Auto-calculated | Tiered auto-discount | Auto-calculated |

**Custom Package Logic:**
- €0 – €99: 0% discount
- €100 – €499: 10% discount
- €500 – €999: 20% discount
- €1,000 – €4,999: 30% discount
- €5,000+: 40% discount

---

## 5. ADVERTISING SERVICES — MULTI-COUNTRY PRICING

> All prices in EUR and credits (dual display). Admin can add new services.
> **Global multiplier** sets base price; country multipliers auto-adjust all country prices.

### Default Service Prices (EUR/month)
| Service | Global | Slovenia | Croatia | Serbia | BiH | TRNC | Turkey |
|---|---|---|---|---|---|---|---|
| Top Developer | €599 | €299 | €349 | €399 | €249 | €279 | €449 |
| Top Project | €399 | €199 | €229 | €249 | €149 | €179 | €299 |
| Top Agency | €499 | €249 | €279 | €299 | €199 | €229 | €379 |
| Top Agent | €199 | €99 | €109 | €119 | €79 | €89 | €149 |
| Top Property | €149 | €79 | €89 | €99 | €59 | €69 | €119 |
| Top Article | €99 | €49 | €55 | €59 | €39 | €45 | €79 |

### Country Multipliers (adjustable in Admin)
| Country | Multiplier |
|---|---|
| Global | 1.00 (base) |
| Slovenia | 0.50 |
| Croatia | 0.58 |
| Serbia | 0.67 |
| BiH | 0.42 |
| TRNC | 0.47 |
| Turkey | 0.75 |

> When Admin changes Global price, all country prices auto-update using multiplier.
> Admin can override individual country prices independently.

---

## 6. MASTER FRANCHISE PRICING (by Country Population)

| Tier | Population | Annual Fee | Monthly Fee |
|---|---|---|---|
| Micro | < 1M | €25,000 | €1,500 |
| Small | 1M – 3M | €50,000 | €2,000 |
| Medium-S | 3M – 7M | €75,000 | €2,500 |
| Medium-L | 7M – 15M | €120,000 | €2,500 |
| Large | 15M – 40M | €180,000 | €3,500 |
| Premium | 40M – 80M | €280,000 | €5,000 |
| Mega | > 80M | €400,000 | €5,000 |

---

## 7. STANDARD FRANCHISE PRICING (by GDP/capita Tier)

| Tier | GDP/capita | Examples | Setup Fee | Monthly SaaS |
|---|---|---|---|---|
| Tier A | < €10k | BiH, Serbia | €2,900 | €249/mo |
| Tier B | €10k–€20k | TRNC | €3,900 | €349/mo |
| Tier C | €20k–€35k | Slovenia, Croatia, Spain | €4,900 | €449/mo |
| Tier D | €35k–€60k | Germany, UK | €5,900 | €549/mo |
| Tier E | > €60k | Switzerland, Qatar | €7,900 | €699/mo |

---

## 8. FINANCIAL PROJECTION INPUTS

| Parameter | Default Value | Adjustable |
|---|---|---|
| Average property value | €250,000 | ✅ |
| Agency commission % | 2% | ✅ |
| Number of agents | 50 | ✅ |
| Number of agencies | 5 | ✅ |
| Number of developers | 2 | ✅ |
| Number of clients | 100 | ✅ |
| Monthly transactions | 10 | ✅ |
| Annual GMV growth rate | 20% | ✅ |

### Projection Timeframes
- Monthly (12 months)
- Annual (3 years)
- Annual (5 years)

### Output Views
- Revenue breakdown by level (HQ / MF / F)
- Net profit (revenue minus costs)
- Charts: Bar (monthly), Line (annual trend), Pie (revenue split)

---

## 9. CHANGE LOG

| Date | Version | Change | Author |
|---|---|---|---|
| 2026-07-19 | 1.0 | Initial Master Document created | Manus AI |

---

*This document is the single source of truth for the Investra Business Model Calculator. All changes must be logged in Section 9.*
