# 🚀 OrbitDeploy — Deployment Orchestration Platform

Multi-cloud deployment platform with automated rollbacks, canary releases, and infrastructure-as-code management.

## Features

- 🚀 **Multi-Cloud Deploy** — Deploy to AWS, GCP, Azure, and edge locations with unified pipeline and automatic region failover.
- 🐤 **Canary Releases** — Gradual rollout with automatic health checks, traffic splitting, and instant rollback on anomaly detection.
- 📝 **GitOps Native** — Infrastructure as code with Git-driven deployments, drift detection, and plan-before-apply workflows.
- 📊 **Deploy Analytics** — Deployment velocity metrics, change failure rate tracking, and MTTR analysis per team and service.

## Quick Start

```bash
npm install -g orbit-deploy
orbit-deploy init my-project
cd my-project
orbit-deploy dev
```

## Stats

- **30s** Deploy Time
- **99.99%** Success Rate
- **4** Cloud Providers
- **0** Downtime

## FAQ

**Does it replace Terraform?**

Works alongside Terraform/Pulumi. We handle deployment orchestration; IaC tools manage state and planning.

**What's the rollback story?**

Automatic rollback on health check failure, plus manual instant rollback. Previous deployment always available.

**How does pricing work?**

Per-deployment pricing with unlimited environments. Start free with 50 deployments/month.


## License

MIT — Built with [MiMo AI](https://100t.xiaomimimo.com/) as part of the 100T Token Initiative.
