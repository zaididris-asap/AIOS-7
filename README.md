# AIOS-7 — Make ChatGPT an interface, not just a chat.

**Seven universal interaction functions. One copy-paste prompt. No backend required.**

AIOS-7 is an experimental, open-source **prompt-first interaction design framework** for ChatGPT. It encourages useful rich cards, controls, comparisons, diagrams and workflow surfaces rather than lengthy plain-text-only answers wherever the interface supports them.

> A prompt cannot enable unsupported UI features, guarantee Rich App Blocks (RABs) on every account, modify model weights, or create cross-chat persistence. AIOS-7 is an independent design framework, not an official OpenAI product.

## Quick start — 30 seconds

1. Open **[AIOS7_PROMPT.md](AIOS7_PROMPT.md)** and copy its contents.
2. Paste into a new ChatGPT conversation or supported project instructions.
3. Describe your actual task as usual. No special commands required.
4. Example: **“Help me choose between three ways to launch my project. Compare trade-offs, let me select provisionally, and distinguish selection from approval.”**

The prompt is portable; **rich interactive rendering varies with product surface, account, model and available tools**. If relevant rich UI cannot render, AIOS offers a useful fallback and the option of a context-transfer note.

## The Seven Universal RAB Functions

| ID | Primitive | Purpose |
|---|---|---|
| RAB-U01 | Identity Header | Subject, context, title, status |
| RAB-U02 | Orientation Navigator | Sections, steps, views |
| RAB-U03 | Core Answer Surface | The actual answer or artifact |
| RAB-U04 | Interaction Controller | Useful selection, editing, filtering |
| RAB-U05 | Evidence & Integrity Lens | Sources, assumptions, uncertainty |
| RAB-U06 | State & Progress Ledger | Proposed vs selected vs approved vs executed vs verified |
| RAB-U07 | Continuation & Recovery Dock | Next action, copying, handoff |

These are seven **semantic functions**, not seven compulsory large cards. Their forms adapt to the task. Correctness and usefulness outweigh novelty or component count.

## Why AIOS-7?

- **Rich interaction where it adds value:** decision cards, evidence inspection, planning navigation, learning checks and more.
- **Protocol intelligence:** source discipline, authority boundaries, execution verification and context handoffs.
- **Functioning controls, not UI theater:** no fake persistence or invented approvals.
- **Adaptive density:** short questions can stay short; complicated work gets appropriate structure.
- **Pattern evolution:** document genuinely reusable interaction designs in a growing registry.
- **Recovery:** when rich interaction is genuinely unavailable, offer a copyable Context Transfer Note.

## Try it

| Ask | Intended pattern |
|---|---|
| “Compare these proposals and let me select one.” | Decision + comparison |
| “Review this contract and identify major issues.” | Document + evidence |
| “Turn this idea into a milestone plan.” | Project navigation |
| “Test my understanding of this topic.” | Learning interaction |
| “What has actually been deployed and tested?” | Evidence-based execution status |

See [examples](examples/TRY_THESE.md) and [pattern registry](docs/RAB_REGISTRY.md).

## Documentation

- [The AIOS-7 master prompt](AIOS7_PROMPT.md)
- [Seven-primitives design specification](docs/SEVEN_PRIMITIVES.md)
- [Pattern registry](docs/RAB_REGISTRY.md)
- [Recovery protocol](docs/RECOVERY.md)
- [Evaluation plan](benchmark/TEST_PLAN.md)
- [Contributing](CONTRIBUTING.md)
- [Release status](docs/RELEASE_STATUS.md)

## Status and integrity

**Public preview — design candidate.** Its specifications and examples are written. Consistent cross-account rich UI support and productivity superiority over ordinary ChatGPT or Rich Blocks-only are **not independently verified**. No 100× productivity claim is made. This repository contains prompts and documentation, not an installed ChatGPT app.

Independent and **not affiliated with or endorsed by OpenAI**. ChatGPT is an OpenAI trademark. “RAB” is a descriptive shorthand for a rich interactive response, not a guarantee of platform support.

## Contributing

Useful examples, counterexamples, accessibility feedback and implementation experiments are welcome. Never commit client-confidential information or API keys.

## License

MIT — see [LICENSE](LICENSE).
