# Hi, I'm Sima Bagheri

**AI governance | release readiness | enterprise AI operating models | multi-agent systems | process excellence**

I build open-source repositories around trustworthy, auditable AI for regulated and high-accountability environments.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/simaba/)
[![Medium](https://img.shields.io/badge/Medium-Read-000000?style=flat-square&logo=medium)](https://medium.com/@bagheri.sima)
[![NIST AI RMF](https://img.shields.io/badge/NIST%20AI%20RMF-Informed-0055A4?style=flat-square)](https://airc.nist.gov/home)

## Portfolio guide

Use this guide to choose the right starting point:

| Goal | Start with | Maturity |
|---|---|---|
| Understand the full operating model for enterprise AI | [`governance-playbook`](https://github.com/simaba/governance-playbook) | Practitioner playbook |
| Validate AI release readiness with a working CLI | [`release-checklist`](https://github.com/simaba/release-checklist) | Alpha working tool |
| Understand release-stage governance | [`release-governance`](https://github.com/simaba/release-governance) | Framework |
| Apply NIST AI RMF in practice | [`nist-rmf-guide`](https://github.com/simaba/nist-rmf-guide) | Practitioner guide |
| Start a new regulated-AI repository from a template | [`regulated-ai`](https://github.com/simaba/regulated-ai) | Template repository |
| Explore multi-agent governance and control patterns | [`multi-agent-governance`](https://github.com/simaba/multi-agent-governance) | Framework |
| See runnable multi-agent behavior in code | [`agent-simulator`](https://github.com/simaba/agent-simulator) | Runnable demo |
| Use AI for structured process-improvement work | [`lean-ai-ops`](https://github.com/simaba/lean-ai-ops) | Working app |
| Browse curated governance resources | [`ai-prism`](https://github.com/simaba/ai-prism) | Resource hub |

## Medium article map

My Medium articles describe operating problems in AI governance and delivery. These repositories translate those ideas into reusable artifacts, templates, and tools.

| Medium theme | Use this repository | Practical next step |
|---|---|---|
| Why AI governance fails in safety-critical or regulated systems | [`governance-playbook`](https://github.com/simaba/governance-playbook) | Adapt the operating-model template |
| AI release readiness as the missing operational layer | [`release-checklist`](https://github.com/simaba/release-checklist) | Run the sample YAML validator |
| Release gates as accountability and readiness controls | [`release-governance`](https://github.com/simaba/release-governance) | Compare the lifecycle gates with the CLI checks |
| Human-in-the-loop is not enough without ownership and redress | [`accountability-patterns`](https://github.com/simaba/accountability-patterns) | Fill the accountability matrix |
| AI roadmaps should be governed by risk, value, and execution reality | [`governance-playbook`](https://github.com/simaba/governance-playbook) | Use the intake and prioritization artifacts |
| EU AI Act and regulated-AI readiness | [`nist-rmf-guide`](https://github.com/simaba/nist-rmf-guide), [`regulated-ai`](https://github.com/simaba/regulated-ai), [`ai-prism`](https://github.com/simaba/ai-prism) | Start with a gap assessment and template kit |
| Multi-agent systems need control logic, evaluation, and escalation paths | [`multi-agent-governance`](https://github.com/simaba/multi-agent-governance), [`agent-eval`](https://github.com/simaba/agent-eval), [`agent-simulator`](https://github.com/simaba/agent-simulator) | Review the evaluation framework, then run the simulator |

## Portfolio map by artifact type

### Working tools and apps

| Repository | Type | What it does |
|---|---|---|
| [`release-checklist`](https://github.com/simaba/release-checklist) | CLI | Validates YAML-based release-readiness configurations |
| [`agent-simulator`](https://github.com/simaba/agent-simulator) | Runnable demo | Simulates bounded multi-agent workflows |
| [`lean-ai-ops`](https://github.com/simaba/lean-ai-ops) | Streamlit app | Generates DMAIC-style improvement packages with analytics |

### Frameworks and practitioner guides

| Repository | Type | What it does |
|---|---|---|
| [`governance-playbook`](https://github.com/simaba/governance-playbook) | Playbook | End-to-end AI operating model |
| [`release-governance`](https://github.com/simaba/release-governance) | Framework | Release lifecycle governance and gates |
| [`nist-rmf-guide`](https://github.com/simaba/nist-rmf-guide) | Guide | Practitioner implementation guide for NIST AI RMF |
| [`accountability-patterns`](https://github.com/simaba/accountability-patterns) | Pattern catalog | Accountability, oversight, and redress patterns |
| [`multi-agent-governance`](https://github.com/simaba/multi-agent-governance) | Framework | Trust, oversight, and accountability for multi-agent systems |
| [`agent-orchestration`](https://github.com/simaba/agent-orchestration) | Pattern catalog | Routing, delegation, validation, and failure-handling patterns |
| [`agent-eval`](https://github.com/simaba/agent-eval) | Evaluation framework | Agent evaluation dimensions, scenarios, and reporting structure |

### Templates and reference hubs

| Repository | Type | What it does |
|---|---|---|
| [`regulated-ai`](https://github.com/simaba/regulated-ai) | Template repository | Governance docs, release stubs, and starter workflows |
| [`ai-prism`](https://github.com/simaba/ai-prism) | Reference hub | Curated governance frameworks, tools, standards, and papers |

## How the repositories fit together

```mermaid
flowchart TD
    GOV["governance-playbook"]
    NIST["nist-rmf-guide"]
    RELGOV["release-governance"]
    RELCHK["release-checklist"]
    STARTER["regulated-ai"]
    ACC["accountability-patterns"]
    MAGOV["multi-agent-governance"]
    ORCH["agent-orchestration"]
    EVAL["agent-eval"]
    SIM["agent-simulator"]
    LSS["lean-ai-ops"]
    PRISM["ai-prism"]

    GOV --> RELGOV
    GOV --> NIST
    GOV --> ACC
    RELGOV --> RELCHK
    NIST --> STARTER
    ACC --> MAGOV
    MAGOV --> ORCH
    MAGOV --> EVAL
    EVAL --> SIM
    SIM --> LSS
    PRISM -.-> GOV
    PRISM -.-> NIST
```

## Design principles across the portfolio

- **clear artifact types** so tools, frameworks, templates, and references are not confused
- **truthful maturity labels** so prototypes are not presented as finished products
- **practical usefulness** over theory for its own sake
- **traceability and accountability** wherever decisions, gates, or evaluations are involved
- **evidence discipline** so claims, assumptions, and gaps are separated clearly

## Scope and disclaimer

These repositories are practitioner resources shared in a personal capacity. They are not legal advice, compliance certification, regulatory approval, safety certification, or official guidance from NIST, the EU, ISO, or any employer.

References to NIST AI RMF, EU AI Act, ISO/IEC 42001, and related standards are self-assessed, practitioner mappings. Always verify against official sources before using them for compliance, safety, or release decisions.

## Featured command-line example

```bash
git clone https://github.com/simaba/release-checklist.git
cd release-checklist
python -m pip install -e .
release-checklist init --industry healthcare
release-checklist validate configs/medium-risk-example.yaml
release-checklist report configs/medium-risk-example.yaml --format markdown
```

*Most repositories are MIT licensed. `ai-prism` is released under CC0.*
