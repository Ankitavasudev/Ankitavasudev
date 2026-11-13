<div align="center">
<img src="https://raw.githubusercontent.com/Ankitavasudev/Ankitavasudev/main/banner-loop.gif" width="880" alt="Ankita Salaria - terminal"/>
</div>

<div align="center">

<p align="center">
  <img src="https://github-readme-cards.vercel.app/api/pin/?username=Ankitavasudev&repo=k8s-health-monitor&theme=tokyonight&hide_border=true" width="49%" alt="k8s-health-monitor"/>
  <img src="https://github-readme-cards.vercel.app/api/pin/?username=Ankitavasudev&repo=podsize&theme=tokyonight&hide_border=true" width="49%" alt="podsize"/>
</p>
<p align="center">
  <img src="https://github-readme-cards.vercel.app/api/pin/?username=Ankitavasudev&repo=errtop&theme=tokyonight&hide_border=true" width="49%" alt="errtop"/>
  <img src="https://github-readme-cards.vercel.app/api/pin/?username=Ankitavasudev&repo=container-lint&theme=tokyonight&hide_border=true" width="49%" alt="container-lint"/>
</p>
<p align="center">
  <img src="https://github-readme-cards.vercel.app/api/pin/?username=Ankitavasudev&repo=godo&theme=tokyonight&hide_border=true" width="49%" alt="godo"/>
  <img src="https://github-readme-cards.vercel.app/api/pin/?username=Ankitavasudev&repo=SolarSystem&theme=tokyonight&hide_border=true" width="49%" alt="SolarSystem"/>
</p>

</div>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=32&duration=3000&pause=1200&color=4A90D9&center=true&vCenter=true&width=760&lines=Ankita+Salaria;Go+%26+Python+%C2%B7+Kubernetes+Tooling;Open+Source+%C2%B7+Developer+Tooling" alt="Ankita Salaria"/>

<sub>CS undergraduate · India · building Kubernetes tooling in Go &amp; Python</sub>

</div>

---

## About

```yaml
Name: Ankita Salaria
Role: CS Undergraduate · Go & Python Developer
Focus:
  - Kubernetes tooling: health checks, pod analysis, resource sizing (Go, Python)
  - Runtime security & observability (KubeArmor)
  - Developer CLIs with real test coverage and CI
Building: quota-guard (k8s operator) · k8s-health-monitor · container-lint · podsize
Open to:  Internships · Open source collaborations
```

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/216120974-24a76b31-7f39-41f1-a38f-b3c1377cc612.png" width="120" alt="coffee mug"/>
</div>

---

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,python,js,ts,cpp,bash" alt="languages"/>
  <br>
  <img src="https://skillicons.dev/icons?i=kubernetes,docker,linux,fastapi,react,threejs,git,githubactions" alt="platform and tools"/>
</p>

**Languages** — Go · Python · JavaScript · TypeScript · C++ · Bash
**Frameworks** — FastAPI · React · Three.js · Cobra · Rich · pytest
**Platform** — Kubernetes · Docker · Linux · Prometheus · GitHub Actions · CI/CD
**Every project ships** — tests · CI · docs

---

## Featured Work

Tools built end to end — not tutorials, not forks.

