# CSA Mayors Deck v4 — Build Spec

## Build Instructions

Use `JOSH_Mayors_v3.html` as the **template reference** — reuse the entire CSS infrastructure:
- Color vars (`--hearth`, `--ember`, `--linen`, `--parch`, etc.)
- Font stack (Playfair Display, Cormorant SC, EB Garamond, Source Sans 3, Cormorant Garamond)
- Chrome system (`.topbar`, `.hdr`, `.ftr`, `.hdr-dark`, `.ftr-dark`)
- Nav system (`#nav`, `#deck`, `#scaler`, slide transitions)
- 960×540 slide dimensions with auto-scaling

Build as a single self-contained HTML file. Same visual quality and polish as v3.

---

## Narrative Architecture

**The spine:** BHF and JOSH are two instruments of one movement, built from the same three first principles:

1. **Start with physical reality** — measure before you mandate
2. **Align human incentives** — make cities want to participate
3. **Build for constitutional and appellate durability** — every input auditable, every finding defensible

The deck shows this pattern twice (BHF, then JOSH), then reveals they are one system.

**Audience:** Mayors and city council members. 15-minute meeting. They need to understand what CSA is, why the framework protects their city, and what the concrete next step is.

---

## Slide-by-Slide Spec

### Slide 1: TITLE

**Layout:** Linen background. Centered. Breathing room. (Reuse s1 pattern from v3.)

**Content:**
- Kicker: `CALIFORNIA STEWARDSHIP ALLIANCE`
- H1: `Built from *First Principles*`
- H2 (italic, lighter): `A framework for housing, fire safety, and the cities caught between them`
- Rule (gold, 40px)
- Bottom line: `californiastewardship.org`

**Footer:** `Confidential — For city leadership`

---

### Slide 2: THE DISEASE

**Layout:** Dark (hearth background). Split layout — big statement left, supporting data right.

**Header kicker:** `The Diagnosis`

**Left side:**
- Big type (Playfair, white): `California mandates growth it has *never measured* — on streets it has *never funded.*`
- Below, smaller italic (EB Garamond): `People have died on streets no one calculated could handle the load. Homes are mandated into neighborhoods whose infrastructure was never assessed.`

**Right side — data column** (3 stat callouts, stacked vertically, gold numbers):
- `4.4%` — Very low income units permitted vs. RHNA allocation (HCD Feb 2026)
- `27.1%` — Market-rate units permitted — six times the rate
- `0` — Times California has measured street capacity before imposing a housing mandate

**Footer:** `Same disease. Two symptoms. One framework.`

**Speaker notes:** The housing crisis and the fire safety crisis share a root cause: California imposes obligations on communities without measuring whether the physical infrastructure can handle them. The RHNA numbers are from HCD's own 6th Cycle data — the state's own scorecard shows the mandate system producing luxury housing at six times the rate of affordable housing. Paradise, Lahaina, Palisades — in each case, development was approved without ever calculating whether everyone could leave at once.

---

### Slide 3: FIRST PRINCIPLES (Overview)

**Layout:** Linen. Three-column layout. Each column is a numbered principle with an icon/symbol, title, and one-sentence definition.

**Header kicker:** `Three Principles — Two Instruments`

**Columns:**

| # | Title | Definition |
|---|-------|-----------|
| I | Start with physical reality | Every street has a measurable capacity. Measure it before you mandate on it. |
| II | Align human incentives | Make cities want to participate. Earn compliance — don't coerce it. |
| III | Build for appellate durability | Every input from a credentialed national authority. Every finding reproducible by any licensed engineer. |

**Bottom bar (dark, full-width, like the s2-principle bar in v3):**
`These three principles built the Balanced Housing Framework. They built JOSH. They are the movement.`

**Speaker notes:** This is the architectural overview. Every claim CSA makes, every tool we build, every policy position we take traces back to these three principles. We show them first in the housing framework, then in the fire safety tool. The audience should feel the repetition — that's the point. The pattern is the argument.

