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

## Portfolio architecture

The repositories are organized as artifact families, not as a single linear dependency chain.

| Layer | Repositories | Role |
|---|---|---|
| **Reference and standards** | [`ai-prism`](https://github.com/simaba/ai-prism), [`nist-rmf-guide`](https://github.com/simaba/nist-rmf-guide) | Curated references and practitioner mappings for governance, risk, standards, and regulatory concepts |
| **Operating model** | [`governance-playbook`](https://github.com/simaba/governance-playbook), [`accountability-patterns`](https://github.com/simaba/accountability-patterns) | Defines ownership, decision rights, governance routines, accountability, oversight, escalation, and redress |
| **Release readiness** | [`release-governance`](https://github.com/simaba/release-governance), [`release-checklist`](https://github.com/simaba/release-checklist), [`regulated-ai`](https://github.com/simaba/regulated-ai) | Turns governance into release gates, templates, checklists, and reusable starter artifacts |
| **Agent systems** | [`multi-agent-governance`](https://github.com/simaba/multi-agent-governance), [`agent-orchestration`](https://github.com/simaba/agent-orchestration), [`agent-eval`](https://github.com/simaba/agent-eval), [`agent-simulator`](https://github.com/simaba/agent-simulator) | Applies governance, orchestration, evaluation, and simulation patterns to agentic systems |
| **Process excellence** | [`lean-ai-ops`](https://github.com/simaba/lean-ai-ops) | Demonstrates AI-assisted process improvement with DMAIC-style outputs, analytics, and exports |

### Recommended review paths

| Reviewer goal | Suggested path |
|---|---|
| Understand the governance thesis | `governance-playbook` → `accountability-patterns` → `release-governance` |
| See a working tool quickly | `release-checklist` → `lean-ai-ops` → `agent-simulator` |
| Review regulated-AI readiness artifacts | `nist-rmf-guide` → `regulated-ai` → `release-checklist` |
| Evaluate agent-system thinking | `multi-agent-governance` → `agent-orchestration` → `agent-eval` → `agent-simulator` |
| Connect articles to reusable implementation artifacts | Medium articles → relevant repository from the article map above |

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