| Project | What it does | Stack |
| :--- | :--- | :--- |
| **[quota-guard](https://github.com/Ankitavasudev/quota-guard)** | Kubernetes operator for per-namespace CPU/memory request budgets: a `ResourceBudget` CRD reconciled against pod requests, writes status conditions + events, exposes Prometheus metrics; distroless image, RBAC, CRD manifest, CI.  | `Go` `controller-runtime` `CRD` `Prometheus` `CI` |
| **[k8s-health-monitor](https://github.com/Ankitavasudev/k8s-health-monitor)** | Terminal dashboard for a cluster: node capacity, pod and deployment health, security findings, resource accounting, namespace diffing. Reports `UNKNOWN` instead of `HEALTHY` when it cannot reach the cluster; `--output prometheus` for scraping. | `Python` `kubectl` `Rich` `Prometheus` `pytest` `CI` |
| **[container-lint](https://github.com/Ankitavasudev/container-lint)** | Lints Dockerfiles and compose files with no Docker daemon. 14 hadolint-style rules, `--format json`, `--fail-on` severity, pipeline-safe exit codes. | `Python` `PyYAML` `pytest` `CI` |
| **[podsize](https://github.com/Ankitavasudev/podsize)** | Reads `kubectl get pods -o json` and gives each pod one verdict: `fix`, `set`, `tighten`, `investigate`, `watch` or `keep`. Refuses to invent numbers it cannot measure. | `Go` `Cobra` `kubectl` `CI` |
| **[errtop](https://github.com/Ankitavasudev/errtop)** | Ranks container log errors by frequency, buckets them by minute, reads from file, stdin or `kubectl logs`. Text, JSON or stable CSV. | `Go` `Cobra` `kubectl` `CI` |
| **[godo](https://github.com/Ankitavasudev/godo)** | Project-aware todo list in one JSON file: filters by project/status/priority/tag, due dates, stats, real CSV import/export. | `Go` `Cobra` `encoding/csv` `CI` |

Live demos (all interactive): **[k8s-health-monitor](https://ankitavasudev.github.io/k8s-health-monitor/)** · **[container-lint](https://ankitavasudev.github.io/container-lint/)** · **[podsize](https://ankitavasudev.github.io/podsize/)** · **[errtop](https://ankitavasudev.github.io/errtop/)** · **[godo](https://ankitavasudev.github.io/godo/)** · **[drydock](https://ankitavasudev.github.io/drydock/)** · **[jobpulse](https://ankitavasudev.github.io/jobpulse/)** · **[gpuscope](https://ankitavasudev.github.io/gpuscope/)** · **[emotion-sense](https://ankitavasudev.github.io/emotion-sense/)** · **[SolarSystem](https://ankitavasudev.github.io/SolarSystem/)** · **[VoxNote](https://ankitavasudev.github.io/VoxNote/)** · **[NexusBoard](https://ankitavasudev.github.io/NexusBoard/)** · **[DevPulse](https://ankitavasudev.github.io/DevPulse/)**

---

## Experience

| Role | Organization | Notes |
| :--- | :--- | :--- |
| Research Assistant | **Moonshot (YC S26)** | remote applied research with an early-stage YC team |
| Product Apprentice | **DoraDAO** — GWY Fellowship 2.0 | AI product building sessions with a shipping-first cohort |
| Scholar | **SheFi** — Season 17 | selected SheFi Scholar, 2026 |

---

## Open Source Contributions

I contribute to cloud-native projects in the CNCF ecosystem. Merged pull requests and reviews are tracked on my [GitHub PR dashboard](https://github.com/pulls?q=is%3Apr+author%3AAnkitavasudev+is%3Amerged).

| Project | Area | Link |
| :--- | :--- | :--- |
| [KubeArmor](https://github.com/kubearmor/KubeArmor) | Runtime security enforcement (LSM-BPF / AppArmor) | [my PRs](https://github.com/kubearmor/KubeArmor/pulls?q=is%3Apr+author%3AAnkitavasudev) |
| [Meshery](https://github.com/meshery/meshery) | Cloud native manager | [my PRs](https://github.com/meshery/meshery/pulls?q=is%3Apr+author%3AAnkitavasudev) |
| [konflux-ci](https://github.com/konflux-ci/konflux-ci) | Trusted builds / software factory | [my PRs](https://github.com/konflux-ci/konflux-ci/pulls?q=is%3Apr+author%3AAnkitavasudev) |

> All contributions are public and reviewable. If a link shows zero PRs, that fork was exploration only — I keep those archived.

---

## Looking for

- **Internships** in Kubernetes / platform engineering / developer tooling (Go, Python).
- **Open source collaborations** in the CNCF ecosystem.
- Reach me: [LinkedIn](https://linkedin.com/in/ankitasalaria21) · [email](mailto:ankitasalaria21@gmail.com).

---

## Education

**University of Jammu** · Computer Science undergraduate

Coursework alongside hands-on work in Kubernetes, distributed systems and developer tooling.

<div align="center">
<img src="https://raw.githubusercontent.com/Ankitavasudev/Ankitavasudev/main/assets/education-cap.gif?v=2" width="120" alt="animated 3D graduation cap"/>
</div>

---

## GitHub Analytics

<p align="center">
  <img src="https://raw.githubusercontent.com/Ankitavasudev/Ankitavasudev/main/assets/divider.gif" width="100%" alt=""/>
</p>

<div align="center">

<img width="96%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Ankitavasudev&theme=tokyonight&v=20261107" alt="profile summary"/>

<br>

<img width="48%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Ankitavasudev&theme=tokyonight&v=20261107" alt="stats"/>

<img width="48%" src="https://streak-stats.demolab.com?user=Ankitavasudev&theme=tokyonight&hide_border=true&v=20261107" alt="streak"/>

</div>

---

## Contact

<div align="center">

<a href="https://linkedin.com/in/ankitasalaria21">
<img src="https://img.shields.io/badge/LinkedIn-Ankita_Salaria-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:ankitasalaria21@gmail.com">
<img src="https://img.shields.io/badge/Email-ankitasalaria21@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://github.com/Ankitavasudev">
<img src="https://img.shields.io/badge/GitHub-Ankitavasudev-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

</div>
