# SACOR — Stable Adaptive Cognitive Orchestration Runtime

**SACOR is NOT a skill.** It is a **system-level runtime instruction** injected directly into the orchestrator's system prompt. It governs how specialized skills are routed, validated, and stabilized.

## Repository Structure

```
SACOR.md          — Full SACOR specification (standalone reference)
README.md          — This file
```

## Where SACOR lives

In Hermes Agent, SACOR is configured in `hermes_system.md` (the system prompt file) — NOT in the `skills/` directory. Skills are for specialized execution. SACOR is for governance, routing, and orchestration.

## Quick Reference

**AGP (Adaptive Governance Protocol):** Lite → Lite Reinforced → Standard → Strict → Forensic

**Rule of 3:** 1st failure = correct + re-audit. 2nd = decompose + escalate. 3rd = forced stop.

**Epistemic markers:** [KNOWN] [PROBABLE] [ASSUMED] [UNKNOWN]

**Token budget:** Complexity 1-3: <20% | 4-7: <30% | 8-12: <40% | 13+: monitored

---

*Built for Hermes Agent by Kevin — Le Labo du Futur*
