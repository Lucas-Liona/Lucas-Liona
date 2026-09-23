<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=32&pause=1000&color=CC0033&center=true&vCenter=true&repeat=false&width=460&height=50&lines=Lucas+Liona" alt="Lucas Liona" />

<sub>CS &amp; Applied Math @ Rutgers–Camden · US Dept. of State Gilman Scholar</sub>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&pause=1200&color=CC0033&center=true&vCenter=true&width=620&height=36&lines=I+build+systems+that+run+themselves;A+homelab+that+deploys+and+heals+itself;An+RL+agent+learning+Street+Fighter+III;Open+to+ML+%2F+infrastructure+roles" alt="Now" />

<br/>

<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white" />
<img src="https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />

</div>

---

## 🏠 Homelab

<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white" />
<img src="https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white" />
<img src="https://img.shields.io/badge/Tailscale-242E30?style=flat-square&logo=tailscale&logoColor=white" />
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />

Single Proxmox node managed entirely as **Infrastructure as Code** — GitOps declarative deploys, remote Terraform state, and CI that plans every change before it touches production.

My three most important containers:
- **Tailscale subnet router** — reach everything from anywhere without exposing it to the internet
- **GPU-passthrough LXC** — CUDA and model workloads for any other container
- **CI/CD runner** — merge-to-deploy, Renovate checks Docker pins, Terraform state in Cloudflare R2

These support media, hardened Docker services, a nightly LLM agent, and full observability (Prometheus / Grafana).

**Tooling**
- SOPS + age
- Claude Code + custom skills
- SSH, workmux worktrees

**Subprojects** — GraphRAG · CUDA experiments · nightly agent · disposable sandboxed Claude Code LXCs (rootless Podman) · private finance & portfolio automation

<!-- Homelab screenshot option: you have graphana.png in Downloads — add it as assets/homelab.png and uncomment: -->
<!-- <div align="center"><img src="assets/homelab.png" width="760" alt="Homelab observability" /></div> -->

---

<div align="center">

## 🛠 Building

| Project | What it does | Stack |
|:--|:--|:--|
| [**Pulsar Graph**](https://github.com/Lucas-Liona/obsidian-pulsar-graph) <img src="https://img.shields.io/github/stars/Lucas-Liona/obsidian-pulsar-graph?style=flat-square&logo=github&label=&color=CC0033" /> | Obsidian plugin — a temporal view of your knowledge graph | `TypeScript` |
| [**Heat-Model**](https://github.com/Lucas-Liona/Heat-Model) | Heat-diffusion PDE solver — a numerical simulation with an interactive 3-D dashboard | `C++` · `pybind11` · `Python` · `Docker` |
| **IPyKanban** | A Jupyter-native kanban board | `Python` · soon |
| **Screen Weave** | Cross-device screen tooling | `Kotlin` · soon |

<a href="https://github.com/Lucas-Liona/obsidian-pulsar-graph"><img src="assets/pulsar-graph.png" width="48%" alt="Pulsar Graph" /></a>
&nbsp;
<a href="https://github.com/Lucas-Liona/Heat-Model"><img src="assets/heat-model.png" width="48%" alt="Heat-Model simulation" /></a>

<sub><b>Pulsar Graph</b> — knowledge graph over time&nbsp;&nbsp;·&nbsp;&nbsp;<b>Heat-Model</b> — heat diffusion in a coffee cup</sub>

## 🧪 Experiments

| Project | What | Status |
|:--|:--|:--|
| **Street Fighter III: Third Strike** | A reinforcement-learning agent that learns to fight · `PyTorch` | `training · devlog soon` |
| **Deal Radar** | Computer-vision + web-scraping deal finder · `Python` | `in progress` |
| **LifeOS** | A self-tracking OS over my own data — TimescaleDB + pgvector, Grafana, Svelte | `live · private` |

</div>

---

## 🐚 Shell & desktop

Reproducible pieces of my setup (managed with chezmoi):
- **[zsh_config](https://github.com/Lucas-Liona/zsh_config)** — zinit-managed zsh, tuned for fast startup
- **zebar** — my status bar, clean and minimal · `releasing soon`

---

<div align="center">

## 📊 Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Lucas-Liona&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&title_color=CC0033&icon_color=CC0033&text_color=c9d1d9&bg_color=00000000&rank_icon=github" />
  <img src="https://github-readme-stats.vercel.app/api?username=Lucas-Liona&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&title_color=CC0033&icon_color=CC0033&text_color=24292f&bg_color=00000000&rank_icon=github" height="170" alt="GitHub stats" />
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Lucas-Liona&layout=compact&hide_border=true&title_color=CC0033&text_color=c9d1d9&bg_color=00000000&langs_count=8" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lucas-Liona&layout=compact&hide_border=true&title_color=CC0033&text_color=24292f&bg_color=00000000&langs_count=8" height="170" alt="Top languages" />
</picture>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Lucas-Liona&hide_border=true&background=0d1117&ring=CC0033&fire=CC0033&currStreakLabel=CC0033&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=6e7681" />
  <img src="https://streak-stats.demolab.com?user=Lucas-Liona&hide_border=true&ring=CC0033&fire=CC0033&currStreakLabel=CC0033" alt="GitHub streak" />
</picture>

<br/><br/>

<!-- Snake renders after .github/workflows/snake.yml runs on main once (creates the `output` branch). -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Lucas-Liona/Lucas-Liona/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Lucas-Liona/Lucas-Liona/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/Lucas-Liona/Lucas-Liona/output/github-snake.svg" alt="contribution snake" />
</picture>

<br/><br/>

**[lucasliona.tech](https://lucasliona.tech)**&nbsp;·&nbsp;**[LinkedIn](https://linkedin.com/in/lucas-liona)**

</div>
