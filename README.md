<!-- ╔══════════════════════════════════════════════════════════════╗ -->
<!-- ║  xm0dx · GitHub profile README                                 ║ -->
<!-- ║  Theme: light-blue terminal — bg #0f1620 · accent #5BC0EB     ║ -->
<!-- ╚══════════════════════════════════════════════════════════════╝ -->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=30&pause=1200&color=5BC0EB&center=true&vCenter=true&width=760&height=70&lines=Hi%2C+I'm+Mick+%C2%B7+%40xm0dx;Administration;Builder+%26+self-hoster+in+my+own+time." alt="typing banner" />

<br/>

![Role](https://img.shields.io/badge/current_role-administration-0f1620?style=flat-square&logo=googleforms&logoColor=5BC0EB)
![Infra](https://img.shields.io/badge/infra-self--hosted-0f1620?style=flat-square&logo=docker&logoColor=5BC0EB)
![Networking](https://img.shields.io/badge/networking-zero--trust-0f1620?style=flat-square&logo=tailscale&logoColor=5BC0EB)
![Style](https://img.shields.io/badge/style-everything--as--code-0f1620?style=flat-square&logo=gnubash&logoColor=5BC0EB)

</div>

---

```text
$ whoami
> Mick (@xm0dx) — I work in administration, and build apps
> and self-host my own cloud in my own time.
> Self-taught and hands-on: I learn by building real systems.
> Right now I run a single-box home lab — ~18 containerized
> services behind one reverse proxy, on a private mesh network,
> with my own auth gate, monitoring, and automated backups.
> I build tools that automate the boring parts.
```

---

### Featured project — [`homelab`](https://github.com/xm0dx/homelab)

> A self-hosted platform: **~18 Docker services** orchestrated with Docker Compose on a single host, reachable only over a private **Tailscale (WireGuard) mesh** — nothing exposed to the public internet.

| Area | What I built |
|------|--------------|
| **Single front door** | An **nginx** reverse proxy serving the dashboard + an embedded web terminal on **one origin** — WebSocket upgrades, same-origin iframes, valid HTTPS certs. |
| **Custom auth gate** | A from-scratch **Python** auth service (stdlib only) guarding the dashboard via nginx `auth_request`: HMAC-signed session cookies, peppered password hashing, **brute-force IP banning**, and a **live visitor/IP tracker**. |
| **Observability** | Real-time host metrics (CPU / temp / RAM / disk / NVMe) on the dashboard, full system monitor, live container logs, and an **uptime monitor + public status page** with alerting. |
| **Apps & data** | Private cloud + office suite, password manager, notes, a self-hosted **Git** server, all on a shared **Postgres 16** backend. |
| **Ops & reliability** | **systemd** units for boot reconciliation, scheduled **backups** with an offsite **storage push**, and an external dead-man's-switch healthcheck. |
| **Self-service dev** | A sandbox to deploy my own Python/Flask apps, plus homemade microservices (a finance planner API, a website health checker). |
| **Investing dashboard** | A self-hosted **investing learning tool**: a live market-quote proxy, portfolio & **allocation tracking** (funds / stocks / cash drag), a **savings-rate → goal projection**, discipline streaks, and a **grounded daily market digest** — every figure pulled from real quotes, never model guesses. |
| **Market assistant** | A **Discord assistant** wired to the same data: live price lookups, big-move **push alerts**, a recurring market + news **pulse**, and a grounded daily briefing — an **LLM kept honest** by real data, not hallucinations. |

**Stack**

![Docker](https://img.shields.io/badge/Docker-0f1620?style=flat-square&logo=docker&logoColor=5BC0EB)
![Compose](https://img.shields.io/badge/Compose-0f1620?style=flat-square&logo=docker&logoColor=5BC0EB)
![Kubernetes](https://img.shields.io/badge/Kubernetes-0f1620?style=flat-square&logo=kubernetes&logoColor=5BC0EB)
![nginx](https://img.shields.io/badge/nginx-0f1620?style=flat-square&logo=nginx&logoColor=5BC0EB)
![Python](https://img.shields.io/badge/Python-0f1620?style=flat-square&logo=python&logoColor=5BC0EB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0f1620?style=flat-square&logo=postgresql&logoColor=5BC0EB)
![Linux](https://img.shields.io/badge/Linux-0f1620?style=flat-square&logo=linux&logoColor=5BC0EB)
![Bash](https://img.shields.io/badge/Bash-0f1620?style=flat-square&logo=gnubash&logoColor=5BC0EB)
![systemd](https://img.shields.io/badge/systemd-0f1620?style=flat-square&logo=systemd&logoColor=5BC0EB)
![Tailscale](https://img.shields.io/badge/Tailscale-0f1620?style=flat-square&logo=tailscale&logoColor=5BC0EB)

---

### Projects

| Project | Stack | What it is |
|---------|-------|------------|
| **[homelab](https://github.com/xm0dx/homelab)** | ![Docker](https://img.shields.io/badge/Docker-0f1620?style=flat-square&logo=docker&logoColor=5BC0EB) ![nginx](https://img.shields.io/badge/nginx-0f1620?style=flat-square&logo=nginx&logoColor=5BC0EB) ![Python](https://img.shields.io/badge/Python-0f1620?style=flat-square&logo=python&logoColor=5BC0EB) | Self-hosted infrastructure: ~18 Docker services behind one reverse proxy on a private Tailscale mesh — custom auth gate, monitoring, automated backups. |
| **[finance-planner](https://github.com/xm0dx/finance-planner)** | ![Python](https://img.shields.io/badge/Python-0f1620?style=flat-square&logo=python&logoColor=5BC0EB) ![JavaScript](https://img.shields.io/badge/JS-0f1620?style=flat-square&logo=javascript&logoColor=5BC0EB) | Personal finance planner — single-page web app with a small Python persistence API. |
| **[web-health-check](https://github.com/xm0dx/web-health-check)** | ![Python](https://img.shields.io/badge/Python-0f1620?style=flat-square&logo=python&logoColor=5BC0EB) ![nginx](https://img.shields.io/badge/nginx-0f1620?style=flat-square&logo=nginx&logoColor=5BC0EB) | Server-side website health checker with SSRF protection. |
| **[minecraft-server](https://github.com/xm0dx/minecraft-server)** | ![Kubernetes](https://img.shields.io/badge/k8s-0f1620?style=flat-square&logo=kubernetes&logoColor=5BC0EB) ![Docker](https://img.shields.io/badge/Docker-0f1620?style=flat-square&logo=docker&logoColor=5BC0EB) | Minecraft server on a Kubernetes (`kind`) cluster — started on Docker, moved to k8s for orchestration. |
| **[RBLX-mechanic](https://github.com/xm0dx/RBLX-mechanic)** | ![Lua](https://img.shields.io/badge/Lua-0f1620?style=flat-square&logo=lua&logoColor=5BC0EB) | A Roblox game mechanic built in Lua. |
| **Discord assistant** *(private)* | ![Python](https://img.shields.io/badge/Python-0f1620?style=flat-square&logo=python&logoColor=5BC0EB) | A personal assistant + automation bot: live market data, scheduled push alerts and briefings, and chat — an LLM grounded in real data. |

---

### What I work with

```text
Containers     Docker · Docker Compose · Kubernetes (kind) · orchestration
Networking     Tailscale / WireGuard · reverse proxy · TLS · WebSockets
Backend        Python (stdlib HTTP, HMAC auth) · REST · Postgres
Cloud / Linux  GCP · Ubuntu · systemd · cron/timers · backups · shell scripting
Security       least-privilege · session auth · brute-force defense · zero public exposure
Automation     scheduled jobs · Discord assistant · LLM integration (grounded, no hallucinated data)
Web            nginx · HTML/CSS/JS dashboards · same-origin design
```
