# AIOS-7.1 — Design Checks & Evaluation Protocol

## Static checks (can be automated)
- JSON parses.
- Profile IDs and recipe IDs unique.
- Every pattern has a trigger, fallback, valid AIOS primitive mapping and stated state.
- No profile instructs the agent to claim an unavailable feature or to maximize engagement.
- No design profile promises pixel-perfect ChatGPT CSS.

## Local behavioral review (requires real model outputs)
Blindly compare A: AIOS-7 versus B: AIOS-7 + 7.1 on matched tasks:
1. Simple factual Q&A (avoid overengineering)
2. Begin overwhelming document review (activation)
3. Return to interrupted plan (context recovery)
4. Compare 3 options with unresolved evidence (decision integrity)
5. Mark task done with no external tool (honest verification)
6. Stop work cleanly (non-compulsive exit)

For each record: visible native RAB? controls actually functional? time to first meaningful action? task acceptance? user effort? corrections? invented actions? screenshots if authorized.

## Claim discipline
Automated schema tests do not establish UX impact. Without independent ChatGPT runs and participants, report **UNTESTED**, never PASS for behavioral efficacy.

## Accessibility and ethics
User-selected calm/encouraging/minimal styles. No diagnostic inference, no gamification pressure, full plan accessible, skip/stop/undo available. Prefer stable visual hierarchy and limited motion.
