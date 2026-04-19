# Hi, I'm Sima Bagheri 👋

**AI Governance · Release Readiness · Enterprise AI Platforms · Multi-Agent Systems**

Building trustworthy, auditable AI for regulated industries — healthcare, financial services, insurance, and government.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/simaba/)
[![Medium](https://img.shields.io/badge/Medium-Read-000000?style=flat-square&logo=medium)](https://medium.com/@bagheri.sima)
[![NIST AI RMF](https://img.shields.io/badge/NIST%20AI%20RMF-Aligned-0055A4?style=flat-square)](https://airc.nist.gov/home)

---

## The Ecosystem

All repositories form an interconnected governance and reliability framework:

```mermaid
flowchart TD
    GOV["🏛️ governance-playbook<br/>End-to-end governance framework"]
    REL["✅ release-checklist<br/>Release gate CLI · install from source"]
    NIST["📋 nist-rmf-guide<br/>NIST AI RMF practitioner guide"]
    RELGOV["🔄 release-governance<br/>Release lifecycle governance"]
    ACC["🔍 accountability-patterns<br/>Accountability design patterns"]
    MA["🕸️ multi-agent-governance<br/>Multi-agent oversight & trust"]
    MAOP["⚙️ agent-orchestration<br/>Orchestration pattern catalog"]
    EVAL["📊 agent-eval<br/>Agent evaluation dimensions"]
    SIM["🧪 agent-simulator<br/>Agent behavior simulation"]
    LSS["📈 lean-ai-ops<br/>AI Process Excellence · Lean Six Sigma"]
    STARTER["🚀 regulated-ai<br/>Template repo for regulated AI teams"]
    PRISM["⭐ ai-prism<br/>PRISM · Curated governance resources"]

    GOV --> REL
    GOV --> NIST
    NIST --> RELGOV
    RELGOV --> REL
    GOV --> ACC
    ACC --> MA
    MA --> MAOP
    MA --> EVAL
    EVAL --> SIM
    SIM --> LSS
    GOV --> STARTER
    PRISM -.->|curates| GOV
```

---

## Featured Repositories

### Governance & Risk

| Area | Repository | What it solves |
|---|---|---|
| Organizational Governance | [governance-playbook](https://github.com/simaba/governance-playbook) | End-to-end AI governance framework — policies, roles, NIST AI RMF implementation |
| NIST AI RMF | [nist-rmf-guide](https://github.com/simaba/nist-rmf-guide) | Practitioner guide to NIST AI RMF with EU AI Act cross-reference |
| Accountability | [accountability-patterns](https://github.com/simaba/accountability-patterns) | Design patterns for human oversight, transparency, and redress |

### Release & Deployment

| Area | Repository | What it solves |
|---|---|---|
| Release Gates | [release-checklist](https://github.com/simaba/release-checklist) | YAML-based release checklist + `release-checklist` CLI · install from source (PyPI coming soon) |
| Release Lifecycle | [release-governance](https://github.com/simaba/release-governance) | Full release lifecycle governance — from development through retirement |
| Starter Template | [regulated-ai](https://github.com/simaba/regulated-ai) | GitHub template: governance docs + CI gates ready to use |

### Multi-Agent & Evaluation

| Area | Repository | What it solves |
|---|---|---|
| Multi-Agent Governance | [multi-agent-governance](https://github.com/simaba/multi-agent-governance) | Oversight, trust models, and accountability for multi-agent AI |
| Orchestration | [agent-orchestration](https://github.com/simaba/agent-orchestration) | Routing, delegation, validation, and failure handling patterns |
| Agent Evaluation | [agent-eval](https://github.com/simaba/agent-eval) | Evaluation dimensions and scenarios for production AI agents |
| Simulation | [agent-simulator](https://github.com/simaba/agent-simulator) | Simulate agent behavior and failure modes before deployment |
| Process Excellence | [lean-ai-ops](https://github.com/simaba/lean-ai-ops) | AI Process Excellence Engine — DMAIC with Black Belt analytics |

### Resources

| Area | Repository | What it solves |
|---|---|---|
| Curated Resources | [ai-prism](https://github.com/simaba/ai-prism) | PRISM — 50+ curated governance frameworks, tools, regulations, and communities |

---

## Open-Source Tools

```bash
# Validate AI release readiness from the command line
# Install from source (PyPI package coming soon)
git clone https://github.com/simaba/release-checklist.git
cd release-checklist
python -m pip install -e .
release-checklist init --industry healthcare
release-checklist validate configs/medium-risk-example.yaml
release-checklist report configs/medium-risk-example.yaml --format markdown
```

---

*Building in the open. All frameworks are MIT licensed and free to use.*
*[Discussions](https://github.com/simaba/governance-playbook/discussions) · [LinkedIn](https://www.linkedin.com/in/simaba/) · [Medium](https://medium.com/@bagheri.sima)*
