# Hi, I'm Sima Bagheri

**AI Governance · Release Readiness · Enterprise AI Platforms · Multi-Agent Systems · Process Excellence**

I build open-source tools, templates, and frameworks for trustworthy, auditable AI in regulated and high-accountability environments.

My focus: making AI systems **releasable**, **accountable**, and **governable**, not just capable.

[LinkedIn](https://www.linkedin.com/in/simaba/) · [Medium](https://medium.com/@bagheri.sima) · NIST AI RMF-informed practitioner work

---

## What I'm building

I work at the intersection of AI systems and operational rigor: governance frameworks, release-readiness tools, accountability patterns, agent-evaluation methods, and process-improvement applications.

The goal is practical: help teams move from AI principles to operating artifacts they can review, adapt, test, and improve.

## Featured repositories

### Governance and risk

**[governance-playbook](https://github.com/simaba/governance-playbook)**  
End-to-end AI governance operating model for intake, prioritization, release, monitoring, and continuous improvement.

**[nist-rmf-guide](https://github.com/simaba/nist-rmf-guide)**  
Practitioner guide for applying NIST AI RMF with related EU AI Act and ISO/IEC 42001 mapping notes.

**[accountability-patterns](https://github.com/simaba/accountability-patterns)**  
Design patterns for ownership, oversight, escalation, appeal, redress, and auditability.

### Release readiness

**[release-governance](https://github.com/simaba/release-governance)**  
Release lifecycle framework for AI systems, from development through deployment, monitoring, and retirement.

**[release-checklist](https://github.com/simaba/release-checklist)**  
Working CLI for validating YAML-based AI release-readiness configurations.

**[regulated-ai](https://github.com/simaba/regulated-ai)**  
Template repository with governance documents, release stubs, model-card templates, and starter workflows.

### Agent systems and evaluation

**[multi-agent-governance](https://github.com/simaba/multi-agent-governance)**  
Governance and oversight patterns for multi-agent AI systems.

**[agent-orchestration](https://github.com/simaba/agent-orchestration)**  
Pattern catalog for routing, delegation, validation, and failure handling.

**[agent-eval](https://github.com/simaba/agent-eval)**  
Evaluation framework for agent performance, safety, reliability, and governance evidence.

**[agent-simulator](https://github.com/simaba/agent-simulator)**  
Runnable demo for simulating bounded agent behavior, retries, escalation, and failure modes.

### Process excellence

**[lean-ai-ops](https://github.com/simaba/lean-ai-ops)**  
AI-assisted Lean Six Sigma app for turning messy process problems into DMAIC-style improvement packages, analytics, and exports.

### Resources

**[ai-prism](https://github.com/simaba/ai-prism)**  
Curated resource hub for AI governance frameworks, tools, standards, papers, and communities.

## Writing to implementation

My Medium articles explore operating-layer problems in AI governance and delivery. These repositories translate those ideas into reusable implementation artifacts:

- Release readiness: `release-governance` and `release-checklist`
- Accountability and human oversight: `accountability-patterns`
- Regulated-AI readiness: `nist-rmf-guide` and `regulated-ai`
- Agent-system control: `multi-agent-governance`, `agent-eval`, and `agent-simulator`
- Process improvement: `lean-ai-ops`

## Try a working tool

```bash
git clone https://github.com/simaba/release-checklist.git
cd release-checklist
python -m pip install -e .
release-checklist init --industry healthcare
release-checklist validate configs/medium-risk-example.yaml
release-checklist report configs/medium-risk-example.yaml --format markdown
```

## Principles

- Clear artifact types: tools, frameworks, templates, and references should not be confused.
- Truthful maturity labels: prototypes should not be presented as finished products.
- Evidence discipline: claims, assumptions, and gaps should be separated clearly.

## Scope

These repositories are practitioner resources shared in a personal capacity. They are not legal advice, compliance certification, regulatory approval, safety certification, or official guidance from NIST, the EU, ISO, or any employer.

Most repositories are MIT licensed. `ai-prism` is released under CC0.
