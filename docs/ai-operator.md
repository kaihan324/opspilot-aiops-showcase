# AI Operator

The OpsPilot AI layer is designed as an **operator assistant**, not an unrestricted autonomous infrastructure controller.

## Responsibilities

- summarize current incident evidence
- explain likely causes
- suggest checks and next steps
- compare signals from multiple sources
- answer general infrastructure questions
- continue incident-oriented follow-ups across Persian and English

## Grounding

Known status and incident questions should prefer deterministic live evidence. The AI layer is used to interpret, explain, and structure that evidence.

## Degraded mode

If the remote AI provider is unavailable or rate-limited, core monitoring, diagnostics, playbooks, reporting, and deterministic operational views should continue to function.

## Safety boundary

The AI can recommend sensitive actions, but production-changing operations remain human-approved.