---

### Slide 4: BHF — PRINCIPLE I (Physical Reality)

**Layout:** Linen. Left-heavy text with a right-side visual element (the street cross-section concept or a simple capacity diagram).

**Header kicker:** `Balanced Housing Framework` | right side: `Principle I — Physical Reality`

**Left side:**
- Label: `THE MEASUREMENT THAT HAS NEVER BEEN MADE`
- Big type: `Every street has a *calculable* vehicular throughput capacity.`
- Body: `A 36-foot residential street in Encinitas and a 36-foot street in City Heights have the same capacity. The measurement doesn't know what the homes cost or who lives in them. It knows the pavement, the load, and the capacity.`
- Second body paragraph: `We honor capacity limits everywhere except housing. We don't let a nightclub exceed its fire marshal occupancy. We don't let a bridge exceed its load rating. But we mandate homes onto streets we've never measured.`

**Right side:** A simple visual — three horizontal bars showing:
- `Nightclub` → Fire marshal capacity ✓
- `Bridge` → Engineering load rating ✓  
- `Residential street` → Never measured ✗

**Speaker notes:** Street width is the constitutional standard. It was chosen because it is the physical fact that shaped every residential neighborhood in California — it determined the density, the density determined the character. A built-out residential street has houses on both sides. The right-of-way is fixed. No one is going to condemn private homes to widen a residential street. The pavement that exists is the pavement that will exist. HCM (Highway Capacity Manual) provides the throughput calculation. A city planner can do it with a calculator. A court can verify it in an afternoon.

---

### Slide 5: BHF — PRINCIPLE II (Align Incentives)

**Layout:** Linen. This slide should feature the equity gate decision tree diagram (reference the uploaded `image.png` — the flow from "City decides" through the equity gate to grow inside/outside certification).

**Header kicker:** `Balanced Housing Framework` | right side: `Principle II — Align Incentives`

**Content approach:** Reproduce the equity gate diagram visually in HTML/CSS (the flowchart from the uploaded image). Below or beside it:

- Key insight text: `Growth is voluntary. The terms of growth are not.`
- Three-line summary:
  - `Cities that certify:` Streamlined permitting, CEQA relief, state infrastructure investment, capacity dividend (40% of incremental tax revenue)
  - `Cities that grow without certifying:` Same equity obligation. Full CEQA. No investment. No dividend.
  - `Cities that stay static:` No mandates. No obligations. But they watch their neighbors capture the investment.

**Bottom bar or callout:** `The rational choice is obvious. That's the design.`

**Speaker notes:** The current system punishes cities. BHF makes them partners. The equity gate is the key — it applies to ALL growth regardless of certification, with a constitutional floor of 15% affordable. But certification unlocks the full framework: streamlined approvals, state investment, the capacity dividend. The competitive pressure is the engine. Cities aren't coerced. They're offered a deal good enough that declining costs them. The diagram makes the architecture visible: stay static (no obligations), grow outside (same obligation, no help), grow inside (same obligation, full support). The "same floor, better deal" framing is the design principle.

---

### Slide 6: BHF — PRINCIPLE III (Appellate Durability)

**Layout:** Dark (hearth). Two-column. Left: the legal architecture. Right: the AFFH defense.

**Header kicker:** `Balanced Housing Framework` | right side: `Principle III — Appellate Durability`

**Left column:**
- Label: `CONSTITUTIONAL DESIGN`
- Key points (styled as short statement blocks, not bullets):
  - `The HAA already contains a health-and-safety exception (§ 65589.5(d)(2)). BHF gives it engineering teeth.`
  - `A certified capacity finding = the "specific, adverse impact" finding the HAA requires. No new carve-out. The framework the exception always needed.`
  - `Guenoc Valley (2024): California courts already held evacuation capacity is cognizable grounds for rejecting development.`

