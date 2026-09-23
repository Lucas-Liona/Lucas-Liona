<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=30&pause=1000&color=CC0033&center=true&vCenter=true&repeat=false&width=460&height=48&lines=Lucas+Liona" alt="Lucas Liona" />

<sub>CS &amp; Applied Math @ Rutgers–Camden · US Dept. of State Gilman Scholar</sub>

### I build systems that run themselves.

<br/>

**Infra**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white" />
<img src="https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white" />
<img src="https://img.shields.io/badge/Tailscale-242E30?style=flat-square&logo=tailscale&logoColor=white" />

**ML**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />

**Shell**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Zsh-4EAA25?style=flat-square&logo=zsh&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/WSL-4D4D4D?style=flat-square&logo=linux&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />

<br/>

⚡ **Now** — building a self-hosting homelab, an RL agent that learns Street Fighter III, and LifeOS.
Open to applied **ML / infrastructure** roles · into open source.

</div>

---

## 🏠 Homelab — declarative, self-hosted, runs itself

Single Proxmox node managed entirely as **Infrastructure as Code**. GitOps declarative deploys, remote Terraform state, and CI that **plans every change before it touches production**.

| | Container | Role |
|---|---|---|
| 🛰 | **Tailscale subnet router** | reach everything from anywhere — nothing exposed to the internet |
| 🎮 | **GPU-passthrough LXC** | CUDA + model workloads for any other container |
| 🔁 | **CI/CD runner** | merge-to-deploy · Renovate checks Docker pins · Terraform state in Cloudflare R2 |

These support media, hardened Docker services, a nightly LLM agent, and full observability (Prometheus / Grafana).

**Tooling** — SOPS + age · Claude Code + custom skills · SSH · workmux worktrees
**Subprojects** — GraphRAG · CUDA experiments · nightly agent · disposable sandboxed Claude Code LXCs (rootless Podman) · private finance & portfolio automation

<!-- SCREENSHOT — your proudest thing. Add your LinkedIn dashboard shot to the repo as homelab.png and uncomment: -->
<!-- <div align="center"><img src="homelab.png" width="720" alt="Homelab dashboard" /></div> -->

*Deep-dive writeup in progress →*

---

<div align="center">

## 🛠 Building

| Project | What it does | |
|:--|:--|:--|
| [**Pulsar Graph**](https://github.com/Lucas-Liona/obsidian-pulsar-graph) | Obsidian plugin — a temporal view of your knowledge graph · `TypeScript` | <img src="https://img.shields.io/github/stars/Lucas-Liona/obsidian-pulsar-graph?style=flat-square&logo=github&label=&color=CC0033" /> |
| [**Heat-Model**](https://github.com/Lucas-Liona/Heat-Model) | Heat-diffusion PDE solver — C++ core (pybind11) + Python/Dash, Dockerized | <img src="https://img.shields.io/github/stars/Lucas-Liona/Heat-Model?style=flat-square&logo=github&label=&color=CC0033" /> |
| **IPyKanban** | A Jupyter-native kanban board · `Python` | `releasing soon` |
| **Screen Weave** | Cross-device screen tooling · `Kotlin` | `releasing soon` |

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

<!-- Snake renders after .github/workflows/snake.yml runs once (creates the `output` branch). Until then it 404s. -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Lucas-Liona/Lucas-Liona/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Lucas-Liona/Lucas-Liona/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/Lucas-Liona/Lucas-Liona/output/github-snake.svg" alt="contribution snake" />
</picture>

<br/><br/>

**[lucasliona.tech](https://lucasliona.tech)**&nbsp;·&nbsp;**[LinkedIn](https://linkedin.com/in/lucas-liona)**

<sub>powered by curiosity, caffeine, and a homelab that won't quit</sub>

</div>
