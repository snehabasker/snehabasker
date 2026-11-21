## Hi, I'm Sneha 👋

**AI & data engineer.** I build LLM agents, knowledge graphs and RL training pipelines that are measured, tested and deployable, not just demos. Every project below ships with an evaluation, a baseline it has to beat, and an honest note on what has *not* been verified yet.

### Featured projects

| Project | What it does | Headline result |
|---|---|---|
| [**PortalPilot**](https://github.com/snehabasker/portalpilot) | Durable, human-supervised AI agent that operates enterprise web portals with no API. Temporal workflows, Playwright, a fine-tuned 2B Qwen2-VL click policy, deployed on AWS with Terraform | **91.3% verified clicks** on an unseen portal; exactly-once filing under pop-ups, 503 storms, MFA and a worker killed mid-batch |
| [**SupplyGraph**](https://github.com/snehabasker/supplygraph) | Supplier-risk intelligence on an ontology-backed knowledge graph: GLEIF, OpenSanctions, SEC EDGAR and GDELT → DuckDB → Neo4j, explainable risk propagation, a disruption digital twin, and a Claude agent whose changes are human-approved, audited actions | News story clustering **F1 0.81** vs 0.54 baseline on held-out pairs; React + Cytoscape explorer; Helm chart |
| [**SiliconGym**](https://github.com/snehabasker/SiliconGym) | RL environment for LLM-written Verilog: GRPO/PPO on Icarus Verilog simulator rewards, multi-turn tool use, and a study of reward hacking | GRPO on a free T4: **pass@8 0.25 → 0.58** on unseen design families |
| [**analytics-agent**](https://github.com/snehabasker/analytics-agent) | Text-to-SQL analytics agent: LangGraph, a semantic layer, Qdrant retrieval, DSPy prompt optimisation, guardrails, MLflow tracking | **100%** must-refuse safety recall, **0%** false refusals, eval gate in CI |

### Toolbox

**LLMs & agents:** Claude, LangGraph, DSPy, RAG / GraphRAG, Qdrant, vision-language models, LoRA fine-tuning<br>
**ML & RL:** PyTorch, TRL (GRPO/PPO), JAX, physics-informed neural networks<br>
**Data:** Neo4j, DuckDB, Postgres, Spark / Delta, Airflow, data-quality checks<br>
**Platform:** FastAPI, Temporal, Docker, Kubernetes / Helm, Terraform, AWS, Prometheus / Grafana, GitHub Actions<br>
**Frontend:** React, TypeScript, Cytoscape.js

### How I work

- **Evaluate first.** Gold sets, held-out splits, baselines, and thresholds tuned on dev and reported on test.
- **Humans approve consequential actions.** Agents propose; changes are audited.
- **Fail loudly in production.** Retries, idempotency, game days and postmortems.