**Right column:**
- Label: `THE AFFH DEFENSE`
- Big statement: `A tape measure has no disparate impact.`
- Body: `Street width does not correlate with race, income, or any protected class. Wealthy neighborhoods have narrow streets. Working-class neighborhoods have narrow streets. The measurement doesn't know what the homes cost. A federal court cannot establish disparate impact on pavement geometry.`

**Speaker notes:** This is where the engineering discipline pays off. The HAA is California's most powerful pro-housing statute. BHF doesn't fight it — it co-opts it. The HAA's own health-and-safety exception permits denial when a project has a "specific, adverse impact on public health or safety" based on "objective, identified written public health or safety standards." That's exactly what BHF provides: peer-reviewed, nationally recognized engineering standards applied to street capacity. Guenoc Valley is the doctrinal anchor — already published, already held that evacuation capacity is cognizable. The AFFH defense is structurally airtight because the criterion (street width) is physically determined, not socially constructed. The measure doesn't move poor people to opportunity — it moves opportunity to people, through infrastructure investment in lower-cost communities.

---

### Slide 7: JOSH — PRINCIPLE I (Physical Reality)

**Layout:** Dark (hearth). Reuse the ΔT visual concept from v3 slide 3 — the big symbol on the left, the definition on the right.

**Header kicker:** `JOSH` | right side: `Principle I — Physical Reality`

**Left side:**
- Symbol: `ΔT` (large, gold, italic Playfair)
- Below: `DELTA · T`
- Threshold text: `When ΔT ≤ 0, people die.`

**Right side:**
- Definition (big, white): `The gap between *evacuation time* and *fire arrival time* — for every street, every intersection, every corridor in your city.`
- Rule
- Explanation: `Paradise. Lahaina. Palisades. In each case, homes were approved through processes that never once asked: if everyone needed to leave at the same time, could they?`
- Standard reference block: `NIST TN 2135 · HCM 2022 · NFPA 101 — Assembled. Never before combined at municipal scale.`

**Speaker notes:** Same first principle as BHF — start with a physical measurement. ΔT is the single number that captures whether a street is safe. Evacuation time is calculated from HCM vehicular throughput. Fire arrival time is calculated from NIST ember transport and flame front models. The gap between them is ΔT. If it's positive, people can leave. If it's zero or negative, they can't. This question has never been asked at systematic scale for any city in California. JOSH asks it for every street.

---

### Slide 8: JOSH — PRINCIPLE II (Align Incentives / Revenue Model)

**Layout:** Linen. Two-column. Left: the compliance case. Right: the economics.

**Header kicker:** `JOSH` | right side: `Principle II — Align Incentives`

**Left column:**
- Label: `THE COMPLIANCE CASE`
- Statement: `AB 747 requires every city in California to have an evacuation plan.`
- Body: `Most cities don't have one. The ones that do paid $90K–$600K for proprietary black-box models (KLD/DYNEV) that can't be audited, can't be shared across jurisdictions, and don't use open FEMA-based standards.`
- Callout/highlight: `JOSH: $95K per city — with a $20K CSA implementation grant for founding coalition partners. Effective cost: $75K.`
- Below: `Open source. Auditable. Transferable. Built on federal standards.`

**Right column:**
- Label: `FUNDING THE MOVEMENT`
- Body: `JOSH is how CSA sustains itself. Every city engagement funds the policy work, the legal infrastructure, and the coalition operations that make BHF possible.`
- Simple visual — a flow/cycle:
  - `City buys JOSH` → `AB 747 compliance + defensible capacity data`
  - `Revenue funds CSA` → `BHF development, coalition building, legal infrastructure`
  - `BHF creates demand for JOSH` → `Capacity assessment is constitutionally required`
- Bottom statement: `The tool serves the framework. The framework creates demand for the tool.`

