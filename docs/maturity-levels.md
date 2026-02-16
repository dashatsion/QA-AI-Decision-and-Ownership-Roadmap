# AI QA Maturity Levels

This model describes how QA organizations evolve when working with AI-powered systems.

Maturity is not about the number of automated tests.  
It reflects how well risk, ownership, and autonomy are governed.

---

## Level 0 — Classical QA Mindset

AI is treated like deterministic software.

Characteristics:
- Pass/fail assertions dominate
- Variance is labeled as flakiness
- No distinction between probabilistic and deterministic behavior
- Ownership for model behavior is unclear

Risk:
Teams underestimate uncertainty and misclassify failures.

---

## Level 1 — Reactive AI Testing

AI testing practices exist, but are incident-driven.

Characteristics:
- Evaluation added after production issues
- Manual fixes follow user complaints
- Human review is inconsistent
- Release criteria remain deterministic

Risk:
Quality improves only after visible damage.

---

## Level 2 — Structured Evaluation

Teams adopt evaluation frameworks and structured testing.

Characteristics:
- Confidence thresholds defined
- Failure patterns tracked
- AI-specific test scenarios documented
- Basic ownership boundaries clarified

Risk:
Governance is present but limited to testing scope.

---

## Level 3 — Ownership Alignment

AI quality becomes cross-functional.

Characteristics:
- Clear QA, engineering, and product responsibilities
- Risk-based release gating
- Human-in-the-loop policies defined
- Escalation paths documented

Risk:
Operational drift may still occur without continuous monitoring.

---

## Level 4 — Agent-Aware Governance

Autonomous systems are treated differently from APIs.

Characteristics:
- Execution limits enforced
- Kill switches implemented
- Tool validation monitored
- Irreversible actions explicitly governed

Risk:
Complexity grows as AI adoption scales.

---

## Level 5 — Proactive AI Governance

QA transitions from reactive validation to proactive risk management.

Characteristics:
- Drift detection integrated
- Trust signals monitored
- Organizational AI policies documented
- Continuous governance reviews performed

Risk:
Scaling challenges require cultural alignment.

---

## How to Use This Model

This maturity model is not a certification checklist.

Use it to:
- Assess current state
- Identify structural gaps
- Prioritize governance improvements
- Align leadership discussions

Progression is incremental.  
Maturity grows when decision-making becomes structured, not when tooling increases.
