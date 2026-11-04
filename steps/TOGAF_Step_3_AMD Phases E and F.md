# TOGAF Standard, 10th Edition — Step 3 Quick Notes

## Step 3 — Distinguish Phase E from Phase F

### Core distinction

- **Phase E — Opportunities & Solutions:** turn the architecture gaps into a practical implementation approach by grouping changes into solution building blocks, work packages, and Transition Architectures.
- **Phase F — Migration Planning:** prioritize and sequence those work packages into a detailed Implementation and Migration Plan.

### Fast mental model

> **E = What implementation packages and transition states could deliver the Target Architecture?**

> **F = In what priority and sequence should those packages be executed?**

### Worked example: unified customer platform

Architecture gaps identified in phases B, C, and D include:

- harmonize customer-registration processes
- consolidate customer data
- replace four portals
- introduce integration and identity capabilities

#### Phase E decisions

Package the gaps into implementable change:

- Work Package 1: customer-data consolidation
- Work Package 2: shared identity and access capability
- Work Package 3: unified portal
- Work Package 4: legacy portal retirement

Define useful intermediate states, such as a **Transition Architecture** in which the unified portal exists but still reads from selected legacy databases during migration.

#### Phase F decisions

Evaluate and sequence the work packages using factors such as:

- business value
- cost
- risk
- dependencies
- resource availability

Possible sequence:

1. establish shared identity
2. create the authoritative customer-data capability
3. deploy the unified portal
4. migrate users and retire legacy portals

### Exam-recognition patterns

Choose **Phase E** when the scenario emphasizes:

- identifying implementation options
- grouping gaps into work packages
- defining solution building blocks
- identifying major implementation projects
- defining Transition Architectures
- creating the initial Implementation and Migration Strategy

Choose **Phase F** when the scenario emphasizes:

- prioritizing projects or work packages
- dependency analysis
- cost, benefit, value, or risk assessment for sequencing
- producing a detailed Implementation and Migration Plan
- confirming the execution roadmap

### Common trap

Both phases discuss implementation and migration. Distinguish them by the decision being made:

- **Packaging and possible transition states → E**
- **Prioritization and detailed sequencing → F**

### Minimum recall

> **E packages the change. F plans the order.**
