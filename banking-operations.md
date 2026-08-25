---
layout: default
title: Banking & Operations
---

# Banking & Operations Reality Check

The unglamorous constraint that can kill this project before any contract is signed: finding a financial institution that will bank a consortium whose purpose is aggregating purchases of intoxicating hemp products. Plus the operational stack needed to run the thing.

---

## The Banking Problem

### Why it's hard

- Hemp is federally legal under the 2018 Farm Bill, but *intoxicating* hemp products (THCA flower, hemp-derived THC) sit in a contested zone: federally compliant on paper (≤0.3% delta-9 dry weight), yet treated with suspicion by risk-averse compliance departments because several states restrict them and Congress has repeatedly moved to close the "loophole"
- Banks and credit unions serving cannabis-adjacent businesses operate under heavy BSA/AML scrutiny; each institution writes its own hemp/CRB (cannabis-related business) policy, and many draw the line at "ingestible intoxicating hemp"
- An LLC named to run THCA purchasing aggregation will be classified as a CRB or hemp business by most onboarding questionnaires regardless of its nonprofit aspirations

### What exists today

| Type | Examples | Notes |
|---|---|---|
| CRB-focused credit unions | [First Commonwealth FCU](https://www.firstcomcu.org/cannabisbanking.html) (PA/NJ region) | Explicitly serves CBD/hemp wholesalers in PA & NJ; NCUA-insured |
| Regional CRB programs | [Affinity FCU](https://www.affinityfcu.com/business-banking/cannabis-banking) (NJ-based) | Dedicated Cannabis-Related Business banking program |
| State directories | [NY Cannabis Banking Directory](https://cannabis.ny.gov/banking-directory) incl. Jonestown Bank & Trust (PA-chartered), Suffolk CU | Directory of self-identified hemp-friendly institutions |
| Hemp-friendly national banks | Stearns Bank, Dart Bank | Appear in state banking directories for hemp businesses |

Since NCUA cleared federally insured credit unions to serve legal hemp businesses (2019), credit unions — not mega-banks — have been the practical entry point.

### Working plan

1. **Interview 3–4 institutions** (First Commonwealth FCU and Affinity FCU first — both explicitly cover PA/NJ hemp wholesalers) *before* finalizing entity paperwork; ask specifically whether they'll bank an organization whose revenue derives from negotiating contracts for THCA product purchases, vs only CBD
2. Expect enhanced due diligence: beneficial-owner disclosures, source-of-funds documentation, member-vendor contract review, possibly higher fees and more frequent reviews than a vanilla business account
3. **Have a fallback posture:** the entity can be capitalized and hold contracts even if payment processing for members routes vendor-direct (members pay distributors directly under consortium pricing; the organization touches only fees/rebates). This dramatically shrinks the CRB footprint of the organization itself — worth structuring toward deliberately
4. Payment processing for any consumer-facing component (dues portals etc.) is a separate, harder problem — keep dues collection via ACH/invoice, not card processors

---

## Operational Stack

What actually has to run, week to week:

### Core functions

| Function | What it involves | Tool class |
|---|---|---|
| Purchase data reconciliation | Match member invoices against contract pricing monthly; audit drift | Shared inbox + spreadsheet initially → dedicated GPO platform later |
| Vendor management | Contracts, COAs library, licensure verification, insurance certs, renewal calendar | Document repository w/ expiration alerts |
| Member administration | Onboarding, agreements, tier tracking, dues invoicing, quarterly rebate payouts | CRM + ACH batch (or GPO SaaS) |
| RFQ / negotiation support | Demand aggregation surveys, bid tabulation, award memos | Structured templates; committee minutes |
| Compliance file | Per-contract compliance binder (COAs, chain-of-custody, state law matrix) | This is also what keeps the bank comfortable |

### Build vs buy

GPO administration platforms exist (used by restaurant and healthcare buying groups) at roughly $500–2K/mo. **Do not start there.** The historical pattern from the [precedents page]({{ '/case-studies' | relative_url }}): every long-lived GPO started with manual reconciliation and graduated to systems once volume justified it. Launch stack: one part-time administrator, shared drive with strict document controls, quarterly reconciliation cadence.

### Staffing model at launch

- **Administrator (part-time):** reconciliation, vendor docs, member onboarding — the single most important early hire; the [spreadsheet failure analysis]({{ '/strengths-weaknesses' | relative_url }}) is fundamentally about what happens when nobody holds this role
- **Negotiation lead:** a founding partner, with documented authority limits from the board
- **Counsel:** nonprofit/business counsel for formation + annual antitrust review ([entity page]({{ '/entity-structure' | relative_url }})); budget ~$5–10K/yr initially

---

## Sequenced Roadmap

| Phase | Milestone | Exit criteria |
|---|---|---|
| 0. Banking first | 3+ institution interviews; account open | Banked entity that accepts our category description |
| 1. Entity | Form [LLC], adopt conflict/antitrust policies, membership agreement v1 drafted ([skeleton]({{ '/membership-agreement' | relative_url }})) | Counsel sign-off |
| 2. Seed members | 10–12 LOIs from shops (Founding + Committed tiers) | ≥$25K/mo committed demand documented |
| 3. First RFQ | Pilot category (flower OR vapes — not all at once), 3+ bids, award 6-mo contract | Real savings % measured vs street baseline — validates/falsifies the [financial model]({{ '/financial-model' | relative_url }}) |
| 4. Reconcile & report | First quarter of purchase-data audit; per-member savings statements | Proof of enforcement — the thing a spreadsheet cannot do |
| 5. Expand | Second category, rebate program conversations with manufacturers, recruit toward 30 shops | Admin fee income trending to breakeven per model sensitivity table |
| 6. Institutionalize | Convert/parallel-form as 501(c)(6) or cooperative; elected board seats filled | Entity no longer dependent on founders personally |

---

## Open Questions

- Will First Commonwealth/Affinity underwrite a *THCA* (vs CBD-only) purchasing organization? Determines whether the vendor-direct payment structure is optional or mandatory
- Which pilot category has the most price dispersion? (Flower likely — commodity-like, wide wholesale spread — making consortium leverage most visible fastest)
- Does NJ require anything specific of a buying organization operating across state lines? **[COUNSEL]**
