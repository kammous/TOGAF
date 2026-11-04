# TOGAF Standard, 10th Edition — Step 4 Quick Notes

## Step 4 — Phase G vs Phase H

### Core distinction

- **G — Implementation Governance:** govern implementation so deployed solutions conform to the approved architecture.
- **H — Architecture Change Management:** monitor change after architecture/implementation and decide whether the architecture or a new ADM cycle must be initiated.

### Fast mental model

> **G = Are they building it according to the architecture?**

> **H = Has the environment changed enough that the architecture itself must change?**

### Phase G recognition patterns

Choose **G** when the scenario emphasizes:

- implementation is underway
- checking implementation against the architecture
- architecture compliance reviews
- governing implementation projects
- handling implementation-related architecture conformance
- Architecture Contract / governance of delivery

**Exam trigger:** project is building + architect checks conformance → **G**.

### Phase H recognition patterns

Choose **H** when the scenario emphasizes:

- monitoring changes after implementation
- new business, technology, regulatory, or environmental change
- determining whether architecture change is required
- deciding whether to start a new ADM cycle
- ongoing architecture lifecycle/change management

**Exam trigger:** something changed + decide whether architecture must be revised → **H**.

### Worked example

For the unified customer platform:

- Developers implement the new portal and an architecture review checks that the approved identity and data architecture are followed → **G**.
- Months later, a major regulatory requirement changes how customer data may be processed; architects assess the impact and whether a new ADM cycle is necessary → **H**.

### Common trap

Both G and H involve "change" and governance.

Ask **what is being governed**:

- **Implementation of the approved architecture → G**
- **Change to the architecture itself → H**

### Minimum recall

> **G = govern the build. H = govern architectural change.**
