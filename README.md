# Mohamed Ben Lakhoua

**Fractional CTO · Platform & FinOps** — [metafive.ai](https://www.metafive.ai) · [linkedin.com/in/benlakhoua](https://linkedin.com/in/benlakhoua) · [mo@metafive.ai](mailto:mo@metafive.ai)

I design the architecture and govern the agents that implement it. AI accelerates delivery; humans own every merge.

## Flagships

Two repos worth cloning. The rest is supporting material.

| Repo | Clone this if you need |
|---|---|
| **[aws-finops-cost-optimizer](https://github.com/mlakhoua-rgb/aws-finops-cost-optimizer)** | Find idle AWS spend (unattached EBS, unused EIPs, over-provisioned EC2) with dollar estimates. Read-only analysis first; Terraform automation is dry-run / opt-in. |
| **[agent-constitution](https://github.com/mlakhoua-rgb/agent-constitution)** | Run multiple AI coding agents on a production codebase without losing decisions, evidence, or review. Constitution + append-only decision log + CI gates. |

```bash
# FinOps — no deploy required
git clone https://github.com/mlakhoua-rgb/aws-finops-cost-optimizer.git
cd aws-finops-cost-optimizer && pip install -r scripts/requirements.txt
python scripts/unused_resources.py --region eu-west-1 --output unused.json
```

## Supporting repos

| Repo | What it is |
|---|---|
| [service-level-management](https://github.com/mlakhoua-rgb/service-level-management) | SLM blueprint: SLA/OLA design, multi-cloud patterns, observability-driven monitoring |
| [aws-monitoring-observability-stack](https://github.com/mlakhoua-rgb/aws-monitoring-observability-stack) | Prometheus / Grafana / CloudWatch on AWS — configs validated in CI |
| [ai-governance-platform-blueprint](https://github.com/mlakhoua-rgb/ai-governance-platform-blueprint) | Reference architecture for AI-governed engineering of regulated platforms |

## Background

30 years of platform work: Abu Dhabi e-Government, init AG (NATO, EPO, BSI), The Sandbox / Animoca Brands (DORA Elite, FinOps savings). Now building [Metafive](https://www.metafive.ai).

**Stack** — AWS · Azure · OpenShift · Kubernetes · Terraform · GitOps · Prometheus · Grafana  
**Governance** — ISO 27001 · ISO 22301 · SOC 2 · GDPR · BSI IT-Grundschutz · EU AI Act

## Contact

[mo@metafive.ai](mailto:mo@metafive.ai) · [LinkedIn](https://linkedin.com/in/benlakhoua) · [metafive.ai](https://www.metafive.ai)
