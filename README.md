# vpd-assessment

**Value Proposition Diagnosis Framework** — An AI skill for diagnosing whether your product truly solves the right customer problem.

> Built on Strategyzer's Value Proposition Design (Osterwalder, Pigneur, Bernarda, Smith)  
> Version: 1.1.0 · Authors: Eason Zhang, Mars

---

## What It Does

Most products fail not because of poor execution, but because they solve the wrong problem — or solve the right problem for the wrong customer.

`vpd-assessment` diagnoses your value proposition at the mechanism level:

- Does your product address real, important customer jobs/pains/gains?
- Is there genuine Product-Market Fit, or just assumed fit?
- Is the business model strong enough to sustain the value proposition?
- How do you stack up against competitors at the VP level?
- What assumptions need to be tested first?

This is **not** about filling in a canvas. It's about getting honest, structured answers before you commit resources.

---

## Three Modes

| Mode | Time | Best For | Output |
|------|------|----------|--------|
| `deep` | 90–120 min | Consulting DD, full feasibility | HTML report (Eason Consulting brand) |
| `medium` | 45–60 min | Initial project evaluation, pre-proposal diagnosis | Markdown ≤500 words + BM Score table |
| `quick` | 30 min | Directional gut-check, group Q&A | Markdown ≤300 words (HTML option for client delivery) |

---

## Five Steps (deep / medium)

1. **Customer Profile Scan** — Surface Functional / Social / Emotional jobs; rank top pains and gains
2. **Value Map Analysis** — Map Pain Relievers and Gain Creators; identify coverage gaps
3. **Fit Diagnosis** — Problem-Solution Fit / Product-Market Fit / Business Model Fit (🟢/🟡/🔴)
3b. **Competitive VP Comparison** *(deep & medium only)* — Side-by-side matrix vs. 2–3 competitors; identify differentiation and overlap risks
4. **Business Model Quality Score** — 7 dimensions × 0–10; weakest dimension + improvement recommendation
5. **Next Steps** *(deep only)* — Innovation directions + Test Cards (Hypothesis → Method → Success criterion)

---

## How It Differs

| Framework | Lens | When to Use |
|-----------|------|-------------|
| **vpd-assessment** | Product-customer fit | Foundation — use first |
| Superpowers | Competitive moats & strategy | After VP is validated |
| YC evaluation | Investor bet-worthiness | After strategy is clear |

**Recommended order**: `vpd-assessment` → Superpowers → YC

---

## Skill Connections

- **After deep mode** → `company-financial-analysis` (VP diagnosis + financial analysis = complete DD)
- **After quick/medium** → `consulting-report` (package findings into client-ready report)
- **Parallel** → `venture-dd` (investor lens complements product-customer lens)

---

## Installation

```bash
npx skills add vpd-assessment
```

Or copy `SKILL.md` into your agent's skills directory.

---

## References Included

- Customer Jobs / Pains / Gains trigger questions (9 each)
- Pain Relievers / Gain Creators trigger questions (9 each)
- 7-dimension Business Model Quality scoring framework
- 10 Characteristics of a Great Value Proposition (QC checklist)
- Six Ways to Innovate from Customer Profile

---

## Quality Standards

- All conclusions grounded in provided information — no fabrication
- Fit conclusions must distinguish **verified facts** vs. **unverified assumptions**
- If data is insufficient, explicitly state "Insufficient data"
- deep mode: 10 Characteristics checklist is mandatory QC before delivery