**Speaker notes:** This is the sustainability engine. JOSH isn't just a fire safety tool — it's the revenue source that funds the entire CSA movement. At $95K per city ($75K effective for founding partners), it undercuts the primary competitor (KLD Associates, $90K–$600K) while providing a structurally superior product: open-source, FEMA-based, auditable, shareable across jurisdictions. KLD's DYNEV model is proprietary — cities can't audit it, can't share it, and it doesn't produce findings in a format that survives appellate review. JOSH does. The flywheel: BHF requires capacity assessments → JOSH provides them → revenue funds CSA → CSA advances BHF → more cities need JOSH. San Diego beachhead: Solana Beach pilot → SANDAG regional standard via Hebner's chairmanship → lateral COG adoption.

---

### Slide 9: JOSH — PRINCIPLE III (Appellate Durability)

**Layout:** Dark. Similar to v3's methodology slide (the standards pipeline). Could reuse the visual concept.

**Header kicker:** `JOSH` | right side: `Principle III — Appellate Durability`

**Content — the standards pipeline** (visual: three source blocks feeding into one output):

Sources (three blocks across the top):
- `NIST TN 2135` — Fire behavior, ember transport, structure ignition
- `HCM 2022` — Vehicular throughput, intersection capacity, lane configuration  
- `NFPA 101` — Occupant load, egress capacity, evacuation timing

Output (single block below):
- `JOSH ΔT` — Combined into one defensible finding per street segment

**Below the pipeline:**
- `Every step auditable. Every number sourced. Every finding defensible in court.`
- `Guenoc Valley (2024): Evacuation capacity is already cognizable grounds for land use decisions in California.`
- WPI validation line: `Methodology developed in collaboration with Worcester Polytechnic Institute. Independent validation in progress.`

**Speaker notes:** Same principle as BHF's appellate durability — but applied to the tool itself. Every input in JOSH comes from a credentialed national authority. No proprietary algorithms. No black boxes. A city attorney can trace any output back to a published, peer-reviewed standard. This is the structural advantage over KLD/DYNEV: when a developer challenges a city's evacuation finding, JOSH's methodology can be verified by any licensed engineer. A proprietary model can't. Guenoc Valley established the legal principle. JOSH provides the engineering framework.

---

### Slide 10: THE SYSTEM

**Layout:** Linen. Full-width. This is the "reveal" slide — showing BHF and JOSH as one integrated system.

**Header kicker:** `One Movement`

**Visual concept:** A simple diagram showing the connection:

```
 ┌─────────────────────────┐         ┌─────────────────────────┐
 │   BALANCED HOUSING      │         │        JOSH             │
 │   FRAMEWORK             │         │                         │
 │                         │         │   Evacuation capacity   │
 │   Constitutional        │◄────────│   findings feed         │
 │   amendment requiring   │         │   directly into BHF     │
 │   capacity assessment   │         │   capacity assessments  │
 │   before mandates       │────────►│                         │
 │                         │         │   BHF creates           │
 │                         │         │   constitutional demand │
 │                         │         │   for JOSH              │
 └─────────────────────────┘         └─────────────────────────┘
           │                                    │
           └────────────┬───────────────────────┘
                        │
              ┌─────────▼─────────┐
              │   CITIES JOIN     │
              │   THE COALITION   │
              │                   │
              │  Immediate:       │
              │  AB 747 compliance│
              │  + defensible     │
              │  capacity data    │
              │                   │
              │  Long-term:       │
              │  Constitutional   │
              │  protection from  │
              │  unfunded mandates│
              └───────────────────┘
```

**Text beside or below diagram:**
- `JOSH is available now. BHF is the 2028 ballot measure.`
- `Cities that adopt JOSH today are building the evidentiary foundation for BHF tomorrow.`

