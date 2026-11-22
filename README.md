# Ankita Salaria — Cloud-Native & Kubernetes Tooling

CS undergraduate (University of Jammu) building **Kubernetes and observability tooling in Go and Python**.
Contributor to **Meshery (CNCF incubating)**. Open to internships, OSS collaboration, and cloud-native mentorship.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ankitasalaria21-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ankitasalaria21)
[![Email](https://img.shields.io/badge/Email-ankitasalaria21%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:ankitasalaria21@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-ankitavasudev.github.io-181717?style=flat&logo=githubpages&logoColor=white)](https://ankitavasudev.github.io)
[![Hireable](https://img.shields.io/badge/Hireable-yes-2ea44f?style=flat)](https://github.com/Ankitavasudev)

---

## About

I build small, honest CLI and operator tools for Kubernetes clusters: health checks, log triage, Dockerfile linting, pod resource sizing, and namespace budget enforcement. Every project ships with tests, CI, and docs that explain the *why* — not just the *how*.

- **Languages:** Go, Python, (some) TypeScript/JavaScript
- **Focus:** Kubernetes, observability, developer CLIs, container security
- **Currently:** Research Assistant @ Moonshot (YC S26); Product Apprentice @ DoraDAO (GWY Fellowship 2.0); SheFi Scholar (Season 17)
- **Open to:** Internships · Open-source collaboration · Cloud-native mentorship

---

## Featured projects

| Project | What it does | Stack |
|---|---|---|
| [quota-guard](https://github.com/Ankitavasudev/quota-guard) | Kubernetes operator enforcing per-namespace CPU/memory request budgets via a `ResourceBudget` CRD. Writes status conditions + events, exposes Prometheus metrics. Distroless image, RBAC, CI. | Go · controller-runtime · CRD · Prometheus |
| [k8s-health-monitor](https://github.com/Ankitavasudev/k8s-health-monitor) | Terminal + browser cluster health: nodes, pods, deployments, resource accounting, security findings, Prometheus endpoint. Reports `UNKNOWN` instead of `HEALTHY` when it can't reach the cluster. | Python · kubectl · Rich · pytest |
| [container-lint](https://github.com/Ankitavasudev/container-lint) | Lints Dockerfiles and compose files without a Docker daemon. 14 hadolint-style rules, JSON/SARIF output, CI-safe exit codes. | Python · PyYAML · pytest |
| [podsize](https://github.com/Ankitavasudev/podsize) | Reads `kubectl get pods -o json` and gives each pod one verdict: `fix` / `set` / `tighten` / `investigate` / `watch` / `keep`. Refuses to invent numbers it can't measure. | Go · Cobra · kubectl |
| [errtop](https://github.com/Ankitavasudev/errtop) | Ranks container log errors by frequency, buckets by minute, reads from file/stdin/`kubectl logs`. Text, JSON, stable CSV. | Go · Cobra · kubectl |
| [godo](https://github.com/Ankitavasudev/godo) | Project-aware terminal task manager in one JSON file: filters by project/status/priority/tag, due dates, stats, CSV import/export. | Go · Cobra · encoding/csv |

Live demos (GitHub Pages): [k8s-health-monitor](https://ankitavasudev.github.io/k8s-health-monitor/) · [container-lint](https://ankitavasudev.github.io/container-lint/) · [podsize](https://ankitavasudev.github.io/podsize/) · [errtop](https://ankitavasudev.github.io/errtop/) · [godo](https://ankitavasudev.github.io/godo/)

---

## Open source (Meshery — CNCF incubating)

- [#22893 — close the gzip reader in TarXZ](https://github.com/meshery/meshery/pull/22893) · merged
- [#22777 — fix "Everytime" typo in build & release guide](https://github.com/meshery/meshery/pull/22777) · merged
- [#22961 — close scaffolded files per iteration instead of deferring](https://github.com/meshery/meshery/pull/22961) · open, all checks passing
- [#22959 — close pod log streams per container](https://github.com/meshery/meshery/pull/22959) · merged

Also merged fixes to [konflux-ci](https://github.com/konflux-ci/konflux-ci) (#9959, #9960) and [gslider-blocks](https://github.com/noruzzamans/gslider-blocks/pull/699).

---

## Stack

**Languages** — Go · Python · Bash
**Frameworks / libs** — controller-runtime · Cobra · Rich · FastAPI · pytest
**Platform** — Kubernetes · Docker · Linux · Prometheus · GitHub Actions
**Every project ships** — tests · CI · docs · (Go projects) goreleaser releases

---

## Education

**University of Jammu** — B.Sc. Computer Science (undergraduate)
Coursework alongside hands-on work in Kubernetes, distributed systems, and developer tooling.

---

## Contact

- 📧 [ankitasalaria21@gmail.com](mailto:ankitasalaria21@gmail.com)
- 💼 [linkedin.com/in/ankitasalaria21](https://www.linkedin.com/in/ankitasalaria21)
- 🌐 [ankitavasudev.github.io](https://ankitavasudev.github.io)
- 🐙 [github.com/Ankitavasudev](https://github.com/Ankitavasudev)

---

> I don't list projects I can't explain line-by-line. If something here interests you, email me and I'll walk you through it.