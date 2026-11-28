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
  <img src="https://github-readme-cards.vercel.app/api/pin/?username=Ankitavasudev&repo=quota-guard&theme=tokyonight&hide_border=true" width="49%" alt="quota-guard"/>
</p>

</div>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=32&duration=3000&pause=1200&color=4A90D9&center=true&vCenter=true&width=760&lines=Ankita+Salaria;Go+%26+Python+%C2%B7+Kubernetes+Tooling;Open+Source+%C2%B7+Developer+Tooling" alt="Ankita Salaria"/>

<sub>CS undergraduate · India · building Kubernetes tooling in Go & Python</sub>

</div>

---

## About

I'm a CS undergraduate at University of Jammu building CLI tools and Kubernetes operators in Go and Python. I contribute to CNCF projects (Meshery, KubeArmor, konflux-ci) and recently started contributing to the Outreachy website.

**Current focus:** Kubernetes observability, developer tooling, and container security.

**Open to:** Internships in platform engineering / developer tooling, open source collaborations.

---

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,python,js,ts,cpp,bash" alt="languages"/>
  <br>
  <img src="https://skillicons.dev/icons?i=kubernetes,docker,linux,fastapi,react,threejs,git,githubactions" alt="platform and tools"/>
</p>

| Category | Technologies |
| :--- | :--- |
| **Languages** | Go, Python, JavaScript, TypeScript, C++, Bash |
| **Frameworks** | FastAPI, React, Three.js, Cobra, Rich, pytest |
| **Platform** | Kubernetes, Docker, Linux, Prometheus, GitHub Actions |
| **Practices** | CI/CD, unit testing, code review, open source contribution |

---

## Projects

### quota-guard
Kubernetes operator for per-namespace CPU/memory request budgets. `ResourceBudget` CRD reconciled against pod requests, writes status conditions + events, exposes Prometheus metrics. Distroless image, RBAC, CI with race detector.
- **Stack:** Go · controller-runtime · CRD · Prometheus
- **Repo:** [Ankitavasudev/quota-guard](https://github.com/Ankitavasudev/quota-guard)

### k8s-health-monitor
Terminal + browser cluster health dashboard. Node capacity, pod/deployment health, security findings, resource accounting, namespace diffing. Reports `UNKNOWN` instead of `HEALTHY` when it can't reach the cluster.
- **Stack:** Python · kubectl · Rich · pytest
- **Repo:** [Ankitavasudev/k8s-health-monitor](https://github.com/Ankitavasudev/k8s-health-monitor)
- **Demo:** [Live](https://ankitavasudev.github.io/k8s-health-monitor/)

### container-lint
Lints Dockerfiles and compose files without a Docker daemon. 14 hadolint-style rules, JSON/SARIF output, CI-safe exit codes.
- **Stack:** Python · PyYAML · pytest
- **Repo:** [Ankitavasudev/container-lint](https://github.com/Ankitavasudev/container-lint)
- **Demo:** [Live](https://ankitavasudev.github.io/container-lint/)

### podsize
Reads `kubectl get pods -o json` and gives each pod a verdict: `fix` / `set` / `tighten` / `investigate` / `watch` / `keep`. Refuses to invent numbers it can't measure.
- **Stack:** Go · Cobra · kubectl
- **Repo:** [Ankitavasudev/podsize](https://github.com/Ankitavasudev/podsize)
- **Demo:** [Live](https://ankitavasudev.github.io/podsize/)

### errtop
Ranks container log errors by frequency, buckets by minute. Reads from file, stdin, or `kubectl logs`. Text, JSON, stable CSV.
- **Stack:** Go · Cobra · kubectl
- **Repo:** [Ankitavasudev/errtop](https://github.com/Ankitavasudev/errtop)
- **Demo:** [Live](https://ankitavasudev.github.io/errtop/)

### godo
Project-aware terminal task manager in one JSON file. Filters by project/status/priority/tag, due dates, stats, CSV import/export.
- **Stack:** Go · Cobra · encoding/csv
- **Repo:** [Ankitavasudev/godo](https://github.com/Ankitavasudev/godo)
- **Demo:** [Live](https://ankitavasudev.github.io/godo/)

---

## Open Source Contributions

I contribute to cloud-native projects in the CNCF ecosystem and the Outreachy website.

| Project | Area | My PRs |
| :--- | :--- | :--- |
| [KubeArmor](https://github.com/kubearmor/KubeArmor) | Runtime security (LSM-BPF / AppArmor) | [view](https://github.com/kubearmor/KubeArmor/pulls?q=is%3Apr+author%3AAnkitavasudev) |
| [Meshery](https://github.com/meshery/meshery) | Cloud native manager | [view](https://github.com/meshery/meshery/pulls?q=is%3Apr+author%3AAnkitavasudev) |
| [konflux-ci](https://github.com/konflux-ci/konflux-ci) | Trusted builds / software factory | [view](https://github.com/konflux-ci/konflux-ci/pulls?q=is%3Apr+author%3AAnkitavasudev) |
| [Outreachy Website](https://github.com/outreachy/website) | Django web app (favicon, export filenames, link fixes) | [view](https://github.com/outreachy/website/pulls?q=is%3Apr+author%3AAnkitavasudev) |

---

## Experience

| Role | Organization | Notes |
| :--- | :--- | :--- |
| Research Assistant | Moonshot (YC S26) | Remote applied research with an early-stage YC team |
| Product Apprentice | DoraDAO · GWY Fellowship 2.0 | AI product building sessions with a shipping-first cohort |
| Scholar | SheFi · Season 17 | Selected SheFi Scholar, 2026 |

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
<a href="https://ankitavasudev.github.io">
<img src="https://img.shields.io/badge/Portfolio-ankitavasudev.github.io-181717?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"/>
</a>

</div>