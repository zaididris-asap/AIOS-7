# RAB Design Registry — Seed v1.0-RC

**Status: Proposed / Public preview.** Maturity labels are not evidence of multi-account compatibility.

| ID | Primitive | Function | Maturity |
|---|---|---|---|
| RAB-U01 | Identity Header | Scope, title and status | SPECIFIED |
| RAB-U02 | Orientation Navigator | Navigate sections/views | SPECIFIED |
| RAB-U03 | Core Answer Surface | Deliver the result | SPECIFIED |
| RAB-U04 | Interaction Controller | Select/filter/adjust | PROTOTYPED in one conversation |
| RAB-U05 | Evidence & Integrity Lens | Sources and caveats | SPECIFIED |
| RAB-U06 | State & Progress Ledger | Proposed vs verified | SPECIFIED |
| RAB-U07 | Continuation & Recovery Dock | Follow-up and handoff | PROTOTYPED in one conversation |

## Specialized pattern seeds

| ID | Name | Key primitives |
|---|---|---|
| DEC-01 | Single Decision Card | U01,U03,U04,U05,U06,U07 |
| CMP-01 | Comparison Matrix | U02,U03,U04,U05 |
| RES-01 | Evidence Inspector | U02,U03,U05 |
| PRJ-01 | Workstream Navigator | U01,U02,U04,U06,U07 |
| EXE-01 | Execution Status | U01,U03,U05,U06,U07 |
| GOV-01 | Risk Review | U02,U03,U04,U05,U06 |
| DAT-01 | Scenario Simulator | U03,U04,U05 |
| DOC-01 | Document Reviewer | U01,U02,U03,U04,U05 |
| CRE-01 | Concept Selector | U03,U04,U07 |
| LEA-01 | Knowledge Check | U02,U03,U04,U05,U06 |
| COM-01 | Message Variant Selector | U03,U04,U07 |
| LIF-01 | Priority Planner | U02,U03,U04,U07 |

These are design patterns, **not built downloadable UI components**.

## Candidate record schema

```yaml
id: RAB-X###-candidate
name:
version:
origin:
use_case:
trigger:
nonduplication_reason:
visual_anatomy:
required_inputs:
state_model:
events:
authority_and_evidence:
fallback:
accessibility:
acceptance_criteria:
validation_status: CANDIDATE
persistence_evidence:
```

Register a new ID only after checking for duplicates. New functionality or a materially different outcome is required; cosmetic differences are variants. Never claim TESTED without tests or APPROVED without approval. Record provenance and confirmed commit for published updates.