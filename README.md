<!-- ╔══════════════════════════════════════════════════════════════╗ -->
<!-- ║  xm0dx · GitHub profile README                                 ║ -->
<!-- ║  Theme: light-blue terminal — bg #0f1620 · accent #5BC0EB     ║ -->
<!-- ╚══════════════════════════════════════════════════════════════╝ -->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=30&pause=1200&color=5BC0EB&center=true&vCenter=true&width=760&height=70&lines=Hi%2C+I'm+Mick+%C2%B7+%40xm0dx;Aspiring+Cybersecurity+%2F+DevOps+Engineer;I+self-host+my+own+cloud%2C+one+container+at+a+time." alt="typing banner" />

<br/>

![Focus](https://img.shields.io/badge/focus-cybersecurity_&_DevOps-0f1620?style=flat-square&logo=linux&logoColor=5BC0EB)
![Infra](https://img.shields.io/badge/infra-self--hosted-0f1620?style=flat-square&logo=docker&logoColor=5BC0EB)
![Networking](https://img.shields.io/badge/networking-zero--trust-0f1620?style=flat-square&logo=tailscale&logoColor=5BC0EB)
![Style](https://img.shields.io/badge/style-everything--as--code-0f1620?style=flat-square&logo=gnubash&logoColor=5BC0EB)

</div>

---

```text
$ whoami
> Mick (@xm0dx) — aspiring Cybersecurity / DevOps engineer.
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

<div align="center">

<a href="https://github.com/xm0dx/homelab">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=xm0dx&repo=homelab&bg_color=0f1620&title_color=5bc0eb&icon_color=5bc0eb&text_color=d6e9f7&border_color=25394d" alt="homelab" />
</a>
<a href="https://github.com/xm0dx/finance-planner">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=xm0dx&repo=finance-planner&bg_color=0f1620&title_color=5bc0eb&icon_color=5bc0eb&text_color=d6e9f7&border_color=25394d" alt="finance-planner" />
</a>
<a href="https://github.com/xm0dx/web-health-check">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=xm0dx&repo=web-health-check&bg_color=0f1620&title_color=5bc0eb&icon_color=5bc0eb&text_color=d6e9f7&border_color=25394d" alt="web-health-check" />
</a>
<a href="https://github.com/xm0dx/minecraft-server">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=xm0dx&repo=minecraft-server&bg_color=0f1620&title_color=5bc0eb&icon_color=5bc0eb&text_color=d6e9f7&border_color=25394d" alt="minecraft-server" />
</a>
<a href="https://github.com/xm0dx/RBLX-mechanic">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=xm0dx&repo=RBLX-mechanic&bg_color=0f1620&title_color=5bc0eb&icon_color=5bc0eb&text_color=d6e9f7&border_color=25394d" alt="RBLX-mechanic" />
</a>

</div>

- **[homelab](https://github.com/xm0dx/homelab)** — self-hosted infrastructure platform: ~18 Docker services behind one reverse proxy on a private Tailscale mesh, with a custom auth gate, monitoring, and automated backups.
- **[finance-planner](https://github.com/xm0dx/finance-planner)** — a personal finance planner: single-page web app with a small Python persistence API.
- **[web-health-check](https://github.com/xm0dx/web-health-check)** — a server-side website health checker (Python microservice behind nginx).
- **[minecraft-server](https://github.com/xm0dx/minecraft-server)** — a Minecraft server deployed on a Kubernetes (`kind`) cluster. Started on Docker, then moved to k8s to get hands-on with orchestration.
- **[RBLX-mechanic](https://github.com/xm0dx/RBLX-mechanic)** — a Roblox game mechanic built in Lua.
- **Discord bot** *(private)* — an automation/chat bot, plus self-learning text-I/O experiments that later ran themselves in the cloud.

---

### What I work with

```text
Containers     Docker · Docker Compose · Kubernetes (kind) · orchestration
Networking     Tailscale / WireGuard · reverse proxy · TLS · WebSockets
Backend        Python (stdlib HTTP, HMAC auth) · REST · Postgres
Cloud / Linux  GCP · Ubuntu · systemd · cron/timers · backups · shell scripting
Security       least-privilege · session auth · brute-force defense · zero public exposure
Web            nginx · HTML/CSS/JS dashboards · same-origin design
```
