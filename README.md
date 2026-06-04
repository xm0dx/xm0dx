<!-- ╔══════════════════════════════════════════════════════════════╗ -->
<!-- ║  xm0dx · GitHub profile README                                 ║ -->
<!-- ║  Theme: Claude terminal — bg #1a1815 · accent #d97757         ║ -->
<!-- ╚══════════════════════════════════════════════════════════════╝ -->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=30&pause=1200&color=D97757&center=true&vCenter=true&width=760&height=70&lines=Hi%2C+I'm+Mick+%C2%B7+%40xm0dx;Aspiring+Cybersecurity+%2F+DevOps+Engineer;I+self-host+my+own+cloud%2C+one+container+at+a+time." alt="typing banner" />

<br/>

![Focus](https://img.shields.io/badge/focus-cybersecurity_&_DevOps-1a1815?style=flat-square&logo=linux&logoColor=D97757)
![Infra](https://img.shields.io/badge/infra-self--hosted-1a1815?style=flat-square&logo=docker&logoColor=D97757)
![Networking](https://img.shields.io/badge/networking-zero--trust-1a1815?style=flat-square&logo=tailscale&logoColor=D97757)
![Style](https://img.shields.io/badge/style-everything--as--code-1a1815?style=flat-square&logo=gnubash&logoColor=D97757)

</div>

---

```text
$ whoami
> Mick (@xm0dx) — aspiring Cybersecurity / DevOps engineer.
> Self-taught and hands-on: I learn by building real systems.
> Right now I run a single-box home lab — ~18 containerized
> services behind one reverse proxy, on a private mesh network,
> with my own auth gate, monitoring, and automated backups.
> I love building tools that automate the boring parts.
```

---

### 🧱 Featured project — `homelab`

> A self-hosted platform: **~18 Docker services** orchestrated with Docker Compose on a single host, reachable only over a private **Tailscale (WireGuard) mesh** — nothing exposed to the public internet.

| Area | What I built |
|------|--------------|
| 🚪 **Single front door** | An **nginx** reverse proxy serving the dashboard + an embedded web terminal on **one origin** — WebSocket upgrades, same-origin iframes, valid HTTPS certs. |
| 🔐 **Custom auth gate** | A from-scratch **Python** auth service (stdlib only) guarding the dashboard via nginx `auth_request`: HMAC-signed session cookies, peppered password hashing, **brute-force IP banning**, and a **live visitor/IP tracker**. |
| 📊 **Observability** | Real-time host metrics (CPU / temp / RAM / disk / NVMe) on the dashboard, full system monitor, live container logs, and an **uptime monitor + public status page** with alerting. |
| 🗄️ **Apps & data** | Private cloud + office suite, password manager, notes, a self-hosted **Git** server, all on a shared **Postgres 16** backend. |
| ⚙️ **Ops & reliability** | **systemd** units for boot reconciliation, scheduled **backups** with an offsite **storage push**, and an external dead-man's-switch healthcheck. |
| 🧰 **Self-service dev** | A sandbox to deploy my own Python/Flask apps, plus homemade microservices (a finance planner API, a website health checker). |

**Stack**

![Docker](https://img.shields.io/badge/Docker-1a1815?style=flat-square&logo=docker&logoColor=D97757)
![Compose](https://img.shields.io/badge/Compose-1a1815?style=flat-square&logo=docker&logoColor=D97757)
![Kubernetes](https://img.shields.io/badge/Kubernetes-1a1815?style=flat-square&logo=kubernetes&logoColor=D97757)
![nginx](https://img.shields.io/badge/nginx-1a1815?style=flat-square&logo=nginx&logoColor=D97757)
![Python](https://img.shields.io/badge/Python-1a1815?style=flat-square&logo=python&logoColor=D97757)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1a1815?style=flat-square&logo=postgresql&logoColor=D97757)
![Linux](https://img.shields.io/badge/Linux-1a1815?style=flat-square&logo=linux&logoColor=D97757)
![Bash](https://img.shields.io/badge/Bash-1a1815?style=flat-square&logo=gnubash&logoColor=D97757)
![systemd](https://img.shields.io/badge/systemd-1a1815?style=flat-square&logo=systemd&logoColor=D97757)
![Tailscale](https://img.shields.io/badge/Tailscale-1a1815?style=flat-square&logo=tailscale&logoColor=D97757)

---

### 📦 More things I've built

| Project | What it is |
|---------|-----------|
| 🎮 **Minecraft server on Docker** | Turned an old machine into a containerized game server. |
| ☸️ **Minecraft server on Kubernetes** | Ran the same server on a `kind` Kubernetes cluster — hands-on with orchestration. |
| 🤖 **Self-learning bots** | Text-based input/output bots, then deployed to run themselves in the cloud. |

---

### 🛠️ What I work with

```text
Containers     Docker · Docker Compose · Kubernetes (kind) · orchestration
Networking     Tailscale / WireGuard · reverse proxy · TLS · WebSockets
Backend        Python (stdlib HTTP, HMAC auth) · REST · Postgres
Cloud / Linux  GCP · Ubuntu · systemd · cron/timers · backups · shell scripting
Security       least-privilege · session auth · brute-force defense · zero public exposure
Web            nginx · HTML/CSS/JS dashboards · same-origin design
```

---

### 📈 GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=xm0dx&show_icons=true&hide_border=false&bg_color=1a1815&title_color=d97757&icon_color=d97757&text_color=e8e3d8&border_color=3a3530" alt="stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=xm0dx&layout=compact&hide_border=false&bg_color=1a1815&title_color=d97757&text_color=e8e3d8&border_color=3a3530" alt="top languages" />

</div>

---

<div align="center">

📫 **Reach me** — [mick.aphisit@gmail.com](mailto:mick.aphisit@gmail.com)

<sub><i>Built on the Claude-terminal theme · #1a1815 / #d97757 · always learning by building.</i></sub>

</div>
