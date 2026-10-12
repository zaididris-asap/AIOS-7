# AIOS-7.1 Native RAB Recipes

All recipes are **semantic**. Choose real components the current chat supports.

## RAB-STYLE-01 · Decision Lens
- Trigger: Single consequential choice with 2–4 alternatives
- Profiles: editorial, studio
- Universal functions: U01, U03, U04, U05, U06, U07
- Controls: radio-group or pressables; request analysis button
- States: UNSELECTED → PRELIMINARY → REVIEW_REQUESTED
- Fallback: Numbered alternatives and a one-line selection syntax
- Evidence state: **SPECIFIED / NOT INDEPENDENTLY TESTED**


## RAB-STYLE-02 · Quiet Action Surface
- Trigger: Explicit Focus Mode with task-starting friction
- Profiles: focus
- Universal functions: U01, U02, U03, U04, U06, U07
- Controls: mark self-reported complete; show full plan; pause
- States: READY → USER_REPORTED → PAUSED → COMPLETE_USER_REPORTED
- Fallback: One next step and optional full plan
- Evidence state: **SPECIFIED / NOT INDEPENDENTLY TESTED**


## RAB-STYLE-03 · Evidence Fold
- Trigger: Claims requiring inspection or competing evidence
- Profiles: editorial, signal
- Universal functions: U03, U05, U06
- Controls: expand details when available
- States: COLLAPSED → EXPANDED
- Fallback: Citations and compact caveats
- Evidence state: **SPECIFIED / NOT INDEPENDENTLY TESTED**


## RAB-STYLE-04 · Return Dock
- Trigger: Known previous task and user asks to resume
- Profiles: focus, studio
- Universal functions: U01, U02, U06, U07
- Controls: resume; copy handoff
- States: CONTEXT_AVAILABLE → CONTEXT_PARTIAL → MISSING
- Fallback: Last supported state, blocker, next action
- Evidence state: **SPECIFIED / NOT INDEPENDENTLY TESTED**



## Unavailable components

If a specialized widget is absent, choose an equivalent supported layout or structured text. Only trigger UX14 context transfer when genuinely meaningful rich UI is unavailable in the session and would help the task.

## Registry quality

Before inventing a new pattern, compare with existing recipes. New IDs require different functional behavior or a distinct user outcome, not cosmetic variation. Submit changes for review before promoting to public release.
