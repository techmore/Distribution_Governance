---
layout: default
title: Legal Model
---

# Legal Model

This page connects the dots between entity choice and the real-world agreements that govern how four people work together. It covers the full stack: how to structure the LLC itself, and how to formalize the partnership among the four members through operating agreements, side letters, and equity mechanics.

---

## Part I: Entity Design

### Recommendation: Multi-Class LLC

A standard single-class LLC (where every member holds identical units) won't work well here. The four members contribute different things — capital, time, relationships, logistics — and need different economic and governance rights.

A **multi-class LLC** solves this by letting you create separate membership classes:

| Class | Holders | Economics | Voting |
|-------|---------|-----------|--------|
| **Class A (Capital)** | Partner 1 | Preferred return + residual | Major decisions only |
| **Class B (Operating)** | Partners 2–4 | Pro-rata profit share, vesting schedule | Day-to-day + major |
| **Class C (Promote)** | Allocated pool | Performance-based overrides | Non-voting |

### Manager-Managed vs. Member-Managed

| Structure | Best For | Downside |
|-----------|----------|----------|
| **Member-managed** | Small teams where everyone operates equally | Can create gridlock; every member binds the company |
| **Manager-managed** | Unequal involvement; investors vs. operators | Requires clear delegation in the OA |

**Recommendation:** Manager-managed. Designate Partner 1 and Partner 2 as co-managers with authority over their domains (finance and operations respectively). Major decisions (debt, new members, dissolution) require unanimous member consent.

---

## Membership Classes: A Practical Walkthrough

### Where Do Membership Classes Live?

**In the Operating Agreement, not the state filing.** Here's the split:

| Document | What it does | Filed with PA? |
|----------|-------------|----------------|
| **Articles of Organization** | Creates the LLC. Lists name, address, registered agent. That's it. | ✅ Yes (~$125) |
| **Operating Agreement** | Defines everything else: classes, voting, economics, transfer rules. | ❌ No — internal document |

The Articles of Organization for a multi-class LLC look identical to a single-class LLC. The state doesn't need to know about your class structure. All the detail — who gets what, how voting works, what happens on exit — lives in the Operating Agreement, which only the members sign.

### Concrete Example: How Classes Work with Real Numbers

Let's say the venture needs $200,000 to start. Partner 1 puts in $150,000. Partners 2, 3, and 4 each put in ~$16,667.

#### Step 1: Define the classes in the OA

```
Class A Units (Capital) — Issued to Partner 1
  - Entitled to 8% preferred return before any other distributions
  - 1 vote per unit on Major Decisions only
  - No management authority

Class B Units (Operating) — Issued to Partners 2, 3, 4
  - Entitled to pro-rata share of remaining profits
  - Full voting rights on ordinary and major decisions
  - Subject to 3-year vesting with 1-year cliff

Class C Units (Promote Pool) — Reserved (unissued)
  - 15% of profits after preferred return and capital return
  - Allocated annually by managers based on performance
  - Non-voting
```

#### Step 2: Initial ownership

| Member | Units | % | Capital | Class |
|--------|-------|---|---------|-------|
| Partner 1 | 150 | 45% | $150,000 | A |
| Partner 2 | 83 | 25% | $16,667 | B |
| Partner 3 | 67 | 20% | $16,667 | B |
| Partner 4 | 50 | 15% | $16,667 | B |

*Unit counts are proportional to capital here, but they don't have to be — you can issue units for sweat equity, IP, or relationships at a negotiated value.*

#### Step 3: The waterfall in action

Year 1 profit: **$100,000**. Here's how it flows:

