# 12 — AI / Intelligence

> Part of the **Hermes Organizational Decision System**. This repo is the
> **AI / Intelligence** line. It references the shared ontology in
> [`00-kojiki-ontology`](https://github.com/hermes-ios/00-kojiki-ontology) for the
> canonical schemas, taxonomy, decision-rights, and handoff standards.

## Primary question
> What can we augment, automate, or learn?

## Purpose
Augment decisions and automate suitable workflows while learning from human and system outcomes.

## Sub-functions
AI Strategy, AI Engineering, Agent Engineering, Automation, Knowledge Engineering, Evaluation, AI Operations, AI Governance

## Typical roles
Chief AI Officer, VP AI, Head of AI, AI Director, AI Engineer, ML Engineer, Agent Engineer, Evaluation Engineer

## Inputs
Decisions, workflows, historical cases, human outcomes, system telemetry, constraints.

## Outputs
Augmented decisions, automations, agents, evaluations, governance controls, learned patterns.

## Learning focus
Agent failure modes; confidence calibration; human overrides; automation ROI; reusable reasoning patterns.

## Operating tree
```text
CURRENT DECISION →
    HUMAN PROCESS →
    DECISION COMPLEXITY →
    INPUTS →
    DATA AVAILABILITY →
    AUTOMATION POTENTIAL →
    AGENT DESIGN →
    HUMAN CONTROL →
    EXECUTION →
    VERIFICATION →
    OUTCOME →
    AGENT LEARNING
```

## Decision states
```text
ASSESSED → DESIGNED → CONTROLLED → EXECUTING → VERIFYING → MONITORING → IMPROVING → REJECTED
```

## Decision outputs
`Automate · Assist · Escalate · Reject · Monitor · Improve`

## Critical prompts (what this function thinks about)
> What decision are we automating?
> Why automate it?
> What inputs are required?
> What context is required?
> What reasoning is required?
> What can the agent decide?
> What must remain human?
> What evidence must the agent collect?
> How does it know when it is uncertain?
> How does it know when it is wrong?
> What verification is required?
> What happens when confidence is low?
> What is the cost of failure?
> How will agent performance be measured?
> What historical decisions can train the system?
> What should the agent learn?

## Canonical record schema (docx Learning Ledger + Decision Object Fields)
Every decision in this line is recorded as:
- a **Decision Object** (docx S9) — see `schema/decision-object.json`
- a **Learning Ledger** entry (docx S7) — see `schema/learning-ledger.json`

and the agent must run the **Orientation Protocol** first (see `AGENT.md`).

## How to use
1. Read `AGENT.md` — the first-run Orientation Protocol.
2. Read `SCHEMA.md` — how this line maps to the universal schema.
3. Read `data/12-ai-intelligence.json` — the machine-readable spec.
4. See `data/example.json` — one fully worked decision (Decision Object + Ledger).
5. Use `decision-graph.mmd` — agent-decodable operating tree + state model.
6. Validate new records: `python3 tools/validate.py data/<name>.json`
