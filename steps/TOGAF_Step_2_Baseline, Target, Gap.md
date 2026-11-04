# TOGAF Standard, 10th Edition — Step 2 Revision Sheet

## Baseline → Target → Gap

Use this pattern when developing Business, Data, Application, and Technology Architectures:

1. **Baseline Architecture:** Where are we now?
2. **Target Architecture:** Where do we want to be?
3. **Gap Analysis:** What must be introduced, changed, or retired to move from Baseline to Target?

## Domain examples

### Phase B — Business Architecture

- **Baseline:** duplicated customer-registration processes and fragmented ownership
- **Target:** unified registration process and operating model
- **Gap:** processes, capabilities, and responsibilities to consolidate or change

### Phase C — Data Architecture

- **Baseline:** three incompatible customer databases
- **Target:** authoritative, consistent customer information
- **Gap:** data consolidation, cleansing, migration, and retirement

### Phase C — Application Architecture

- **Baseline:** four separate customer portals
- **Target:** unified customer platform
- **Gap:** applications and interfaces to introduce, integrate, replace, or retire

### Phase D — Technology Architecture

- **Baseline:** fragmented legacy infrastructure
- **Target:** technology services supporting the unified platform
- **Gap:** technology capabilities to introduce, change, or retire

## Exam-recognition patterns

When a scenario compares an existing environment with a desired environment:

1. Identify the **architecture domain**.
2. Map it to its ADM phase.
3. Recognize the work as **Baseline → Target → Gap Analysis**.

- Business → **B**
- Data → **C**
- Applications → **C**
- Technology → **D**

**Trigger example:** current and desired customer databases + differences → **Phase C, Data Architecture**.

## Common trap

Do not choose a phase merely because the words **gap analysis** appear. Gap Analysis is used across architecture domains. The examined domain determines whether the answer is B, C, or D.

## Minimum recall

> **Baseline = now. Target = desired future. Gap = what must change.**