| Tier | Calculation | Amount | Recipient |
|------|------------|--------|-----------|
| 1. Preferred return | 8% × $150,000 (A's capital) | $12,000 | Partner 1 only |
| 2. Return of capital | Pro rata to basis | $0 (retained) | All members |
| 3. Promote | 15% × remaining $88,000 | $13,200 | Allocated by managers |
| 4. Residual | Remaining $74,800 pro rata | Partners 1–4 by % | All members |

Partner 1 ends up with ~$46,000, Partner 2 with ~$19,000, Partner 3 with ~$16,000, Partner 4 with ~$13,000. The preferred return compensates Partner 1 for the risk of putting up most of the capital, while the promote pool incentivizes performance.

#### Step 4: Exit scenario

If the company sells for **$2M** after 5 years:

1. Return of capital: $200,000 returned to members pro rata
2. Preferred return catch-up: ~$60,000–$75,000 to Partner 1 (8% compounded)
3. Promote: 15% of remaining (~$260,000) to promote pool
4. Residual: ~$1.48M split by ownership %

Partner 1 walks away with ~$800,000–$900,000. Partners 2–4 each get ~$300,000–$500,000 depending on vesting and promote allocation.

### Sample Operating Agreement Language

Here's what the membership class provisions look like in a real OA (simplified):

> **Section 3.1 — Classes of Membership Interests.** The Company shall have three classes of membership interests designated as follows:
>
> **(a) Class A Units.** Class A Units shall have a **Preferred Return** of eight percent (8%) per annum, compounded annually, on the Unreturned Capital Contribution of the holder. Class A Units shall be entitled to vote only on Major Decisions (as defined in Section 5.4) and shall have no management rights.
>
> **(b) Class B Units.** Class B Units shall participate in Profits and Losses pro rata with all other Class B Units and shall be subject to the vesting schedule set forth in Schedule C. Class B Units shall have full voting rights on all matters.
>
> **(c) Class C Units.** Class C Units shall be non-voting and shall entitle the holder to a percentage of Profits as determined annually by the Managers, not to exceed fifteen percent (15%) of Profits in any fiscal year.

> **Section 4.2 — Waterfall Distribution.** Distributions shall be made in the following order:
>
> 1. *First*, to Class A Members, an amount equal to the accrued and unpaid Preferred Return;
> 2. *Second*, to all Members, pro rata, an amount equal to their unreturned Capital Contributions;
> 3. *Third*, to Class C Members, the Promote Allocation;
> 4. *Fourth*, to all Members, pro rata in accordance with their Percentage Interests.

### Key Questions to Negotiate

| Question | Why It Matters |
|----------|---------------|
| Does the preferred return compound? | Big difference in Partner 1's payout over time |
| Can the company skip the preferred return in lean years? | Preserves cash; may or may not accumulate |
| Do Class B units vest? | Protects against someone leaving early with full equity |
| Who allocates the promote pool? | Needs to be fair and transparent |
| Can classes be converted? | Allows Class A to convert to Class B on exit for tax reasons |
| What happens if a member stops working? | Defines whether they keep unvested units |

### Holding Company + Operating Subs

If the venture expands into licensed cannabis distribution (especially NJ's Class 4 license), consider a parent-subsidiary structure:

```
Parent LLC (PA)
  ├── PA Distribution LLC  (medical accessories, non-licensed)
  └── NJ Distribution LLC  (Class 4 licensed entity)
```

This isolates regulatory risk and makes it easier to sell or partner on a state-by-state basis.

### Series LLC (Alternative)

Pennsylvania recognizes Series LLCs (15 Pa.C.S. § 8855), which let you create separate "series" within a single LLC — each with its own assets, liabilities, and members. This is lighter than separate subsidiaries but has uncertain treatment in other states (including NJ), so proceed with caution.

---

## Part II: Partnership Agreement Mechanics

The Operating Agreement is the central contract. But for a four-person venture with pre-existing businesses, several additional documents may be needed.

### 1. Operating Agreement (Core Contract)

This is the main governance document. Key sections:

- **Capital Contributions** — Schedule A with exact amounts and timelines
- **Distributions** — Waterfall: (1) return of capital, (2) preferred return to Class A, (3) promote, (4) residual
- **Voting** — List of "major decisions" requiring unanimous or supermajority consent
- **Transfer Restrictions** — Rights of first refusal, tag-along/drag-along
- **Buy-Sell** — Trigger events, valuation method, payment terms

See the [Operating Agreement]({{ '/operating-agreement' | relative_url }}) page for a full breakdown.

### 2. Vesting Agreement (Sweat Equity)

If Partners 2–4 earn their equity over time (common when capital is uneven), use a vesting schedule:

- **Cliff:** 1-year cliff — no equity vests until 12 months in
- **Vesting:** Monthly or quarterly over 3–4 years thereafter
- **Acceleration:** Single-trigger (change of control) or double-trigger (change + termination)
- **Forfeiture:** Unvested units return to the company at cost

### 3. Capital Contribution Agreement

Formalizes when and how Partner 1's capital is deployed:

- Total commitment amount
- Draw schedule (e.g., $X at closing, $Y at milestones)
- Conditions to funding (e.g., signed contracts with 3 brands)
- Default provisions if capital isn't called

### 4. Side Letter: Existing Business Carve-Outs

Since all four members run existing businesses, a side letter should explicitly:

- Define each member's **pre-existing business** (Schedule B)
- Carve those businesses out from any non-compete
- Restrict use of venture resources for side businesses
- Establish **conflict-of-interest** disclosure requirements

### 5. Intellectual Property Assignment

Not critical for a distribution business, but worth documenting:

- Any IP created for the venture (branding, systems, processes) belongs to the company
- Members grant a license for any pre-existing IP they contribute

---

## Part III: Putting It Into Practice

### Recommended Process

| Step | Action | Who | Reference |
|------|--------|-----|-----------|
| 1 | Negotiate economic terms (who gets what) | All members | — |
| 2 | Draft Operating Agreement | Attorney | [PA Multi-Member OA Template](https://eforms.com/download/2016/01/pennsylvania-multi-member-llc-operating-agreement-template.pdf) |
| 3 | File Articles of Organization with PA | Attorney or members | [DSCB Form 15-8821 (PDF)](https://www.pa.gov/content/dam/copapwp-pagov/en/dos/programs/business/forms/offsite-forms/15-8821-Cert-of-Org-Dom-LLC.pdf) · [File Online](https://www.corporations.pa.gov/) |
| 4 | Draft side letters (vesting, carve-outs, capital) | Attorney | — |
| 5 | Execute all documents | All members | — |
| 6 | Open bank account, obtain EIN | Partner 1 | [IRS EIN Application](https://www.irs.gov/businesses/small-businesses-self-employed/apply-for-an-employer-identification-number-ein-online) |
| 7 | Register for PA taxes | Partner 2 | [PA myPATH](https://mypath.pa.gov/) |
| 8 | File BOI report (if required) | Partner 2 | [FinCEN BOI E-Filing](https://boiefiling.fincen.gov/) · [BOI Instructions](https://www.fincen.gov/boi) |

### Timeline

- **Week 1–2:** Term sheet negotiation among members
- **Week 3–4:** Attorney drafts documents
- **Week 5:** Filing + execution
- **Week 6:** Bank account, EIN, tax registrations

### Estimated Costs

| Item | Cost |
|------|------|
| PA LLC filing fee | ~$125 |
| Attorney (OA + side letters) | $3,000–$7,500 |
| Registered agent (optional) | $100–$300/yr |
| BOI report filing | $0 (free) |

---

## Summary: The Right Way to Do It

1. **Entity:** Pennsylvania multi-class, manager-managed LLC
2. **Economics:** Waterfall distribution with Class A preferred return
3. **Governance:** Co-managers (Partner 1 + Partner 2), unanimous consent for major decisions
4. **Partners:** Vesting schedules for operating members, clear carve-outs for existing businesses
5. **Documents:** Operating Agreement + Vesting Agreement + Capital Contribution Agreement + Side Letter

---

## References & Templates

Links to the actual forms and templates referenced throughout this site. These are the same documents your attorney will use.

### PA LLC Formation

| Document | Source | Link |
|----------|--------|------|
| Certificate of Organization (Form DSCB:15-8821) | PA Department of State | [PDF](https://www.pa.gov/content/dam/copapwp-pagov/en/dos/programs/business/forms/offsite-forms/15-8821-Cert-of-Org-Dom-LLC.pdf) |
| Docketing Statement (Form DSCB:15-134A) | PA Department of State | [PDF](https://www.pa.gov/content/dam/copapwp-pagov/en/dos/resources/business/forms/15-134A%20Docketing%20statement%20creation.pdf) |
| Online filing portal | PA Business One-Stop | [File Online](https://www.corporations.pa.gov/) |
| PA LLC guide | PA Department of State | [Guide](https://www.pa.gov/agencies/dos/programs/business/types-of-filings-and-registrations/pennsylvania-limited-liability-company) |

### Operating Agreement Templates

| Document | Source | Link |
|----------|--------|------|
| PA Multi-Member LLC Operating Agreement | eForms | [PDF](https://eforms.com/download/2016/01/pennsylvania-multi-member-llc-operating-agreement-template.pdf) · [DOCX](https://eforms.com/download/2016/01/pennsylvania-multi-member-llc-operating-agreement-template.docx) |
| PA Multi-Member LLC Operating Agreement | FreeForms | [PDF](https://freeforms.com/wp-content/uploads/2024/02/Pennsylvania-Multi-Member-LLC-Operating-Agreement-Form.pdf) · [DOCX](https://freeforms.com/wp-content/uploads/2024/02/Pennsylvania-Multi-Member-LLC-Operating-Agreement-Form.docx) |
| General Multi-Member OA Template | PandaDoc | [Template](https://www.pandadoc.com/pennsylvania-operating-agreement-templates) |

### Federal & Tax

| Document | Source | Link |
|----------|--------|------|
| EIN Application (SS-4) | IRS | [Apply Online](https://www.irs.gov/businesses/small-businesses-self-employed/apply-for-an-employer-identification-number-ein-online) |
| BOI Report Filing | FinCEN | [E-Filing Portal](https://boiefiling.fincen.gov/) |
| BOI Reporting Overview | FinCEN | [Guidance](https://www.fincen.gov/boi) |
| PA Tax Registration | PA Revenue | [myPATH Portal](https://mypath.pa.gov/) |

### PA Cannabis Regulation

| Document | Source | Link |
|----------|--------|------|
| PA Medical Marijuana Act (Act 16) | PA General Assembly | [Statute](https://www.legis.state.pa.us/cfdocs/legis/li/uconsCheck.cfm?yr=2016&sessInd=0&act=16) |
| NJ CREAMMA (P.L. 2021, c. 16) | NJ Legislature | [Statute](https://pub.njleg.gov/bills/2020/PL21/16_.HTM) |
| NJ CRC Licensing | NJ Cannabis Regulatory Commission | [Website](https://www.nj.gov/cannabis/) |

<div class="disclaimer">
  <strong>Disclaimer:</strong> This is a conceptual legal model, not a template or recommendation for any specific situation. Every venture's circumstances are different. Engage a Pennsylvania-licensed business attorney to draft and negotiate all documents.
</div>
