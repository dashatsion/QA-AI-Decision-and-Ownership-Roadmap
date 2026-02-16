# Decision Patterns for AI QA Governance

This document describes recurring decision patterns that emerge when QA teams work with AI-powered systems.

These patterns help structure discussions around risk, ownership, and operational responsibility.

---

## 1️⃣ AI Adoption Pattern

When introducing AI into a system, teams often focus on capability before necessity.

Use this pattern to evaluate whether AI is justified.

Key checks:
- Does AI provide measurable improvement?
- Can deterministic logic achieve similar results?
- What new risks are introduced?
- Who owns AI behavior post-release?

This pattern prevents unnecessary complexity and long-term operational debt.

---

## 2️⃣ Risk-Based Release Gating Pattern

AI systems operate under uncertainty.  
Release decisions should reflect risk exposure, not only test completion.

Key checks:
- Are confidence thresholds defined?
- Are high-impact failure scenarios identified?
- Is there a clear release blocking policy?
- Who approves risk acceptance?

This pattern ensures AI releases are governed, not rushed.

---

## 3️⃣ Human-in-the-Loop Pattern

Some AI decisions require structured oversight.

Apply this pattern when:
- Outputs affect users directly
- Actions are irreversible
- Model confidence is low
- Regulatory impact exists

Key checks:
- Are review thresholds defined?
- Is routing automated based on confidence?
- Are manual overrides available?

Human oversight is governance — not regression.

---

## 4️⃣ Agent Governance Pattern

AI agents differ from APIs.

They:
- plan steps
- retry autonomously
- select tools dynamically
- act with operational impact

Key checks:
- Are execution limits enforced?
- Are tool outputs validated?
- Are retry caps defined?
- Is a kill switch available?

Agents must be governed as autonomous systems, not endpoints.

---

## 5️⃣ Drift & Trust Monitoring Pattern

AI behavior evolves over time.

Quality does not end at release.

Key checks:
- Is performance monitored continuously?
- Are trust signals tracked?
- Are user complaints analyzed systematically?
- Are model updates governed?

This pattern shifts QA from reactive validation to proactive risk management.

---

## 6️⃣ Ownership Alignment Pattern

AI quality spans QA, engineering, and product.

Ambiguity in ownership leads to unmanaged risk.

Key checks:
- Is responsibility for model behavior defined?
- Are escalation paths documented?
- Are incident response roles clear?

Explicit ownership reduces operational chaos.

---

## How to Apply These Patterns

Decision patterns are not sequential steps.

Instead:
- Identify the system type (deterministic, probabilistic, agent-based)
- Assess risk level
- Select relevant patterns
- Use them to guide structured team discussions

The goal is not compliance — it is clarity.
