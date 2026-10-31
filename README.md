<div align="center">

<img src="https://github.com/Ankitavasudev.png" width="116" style="border-radius:50%" alt="Ankita Salaria" />

<h1>Ankita Salaria</h1>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3200&pause=900&color=00ADB5&center=true&vCenter=true&width=580&lines=CS+Student+at+MBS+College+of+Engineering;Kubernetes+tooling+in+Go+%26+Python;CLI+tooling+%C2%B7+observability+%C2%B7+upstream+open+source" alt="what I do" />

<a href="https://linkedin.com/in/ankitasalaria21"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:ankitasalaria21@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/Ankitavasudev?tab=repositories"><img src="https://img.shields.io/badge/Repositories-161B22?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>

</div>

<br />

```console
$ whoami
ankita — CS student, Jammu (IN) · building infrastructure tooling since Jan 2026

$ cat focus.txt
kubernetes      → health checks, pod analysis, scheduling, cost recommendations
go & python     → CLIs that operators actually run at 3am
observability   → prometheus, grafana, log pipelines
open source     → patches sent upstream to CNCF projects, reviewed and reworked

$ git shortlog -sn --no-merges
18 merged PRs · 6 tools shipped · 3 upstream PRs awaiting review
```

<br />

<div align="center">

### Stack

<img src="https://skillicons.dev/icons?i=go,py,js,bash,docker,kubernetes,linux,git,githubactions,prometheus,grafana,vscode&theme=dark&perline=12" alt="stack" />

</div>

<br />

## Featured work

Tools I built end to end — not tutorials, not forks.

| Project | What it does | Stack |
| :--- | :--- | :--- |
| **[k8s-health-monitor](https://github.com/Ankitavasudev/k8s-health-monitor)** | Cluster health checks, security scanning, namespace diffing and quota analysis, with Rich-rendered reports | `Python` `kubectl` `Docker` `CI` |
| **[go-task-cli](https://github.com/Ankitavasudev/go-task-cli)** | Task manager with priorities, due dates, search, CSV/JSON I/O and an interactive TUI | `Go` `Cobra` `REST` |
| **[k8s-pod-analyzer](https://github.com/Ankitavasudev/k8s-pod-analyzer)** | Pod log analysis with filter flags, statistics summaries and JSON/CSV report export | `Go` `Kubernetes API` |
| **[container-lint](https://github.com/Ankitavasudev/container-lint)** | Dockerfile linter with 15+ rules, security scanning and HTML report output | `Python` `AST` `Docker` |
| **[k8s-pod-recommender](https://github.com/Ankitavasudev/k8s-pod-recommender)** | Recommends CPU/memory limits from observed usage; HPA/VPA aware, cost-oriented | `Go` `K8s` `metrics` |
| **[CodeLens-AI](https://github.com/Ankitavasudev/CodeLens-AI)** | Automated code review platform that flags issues before they reach a PR | `JavaScript` `AI` |

<br />

## Upstream patches

Sent to CNCF projects — status shown as it actually is.

| Project | Patch | Status |
| :--- | :--- | :--- |
| [kubeedge/kubeedge](https://github.com/kubeedge/kubeedge) | [#7219](https://github.com/kubeedge/kubeedge/pull/7219) — add `govulncheck` CI workflow | ![open](https://img.shields.io/badge/open-3FB950?style=flat-square) |
| [volcano-sh/volcano](https://github.com/volcano-sh/volcano) | [#5862](https://github.com/volcano-sh/volcano/pull/5862) — test utility builders for test pods | ![open](https://img.shields.io/badge/open-3FB950?style=flat-square) |
| [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger) | [#9292](https://github.com/jaegertracing/jaeger/pull/9292) — sort span events by timestamp | ![open](https://img.shields.io/badge/open-3FB950?style=flat-square) |
| [kubeedge/kubeedge](https://github.com/kubeedge/kubeedge) | [#7274](https://github.com/kubeedge/kubeedge/pull/7274) — error handling in cloud controllers | ![closed](https://img.shields.io/badge/closed-8B949E?style=flat-square) |
| [Project-HAMi/HAMi](https://github.com/Project-HAMi/HAMi) | [#2872](https://github.com/Project-HAMi/HAMi/pull/2872) — quick start guide for contributors | ![closed](https://img.shields.io/badge/closed-8B949E?style=flat-square) |

<br />

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Ankitavasudev&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=00ADB5&icon_color=00ADB5&text_color=C9D1D9" alt="stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ankitavasudev&layout=compact&langs_count=6&hide_border=true&bg_color=0D1117&title_color=00ADB5&text_color=C9D1D9" alt="languages" />

<br />

<img src="https://streak-stats.demolab.com?user=Ankitavasudev&hide_border=true&background=0D1117&ring=00ADB5&fire=00ADB5&currStreakLabel=00ADB5&sideLabels=C9D1D9&dates=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9" alt="streak" />

<br />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Ankitavasudev&bg_color=0D1117&color=00ADB5&line=00ADB5&point=E6EDF3&area=true&hide_border=true" alt="activity" />

</div>

<br />

<div align="center">

<details>
<summary><b>How I build</b></summary>

<br />

- Start from the operator's problem, not the framework — every tool here came from a real gap in `kubectl` or a noisy dashboard.
- Ship it with tests, a Dockerfile and CI, or it does not count as finished.
- Read the upstream issue, match the maintainers' conventions, expect review comments, come back with a better patch.

</details>

<details>
<summary><b>Currently</b></summary>

<br />

- Finalising the ML model behind `k8s-pod-recommender` and its evaluation against real cluster traces.
- Reading through Kubernetes scheduler internals to extend pod-placement experiments.
- Keeping upstream PRs green while maintainers review.

</details>

</div>

<br />

<div align="center">

<img src="https://raw.githubusercontent.com/Ankitavasudev/Ankitavasudev/output/github-contribution-grid-snake-dark.svg" alt="contribution snake" width="100%" />

<br /><br />

<img src="https://komarev.com/ghpvc/?username=Ankitavasudev&color=00ADB5&style=flat-square&label=profile+views&labelColor=0D1117" alt="profile views" />

</div>
