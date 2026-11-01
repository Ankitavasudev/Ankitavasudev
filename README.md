<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:0B7285,100:00ADB5&height=130&section=header" width="100%" alt="" />

<img src="https://github.com/Ankitavasudev.png" width="120" style="border-radius:50%" alt="Ankita Salaria" />

<h1>Ankita Salaria</h1>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=3000&pause=900&color=00ADB5&center=true&vCenter=true&width=720&lines=CS+Student+%40+MBS+College+of+Engineering;Cloud-Native+Tooling+in+Go+%26+Python;Kubernetes+%C2%B7+Observability+%C2%B7+Open+Source" alt="what I do" />

<br />

<img src="https://img.shields.io/badge/Computer_Science-Undergraduate-00ADB5?style=flat-square&logo=googlescholar&logoColor=white" />
&nbsp;
<img src="https://img.shields.io/badge/Jammu-India-0B7285?style=flat-square&logo=googlemaps&logoColor=white" />
&nbsp;
<img src="https://img.shields.io/badge/Open_to-Internships-1F6F78?style=flat-square&logo=handshake&logoColor=white" />

<br /><br />

<img src="https://komarev.com/ghpvc/?username=Ankitavasudev&color=00ADB5&style=flat-square&label=Profile+Views&labelColor=0D1117" />

</div>

---

# 🐚 About Me

```console
$ whoami
ankita — CS student, Jammu (IN) · building infrastructure tooling since Jan 2026

$ cat focus.txt
kubernetes      → health checks, pod analysis, scheduling, cost recommendations
go & python     → CLIs that operators actually run at 3am
observability   → prometheus, grafana, log pipelines
open source     → patches sent upstream to CNCF projects, reviewed and reworked

$ git shortlog -sn --no-merges
11 projects shipped · every repo green in CI · 3 upstream PRs open, 2 closed
```

---

## ⚡ Tech Stack

<table align="center">
<tr>
<td valign="top" width="50%">

### Languages

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,py,js,bash&theme=dark" />
</p>

</td>
<td valign="top" width="50%">

### Containers & Orchestration

<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,linux,nginx&theme=dark" />
</p>

</td>
</tr>
<tr>
<td valign="top" width="50%">

### Observability

<p align="center">
  <img src="https://skillicons.dev/icons?i=prometheus,grafana&theme=dark" />
</p>

</td>
<td valign="top" width="50%">

### Workflow

<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,githubactions,vscode&theme=dark" />
</p>

</td>
</tr>
<tr>
<td valign="top" width="50%">

### Web

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,threejs,react&theme=dark" />
</p>

</td>
<td valign="top" width="50%">

### APIs & Testing

<p align="center">
  <img src="https://skillicons.dev/icons?i=fastapi,nodejs,pytest,npm&theme=dark" />
</p>

</td>
</tr>
</table>

<br />

# 🛠️ Featured Work

Tools I built end to end — not tutorials, not forks. Every one has tests and a green CI run.

