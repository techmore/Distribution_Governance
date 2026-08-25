---
layout: default
title: Consortium Model
---

# Consortium Model

How a membership purchasing consortium actually works — mechanically, financially, and contractually — applied to local THCA hemp distribution.

---

## The Basic Mechanism

A purchasing consortium sits between many small buyers and their suppliers. It does **not** buy and resell inventory (in its purest form). It aggregates *commitments* and negotiates contracts that members purchase under directly.

```
  40 member retailers          THE CONSORTIUM              3-5 distributors/brands
  ───────────────────         ────────────────            ──────────────────────
  Each commits monthly   →    Negotiates master      →    One contract covering
  volume through the          contracts, sets tier        all committed volume,
  consortium contract         pricing, audits             bulk-tier pricing,
                              compliance                  one invoice stream
```

Members still order individually, receive individually, and pay individually. What changes is the **price sheet they order against** and the **contract that stands behind it**. This is the model used by virtually every successful GPO: as the [Healthcare Supply Chain Association puts it](https://supplychainassociation.org/about-us/faq/), "GPOs do not purchase or buy any products. They negotiate contracts that hospitals can use when making their own purchases."

### Why Distributors Say Yes

The distributor's benefit is the half of the bargain people forget:

| Without consortium | With consortium |
|---|---|
| 40 small accounts at ~$2K/month | 1 wholesale-tier account at ~$80K/month |
| 40 onboarding, credit checks, sales touches | 1 onboarding, 1 relationship manager |
| Erratic ordering; churn when a cheaper vendor appears | Contracted volume with term commitments |
| High cost-to-serve per revenue dollar | Cost-to-serve amortized across pooled volume |
| Price-shopping pressure on every transaction | Price stability in exchange for reliability |

A distributor will trade margin for predictability. Fewer customers to manage at higher aggregate volume is a genuinely better business for them — this is the core insight that makes consortiums viable rather than parasitic.

### Why Members Join

**Bulk pricing without bulk quantities.** A single smoke shop can't hit Tier 3 wholesale pricing alone. Forty of them together can. The member buys their usual twelve units; the contract price reflects eighty thousand dollars a month.

Additional member benefits observed across every industry studied:

- **Price stability** — contracted terms hold for the agreement period instead of repricing weekly
- **Administrative relief** — no need for each shop to source and vet vendors
- **Quality assurance** — the consortium vets suppliers once (COAs, licensing, compliance) instead of each member doing it badly or not at all
- **Rebates** — manufacturer rebate programs collected collectively and passed through quarterly (the Dining Alliance model)
- **Market intelligence** — aggregated pricing data shows members what fair market actually looks like

---

## Membership Structure

### Tiers

Volume-based tiers create the incentive to route purchases through the consortium:

| Tier | Qualification | Pricing | Governance weight |
|------|--------------|---------|-------------------|
| Member | Signed agreement + modest annual dues | Standard consortium contract pricing | 1 vote |
| Committed Member | Quarterly minimum volume commitment | Deeper negotiated tiers | 1 vote + priority allocation on scarce product |
| Founding Member | Initial capital contribution / launch risk | Best available terms, locked longest | Board seat eligibility |

Tiering matters because distributors price off *committed* volume. A promise isn't a commitment; a signed quarterly minimum is. The gap between "Member" and "Committed Member" pricing is itself a recruiting tool.

### Dues and Revenue

The consortium entity needs operating revenue to negotiate, audit, and administer. Historical models, in rough order of preference for our context:

1. **Vendor administrative fees** (the healthcare GPO standard): vendors pay a fee of roughly 1–3% of purchases made under consortium contracts (GAO's finding was 1.22–2.25% weighted average). Members pay nothing upfront; the model scales automatically with volume. *Requires transparency covenants with members.*
2. **Flat membership dues**: predictable, simple, but a hurdle for recruiting small shops.
3. **Hybrid**: low nominal dues (filter for seriousness) + admin fees above a disclosed cap.
4. **Rebate share**: consortium collects manufacturer rebates, retains an administration slice, passes the rest through quarterly (Dining Alliance keeps "a small portion" of rebates it collects on behalf of restaurants).

### What Members Sign

At minimum, a membership agreement covering:

- Term and renewal; voluntary exit and notice period
- Commitment level (or explicitly none, for basic tier) and true-up mechanics
- Agreement to purchase covered categories through consortium contracts (with an explicit off-contract allowance — forcing 100% compliance breeds resentment; healthcare GPOs are entirely voluntary)
- Confidentiality of negotiated pricing
- Dispute resolution
- Governance: voting, meetings, amendment procedures

---

## Operations

### The Negotiation Cycle

1. **Aggregate demand data** — members report (or the platform tracks) category-level demand
2. **RFQ to qualified vendors** — competitive bidding across distributors and brands
3. **Committee review** — a product committee of member representatives evaluates price, quality, COAs, reliability (mirrors healthcare GPO clinical committees)
4. **Award contracts** — fixed terms, typically 6–12 months in a volatile market
5. **Publish price sheets** — members order against them
6. **Audit compliance** — verify vendors honor contract pricing and members receive it (purchase-data reconciliation)

### The First RFQ: What "Good" Looks Like

The pilot RFQ is the project's cheapest kill-switch (~$10K in). Structure it to maximize information:

1. **Pick one category** — flower is the leading candidate: commodity-like, widest wholesale price dispersion, so consortium leverage shows up fastest and most measurably
2. **Baseline first:** document 10+ members' actual recent purchase prices (invoices, not quotes) before any vendor talks. Without a real baseline you can't prove savings later — this is the audit foundation
3. **Bid at least three vendors** with a standardized bid sheet: price/lb by grade band, payment terms, COA policy, batch-failure recourse, delivery terms
4. **Score on total landed cost**, not headline price — a $700/lb vendor with net-15 terms may beat $680/lb on net-30 for cash-tight shops
5. **Award 6 months maximum** in year one. The market reprices faster than annual contracts; don't lock into yesterday's pricing
6. **Publish the results to all bidding vendors** (aggregate win/loss summary) — keeps losers in the game for round two and signals professionalism

### Negotiating Posture With Distributors

- Lead with the aggregate number and the commitment quality, not the discount ask: "$40K/month committed quarterly" opens doors that "what discount do we get?" doesn't
- Ask for **retroactive tier ladders** (see [precedents mechanism detail]({{ '/case-studies' | relative_url }})) rather than maximum upfront depth — vendors accept contingent discounts more readily than flat ones
- Trade data for price: monthly aggregate share-of-wallet reporting is worth basis points; individual member data is never traded
- Keep two vendors warm per category even after awarding one — the credible alternative is the whole negotiation

### Vendor Vetting (Category-Specific)

For THCA hemp products specifically, vetting is not optional window-dressing — it is a core member-protection service:

- Current Certificates of Analysis from DEA-registered labs (delta-9 ≤0.3% dry weight, contaminant panels)
- Hemp producer/processor licensure verification
- Product liability insurance requirements
- Recourse terms for failed or non-compliant batches

In a market full of fly-by-night processors, "we only contract with vetted suppliers" is arguably the consortium's second-biggest value proposition after price.

### Reconciliation Mechanics (the core operational discipline)

The monthly reconciliation loop is what separates a consortium from a spreadsheet — it's the enforcement layer. Concretely:

1. **Data acquisition:** each contracted distributor sends a line-item purchase report per member account (make this a contract deliverable, not a favor). Format: member ID, date, SKU, quantity, unit price paid.
2. **Price audit:** script compares every line against the contract price sheet. Exceptions (price above contract) go to the vendor for credit memo within 15 days — automatic, not adversarial.
3. **Spend-through tracking:** each Committed-tier member's quarter-to-date total vs their minimum; shortfall notices at week 10 of 13, not after quarter close.
4. **Rebate accrual:** manufacturer-eligible lines accumulate to a quarterly payout file; ACH batch with per-member statements.
5. **Exception log:** every dispute, credit, and shortfall recorded. This log is also the bank-compliance artifact and the annual savings-statement source.

At 30 members × ~4 orders/month this is roughly 150–200 lines/month — genuinely spreadsheet-scale for one part-time administrator with a simple script. The GPO-platform decision can safely wait until volumes triple.

### Compliance Calendar

| Cadence | Item |
|---|---|
| Monthly | Price reconciliation; vendor COA spot-check on new batches |
| Quarterly | Member savings statements; spend-through report; board meeting |
| Semi-annual | Vendor licensure + insurance re-verification |
| Annual | Independent savings audit; antitrust counsel review; fee disclosure statement to all members; policy re-adoption |

### Failure Modes to Design Against

Covered exhaustively on the [trade-offs page]({{ '/strengths-weaknesses' | relative_url }}), but named here because they should shape the operating design: free-riding (members taking negotiated prices while buying elsewhere), vendor capture (consortium favoring vendors who pay the biggest admin fees), antitrust exposure (agreed purchasing conduct must stay on the right side of group-purchasing law), and governance drift (the entity serving insiders instead of members).
