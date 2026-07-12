# Prompt: Build "Distribution Governance" GitHub Pages Site

## Mission

Build a Jekyll-based GitHub Pages website at **distribution-governance.github.io** (or your custom domain) that serves as a definitive reference for structuring a **marijuana distribution venture** in **Pennsylvania and New Jersey**.

## The Venture

Four existing business owners are forming a side venture to distribute brands (marijuana-related products) to retail stores across PA and NJ. The business model is bulk distribution — sourcing products from brands and supplying dispensaries/retailers.

### The Four Roles

| Role | Responsibilities |
|------|-----------------|
| **Partner 1 (Funder/Admin)** | Provides capital, oversees administration, financial oversight, high-level governance |
| **Partner 2 (Operations)** | General accounting, support desk, day-to-day operations management |
| **Partner 3 (Sales)** | Sales acquisition, relationship management, brand partnerships |
| **Partner 4 (Fulfillment)** | Logistics, warehousing, order fulfillment, delivery |

### States of Operation
- **Pennsylvania** (primary) — PA has a medical marijuana program (MMJ). Adult-use is not yet legal as of 2025 but is advancing legislatively.
- **New Jersey** (secondary) — NJ has both medical and adult-use (recreational) marijuana markets.

## Content Requirements

### Pages to Create

1. **Home** (`index.md`) — Overview of the venture, quick navigation, elevator pitch
2. **Legal Framework** — Deep analysis of entity structures for PA:
   - LLC vs. Corporation vs. Partnership
   - Why an LLC is likely optimal (flexibility, pass-through taxation, limited liability, operating agreement flexibility)
   - PA-specific requirements (Department of State filing, taxes, marijuana-specific regulations)
   - NJ considerations if expanding
3. **Team & Roles** — Details on each partner's role, equity split considerations, decision-making rights
4. **Operating Agreement** — Key clauses for a multi-member LLC:
   - Capital contributions
   - Profit/loss distribution (waterfall vs. pro-rata)
   - Voting rights and deadlock resolution
   - Buy-sell provisions
   - Non-compete and confidentiality
   - Dissolution terms
5. **PA/NJ Marijuana Context** — Regulatory landscape:
   - PA Medical Marijuana Program (Act 16)
   - NJ Cannabis Regulatory, Enforcement Assistance, and Marketplace Modernization Act (CREAMMA)
   - Licensing types (grower/processor, dispensary, etc.)
   - Distribution-specific regulations
   - Banking/financial considerations (280E, SAFE Banking)

### Design & UX

- Clean, professional, modern — suitable for business stakeholders
- Mobile-responsive
- Dark blue / green color scheme (evoking governance + cannabis)
- Easy navigation between pages
- Print-friendly (for printing agreements or reference docs)

### Technical Requirements

- **Static site generator**: Jekyll (native GitHub Pages support)
- **Deployment**: GitHub Pages via `gh-pages` branch or root of `main`
- **Custom domain**: Optional (plan for it in config)
- **No backend**: Everything static HTML/JS
- **Markdown content** with YAML front matter

## Tone

Professional, authoritative, practical. Write for business owners making legal decisions — not lawyers, but sophisticated enough to have informed conversations with their attorney. Cite relevant PA/NJ statutes where appropriate.

## Output

Generate the complete Jekyll site including:
- `_config.yml` with site configuration
- `_layouts/default.html` — main layout
- `assets/css/main.scss` — all styles
- `index.md` — home page
- Pages for each content area above
- `.gitignore` for Jekyll

## Constraints

- No external dependencies beyond what GitHub Pages supports natively
- No JavaScript frameworks (vanilla JS or none)
- All content must be original or properly attributed
- Do NOT give legal advice — frame as "considerations" and "common structures," always recommending consultation with a qualified attorney