**Speaker notes:** This is the key strategic insight for mayors: JOSH and BHF are not separate products. They are two phases of the same movement. A city that runs JOSH today gets immediate AB 747 compliance — a real, present legal obligation. But the capacity data JOSH produces is exactly the data BHF will constitutionally require. Every city that adopts JOSH is pre-building its BHF capacity assessment. The timeline: JOSH is available now. BHF files with the AG in early 2027, signature drive launches July 2027, targeting the November 2028 general election ballot.

---

### Slide 11: THE COALITION + ASK

**Layout:** Linen. Split — left: the ask. Right: the city grid + steps. (Reuse the s7/s8 hybrid concept from v3.)

**Header kicker:** `The Invitation`

**Left side:**
- Big type: `What is *your city's* number?`
- Body: `No commitment. No budget. One conversation — and you'll know exactly where your evacuation corridors stand, what your capacity is, and what your legal options are.`
- `We'll run the analysis. You decide what to do with it.`

**Right side — three steps** (numbered, like v3):
1. **Request a Briefing** — One meeting. We run your city's JOSH analysis and walk through the results with you and your staff.
2. **Review with Your Attorney** — Share the analysis and legal memo with your city attorney. Everything is open source and fully auditable.
3. **Join the Coalition** — Adopt the model ordinance. Your city's weight makes the standard harder to attack for every city that follows.

**Below the steps — city grid** (like v3):
- Encinitas (flagged as joined)
- 11 open "Your City" slots

**Bottom:**
- `californiastewardship.org`
- `California Stewardship Alliance · In collaboration with Worcester Polytechnic Institute`

**Speaker notes:** The ask is deliberately low-friction. No budget commitment. No council vote required for the first step. Just one meeting where we run the analysis and show them their own data. The city grid is the coalition visualization — every slot filled makes the standard harder to attack. One city is a target. Twenty cities is a standard. Sacramento can challenge one city's methodology. It cannot challenge a coalition's standard that's validated by WPI, grounded in federal standards, and adopted across jurisdictions.

---

## Design Notes

### Visual Rhythm
- Slides alternate between linen (light) and hearth (dark) backgrounds
- The three-principle pattern creates a visual cadence: overview (linen), BHF I (linen), BHF II (linen w/ diagram), BHF III (dark), JOSH I (dark), JOSH II (linen), JOSH III (dark), System (linen), Ask (linen)
- Dark slides = physics, measurement, legal architecture
- Light slides = incentives, offers, invitations

### Recurring Motifs
- The three-principle numbering (I, II, III) should be visually consistent across BHF and JOSH sections — same treatment, same position — so the audience feels the repetition
- Header kicker pattern: left side identifies the section (BHF or JOSH), right side identifies which principle — this creates wayfinding
- Gold rule (1.5px, 32-40px wide) as section divider within slides

### Typography Hierarchy
- Slide titles / big statements: Playfair Display, 28-48pt, bold
- Emphasis / italics within titles: Playfair italic, ember gold color
- Labels / kickers: Cormorant SC, 8-10px, tracked out, ember
- Body text: EB Garamond, 14px, italic, walnut
- Data / stats: Source Sans 3, 600 weight, large (48-72pt for callout numbers)
- Standard references: Source Sans 3, 9px, rgba white 35%

### Key Brand Elements to Preserve from v3
- The 3px gold gradient topbar on every slide
- The header bar with Cormorant SC kickers
- The footer bar with EB Garamond italic left / Cormorant SC right
- The dark "principle bar" at bottom of key slides (full-width, hearth bg, centered italic Playfair statement)
- The transition system (translateX with opacity)
- The nav bar with slide counter

---

## File Inputs

- `JOSH_Mayors_v3.html` — Template for all CSS/JS infrastructure
- `image.png` — Equity gate decision tree (reference for slide 5 layout; rebuild in HTML/CSS rather than embedding the image)
- BHF v12 document — Source for all policy content and data points

## Output

Single HTML file: `CSA_Mayors_v4.html`
11 slides. Self-contained. Same nav/scaling/fullscreen system as v3.