| Project | What it does | Stack |
| :--- | :--- | :--- |
| **[k8s-health-monitor](https://github.com/Ankitavasudev/k8s-health-monitor)** | Terminal dashboard for a cluster: node capacity, pod and deployment health, security findings, resource accounting, namespace diffing. Says `UNKNOWN` instead of `HEALTHY` when it cannot reach the cluster. `--output prometheus` for scraping. | `Python` `kubectl` `Rich` `Prometheus` `pytest` `CI` |
| **[container-lint](https://github.com/Ankitavasudev/container-lint)** | Lints Dockerfiles and compose files with no Docker daemon. 14 rules (hadolint-style ids), `--format json`, `--fail-on` severity, exit codes a pipeline can trust. | `Python` `PyYAML` `pytest` `CI` |
| **[k8s-pod-recommender](https://github.com/Ankitavasudev/k8s-pod-recommender)** | Reads `kubectl get pods -o json` and gives each pod one verdict: `fix`, `set`, `tighten`, `investigate`, `watch` or `keep`. Refuses to invent numbers it cannot measure. | `Go` `Cobra` `kubectl` `CI` |
| **[k8s-pod-analyzer](https://github.com/Ankitavasudev/k8s-pod-analyzer)** | Ranks the errors inside container logs by frequency (timestamps stripped so repeats group), buckets them by minute, and reads from a file, stdin or `kubectl logs`. Text, JSON or stable CSV. | `Go` `Cobra` `kubectl` `CI` |
| **[go-task-cli](https://github.com/Ankitavasudev/go-task-cli)** | Project-aware todo list in one JSON file: filters by project/status/priority/tag, due-date tracking, stats, JSON and real CSV import/export. | `Go` `Cobra` `encoding/csv` `CI` |
| **[SolarSystem](https://github.com/Ankitavasudev/SolarSystem)** — [▶ live](https://ankitavasudev.github.io/SolarSystem/) | Interactive 3D orrery: real planet textures, scaled Kepler orbits, Saturn's rings, an asteroid belt and meteors — hover a planet for facts, click for a ripple. | `Three.js` `WebGL` `JS` `GitHub Pages` |
| **[VoxNote](https://github.com/Ankitavasudev/VoxNote)** — [▶ live](https://ankitavasudev.github.io/VoxNote/) | Voice notes that never leave the browser: Web Speech transcription, localStorage, search and export. No account, no server. | `JS` `Web Speech API` `node:test` `Pages` |
| **[NexusBoard](https://github.com/Ankitavasudev/NexusBoard)** — [▶ live](https://ankitavasudev.github.io/NexusBoard/) | Infinite whiteboard in a tab: pen, shapes, text, eraser, undo/redo, PNG export. Zero dependencies, 29 tests. | `JS` `Canvas` `node:test` `Pages` |
| **[DevPulse](https://github.com/Ankitavasudev/DevPulse)** — [▶ live](https://ankitavasudev.github.io/DevPulse/) | Type a GitHub username, get the shape of that developer in one screen — languages, activity, top repos — from the public API, single file. | `JS` `GitHub API` `Pages` |
| **[CodeLens-AI](https://github.com/Ankitavasudev/CodeLens-AI)** | Paste code, get a structured review — or an explanation, a refactor, a translation. FastAPI routers, React front end, 30 tests. | `FastAPI` `Python` `React` `Docker` `pytest` |
| **[emotion-sense](https://github.com/Ankitavasudev/emotion-sense)** | Explainable emotion scoring: every prediction lists the exact words that produced it, with a `/explain` breakdown. | `FastAPI` `Python` `React` `pytest` |

---

# 🌱 Upstream Patches

Sent to CNCF projects — status shown as it actually is.

| Project | Patch | Status |
| :--- | :--- | :--- |
| [kubeedge/kubeedge](https://github.com/kubeedge/kubeedge) | [#7219](https://github.com/kubeedge/kubeedge/pull/7219) — add `govulncheck` CI workflow | ![open](https://img.shields.io/badge/open-3FB950?style=flat-square) |
| [volcano-sh/volcano](https://github.com/volcano-sh/volcano) | [#5862](https://github.com/volcano-sh/volcano/pull/5862) — test utility builders for test pods | ![open](https://img.shields.io/badge/open-3FB950?style=flat-square) |
| [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger) | [#9292](https://github.com/jaegertracing/jaeger/pull/9292) — sort span events by timestamp | ![open](https://img.shields.io/badge/open-3FB950?style=flat-square) |
| [kubeedge/kubeedge](https://github.com/kubeedge/kubeedge) | [#7274](https://github.com/kubeedge/kubeedge/pull/7274) — error handling in cloud controllers | ![closed](https://img.shields.io/badge/closed-8B949E?style=flat-square) |
| [Project-HAMi/HAMi](https://github.com/Project-HAMi/HAMi) | [#2872](https://github.com/Project-HAMi/HAMi/pull/2872) — quick start guide for contributors | ![closed](https://img.shields.io/badge/closed-8B949E?style=flat-square) |

---

# 📈 GitHub Analytics

<div align="center">

<img width="95%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Ankitavasudev&theme=github_dark" alt="profile details" />

<br /><br />

<img width="45%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Ankitavasudev&theme=github_dark" alt="most used language" />
<img width="45%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Ankitavasudev&theme=github_dark" alt="repos per language" />

<br /><br />

<img width="45%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Ankitavasudev&theme=github_dark&utcOffset=5.5" alt="productive time" />
<img width="45%" src="https://streak-stats.demolab.com?user=Ankitavasudev&hide_border=true&background=0D1117&ring=00ADB5&fire=00ADB5&currStreakLabel=00ADB5&sideLabels=C9D1D9&dates=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9" alt="streak" />

</div>

---

# 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/Ankitavasudev/Ankitavasudev/output/github-contribution-grid-snake-dark.svg" width="100%" alt="contribution snake" />

</div>

---

<div align="center">

<details>
<summary><b>🧭 How I build</b></summary>

<br />

- Start from the operator's problem, not the framework — every tool here came from a real gap in `kubectl` or a noisy dashboard.
- Ship it with tests and CI, or it does not count as finished — all eleven repos here have a passing workflow.
- Read the upstream issue, match the maintainers' conventions, expect review comments, come back with a better patch.

</details>

<details>
<summary><b>🎯 Currently</b></summary>

<br />

- Wiring `kubectl top` into `k8s-pod-recommender` so it can size from measured usage instead of only inconsistent specs.
- Adding rules to `container-lint` and more checks to `k8s-health-monitor`.
- Keeping the five upstream patches green while maintainers review.

</details>

</div>

---

# 🌐 Connect

<div align="center">

<a href="https://linkedin.com/in/ankitasalaria21">
<img src="https://img.shields.io/badge/LinkedIn-Ankita_Salaria-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="mailto:ankitasalaria21@gmail.com">
<img src="https://img.shields.io/badge/Email-Write_to_me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://github.com/Ankitavasudev">
<img src="https://img.shields.io/badge/GitHub-Follow-00ADB5?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

<br />

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ADB5,50:0B7285,100:0D1117&height=120&section=footer" width="100%" alt="" />

**Thanks for stopping by — building in public, one commit at a time.**

</div>
