# Sima Bagheri

**Technical program and product management for AI systems, evaluation, governance, and operational decision-making**

I build open-source tools and practitioner methods for work that sits between product intent and accountable operation: defining what an AI-enabled system may do, designing evidence that can support a decision, validating structured artifacts, and making failure, uncertainty, ownership, and change visible.

[LinkedIn](https://www.linkedin.com/in/simaba/) · [Medium](https://medium.com/@bagheri.sima)

## Selected work

These repositories best represent the portfolio because they contain working behavior, explicit decision rules, or developed methods—not only topic summaries.

| Repository | What is implemented | Why it matters |
|---|---|---|
| [`everything-program-management`](https://github.com/simaba/everything-program-management) | Authored methods for charters, RAID, triage, decision memos, stakeholder analysis, and briefs; JSON schemas and a validation CLI | Separates evidence, assumptions, hard constraints, ownership, and follow-through in everyday program work |
| [`release-checklist`](https://github.com/simaba/release-checklist) | Packaged Python CLI, YAML configuration, semantic validation, reports, tests, and matrix CI | Makes release-readiness claims inspectable instead of relying on a completed document or meeting |
| [`agent-eval`](https://github.com/simaba/agent-eval) | Evaluation-report schema, semantic validator, fictional examples, and a detailed evidence-validity method | Connects metrics to a population, evaluator, uncertainty, hard gates, and a bounded product or release decision |
| [`regulated-ai`](https://github.com/simaba/regulated-ai) | Starter repository with tested release-decision validation and fictional evidence records | Demonstrates how a governance template can check decision coherence without pretending to certify safety or compliance |
| [`agent-simulator`](https://github.com/simaba/agent-simulator) | Runnable retry, fallback, escalation, and failure scenarios; tests; clean-wheel installation check | Turns agent-control language into behavior that can be executed and inspected |
| [`lean-ai-ops`](https://github.com/simaba/lean-ai-ops) | Structured improvement application with explicit live-model versus deterministic-fallback provenance | Shows how AI-generated analysis can remain useful without hiding where the output came from or overstating weak evidence |

## Developed frameworks

### Release and organizational governance

- [`release-governance`](https://github.com/simaba/release-governance) — scoped release propositions, evidence freshness, hard gates, conditions, exceptions, residual risk, and invalidation triggers.
- [`governance-playbook`](https://github.com/simaba/governance-playbook) — governance as an intake, evidence, decision, and follow-through service rather than a list of committees.
- [`accountability-patterns`](https://github.com/simaba/accountability-patterns) — decision rights, meaningful human review, minimal provenance, explanation, correction, appeal, and control trade-offs.
- [`nist-rmf-guide`](https://github.com/simaba/nist-rmf-guide) — evidence-based practitioner navigation of NIST AI RMF without maturity-score theater or claims of implementation by template.

### Agent authority and control flow

- [`multi-agent-governance`](https://github.com/simaba/multi-agent-governance) — authority envelopes, propagation controls, human authorization, containment, and recovery.
- [`agent-orchestration`](https://github.com/simaba/agent-orchestration) — state, evidence, authority, retry, delegation, fallback, circuit-breaker, and escalation contracts.
- [`mcp-agent-risk-checklist`](https://github.com/simaba/mcp-agent-risk-checklist) — principal binding, effective tool authority, data reach, invocation controls, supply chain, and recovery for MCP integrations.

### Product, evaluation, and traceability tools

- [`ai-platform-pm-playbook`](https://github.com/simaba/ai-platform-pm-playbook) — behavior contracts, stage-specific evidence, product error budgets, rollout controls, and build-versus-buy decisions.
- [`automotive-llm-eval-harness`](https://github.com/simaba/automotive-llm-eval-harness) — synthetic evaluation cases, hard-gate semantics, run manifests, and reproducibility records for a bounded automotive domain example.
- [`harness-bench`](https://github.com/simaba/harness-bench) — normalized run-artifact scoring plus a contract for deciding when cross-harness results are actually comparable.
- [`prompt-harness-translator`](https://github.com/simaba/prompt-harness-translator) — narrow, tested translation of supported agent/prompt artifacts across documented target formats.
- [`decision-journal-agent`](https://github.com/simaba/decision-journal-agent) — local Markdown decision capture, review, due-date handling, and calibration-oriented follow-up.
- [`ai-act-compliance-agents`](https://github.com/simaba/ai-act-compliance-agents) — structured traceability drafting and accountable-review support using fictional or sanitized inputs.

## How the work connects

The repositories share a common operating sequence:

```text
define the decision, user, scope, and authority
                    ↓
state hard constraints, uncertainty, and evidence needs
                    ↓
build or validate the artifact, workflow, or evaluation
                    ↓
inspect failures, disagreement, and partial execution
                    ↓
record the decision, owner, conditions, and residual risk
                    ↓
monitor changes that invalidate the evidence or approval
```

That sequence is more important than any single framework name. It keeps governance connected to product behavior and operational reality.

## Working principles

- **Evidence classes matter.** Measured facts, estimates, assumptions, interpretations, and unknowns should not be blended into one confident narrative.
- **Hard constraints are not weighted criteria.** A quality score should not compensate for an unauthorized action, sensitive-data boundary failure, or other non-compensable condition.
- **Authority must be enforceable.** Tool and data boundaries belong in identity, permission, and execution controls—not only prompts.
- **A second agent is not automatically an independent reviewer.** Common models, context, retrieval, rubrics, and incentives can create common-mode failure.
- **A valid schema is not a valid decision.** Validation can catch contradictions and missing structure; it cannot prove evidence quality, safety, legality, or value.
- **Claims should be bounded.** A small synthetic suite can support a finding about that suite and version, not a universal ranking or safety claim.
- **Failure handling is part of the product.** Retry, partial state, cancellation, containment, rollback, correction, and redress deserve first-class design.

## Other resources

- [`ai-prism`](https://github.com/simaba/ai-prism) — curated public AI-governance and security resources with review status and automated link checking.
- [`.github`](https://github.com/simaba/.github) — shared contribution, security, and public-release guidance.

## Scope

This is personal open-source practitioner work. It does not represent an employer and is not legal advice, regulatory approval, compliance certification, safety certification, or official guidance from NIST, the EU, ISO, or any platform provider. Examples are intended to be fictional, synthetic, public, or fully sanitized.
