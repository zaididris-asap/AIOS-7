# Universal Seven RAB Primitives — Specification v1.0-RC

## Core architecture

AIOS-7 standardizes **seven semantic functions** rather than seven mandatory visual cards. Each function may be represented by a compact element or combined surface. The composition should optimize actual user outcomes and preserve information clarity on phones.

| ID | Trigger | Inputs | Output or interaction | Fallback |
|---|---|---|---|---|
| U01 Identity Header | Named task, project or status | Topic, scope, revision, status | Header with task context | Inline heading |
| U02 Orientation Navigator | Multi-section or staged content | Sections, steps, order | Tabs, navigation, stepper | Brief outline |
| U03 Core Answer Surface | Every task | Task-relevant facts and result | Substantive answer/artifact | Direct prose |
| U04 Interaction Controller | Meaningful user control | Options, bounds, change events | Stateful selection, filtering, editing | Short reply syntax |
| U05 Evidence & Integrity Lens | Contested facts or consequential claims | Sources, assumptions, uncertainty | Traceable evidence display | Citations and caveats |
| U06 State & Progress Ledger | Decisions, approvals and actions | State, actor, evidence | Distinct proposed/approved/executed/verified statuses | Explicit status line |
| U07 Continuation & Recovery Dock | Useful next step or inability to render RAB | Available action, context | Working follow-up/copy/handoff | Copyable prompt |

## Composition requirements

- Begin with the result where feasible; no mandatory UI preamble for simple answers.
- Match interaction intensity to the task. No forms without meaningful inputs.
- Controls must alter local output or invoke real available actions, never pretend to save or deploy.
- Unverified actions and tests cannot be labeled successful.
- Selection is NOT approval. Approval is NOT execution. Execution is NOT verification.
- Use progressive disclosure, narrow-screen-friendly composition and descriptive labels.
- Expose uncertainty and evidence proportionally to the stakes.
- Invent new patterns only for genuine benefit; register candidates with contracts and checks.
- If rich UI is unavailable, use UX14 Recovery Protocol.

## Interaction contract

Each reusable pattern must define: ID, name, use case, trigger, input schema, state model, event transitions, approval policy, output contract, evidence requirements, accessibility, fallback, tests, and maturity.

## Validation status

SPECIFIED means design documented, PROTOTYPED means a working local example observed, TESTED means formal tests with evidence, APPROVED requires authorized decision. The seven primitives are design candidates, not a shipped interactive SDK.