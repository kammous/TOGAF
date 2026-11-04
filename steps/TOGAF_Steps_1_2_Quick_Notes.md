# TOGAF Standard, 10th Edition — Steps 1 & 2 Quick Notes

## Step 1 — Understand the ADM as a decision-making process

### Core mental model

**Preliminary → A → B → C → D → E → F → G → H → repeat**

**Requirements Management** operates throughout the ADM.

| Phase | Question to ask yourself |
|---|---|
| Preliminary | How are we going to do architecture here? |
| A — Architecture Vision | What are we trying to achieve, why, and who cares? |
| B — Business Architecture | How must the business operate? |
| C — Information Systems Architectures | What data and applications do we need? |
| D — Technology Architecture | What technology/infrastructure supports it? |
| E — Opportunities & Solutions | How do we package the change into implementable solutions? |
| F — Migration Planning | In what order should we implement them? |
| G — Implementation Governance | Are projects implementing what we designed? |
| H — Architecture Change Management | Has enough changed that the architecture must change? |

### Phase A recognition pattern

Think **Phase A — Architecture Vision** when the problem focuses on:

- stakeholders and their concerns
- scope
- business motivation/value
- high-level target/vision
- agreement on what the architecture initiative is trying to accomplish

**Exam trigger:** stakeholders + concerns + scope + high-level target/value → **Phase A**.

### Domain mapping to know cold

- Business processes/capabilities → **B**
- Data → **C**
- Applications → **C**
- Technology/infrastructure → **D**

---

## Step 2 — Baseline → Target → Gap

For architecture domains in phases B, C, and D, use this mental pattern:

1. **Baseline Architecture** — Where are we now?
2. **Target Architecture** — Where do we want to be?
3. **Gap Analysis** — What is different between Baseline and Target?

### Example: unified customer platform

#### B — Business Architecture

- **Baseline:** duplicated customer-registration processes and fragmented ownership.
- **Target:** unified registration process and operating model.
- **Gap:** processes and responsibilities that must be consolidated or changed.

#### C — Information Systems Architectures

C covers **Data Architecture** and **Application Architecture**.

- **Baseline:** 3 incompatible customer databases and 4 portal applications.
- **Target:** authoritative customer information and a unified customer platform.
- **Gap:** data migration/consolidation, application replacement/retirement, and integration changes.

#### D — Technology Architecture

- **Baseline:** legacy infrastructure supporting separate portals.
- **Target:** technology services/platform supporting the unified architecture.
- **Gap:** technology capabilities that must be introduced, changed, or retired.

### Exam technique

When a question says the architect is comparing current and desired environments, do not select a phase merely because you see the words **gap analysis**.

First ask:

> **Which architecture domain is being examined?**

Then map the domain to its ADM phase:

- Business → **B**
- Data → **C**
- Applications → **C**
- Technology → **D**

### Key example

> Current customer data is held in three incompatible databases. The architect describes the current data environment, defines the desired data environment, and identifies the differences.

Answer:

- **Phase C — Information Systems Architectures**, specifically Data Architecture.
- Perform **Baseline → Target → Gap Analysis**.

---

## Minimum recall before continuing

You should be able to say from memory:

> **A = Vision, B = Business, C = Data + Applications, D = Technology.**

and:

> **Baseline = now, Target = desired future, Gap = what must change.**
