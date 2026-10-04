# Hi, I'm 3uba 👋

Backend developer, learning offensive security on the side. I like building
small, focused tools that do one thing well, usually in Python, Go, or
TypeScript.

### 🔧 What I'm working on

| Project | What it is | Stack |
| --- | --- | --- |
| [**trex**](https://github.com/3uba/trex) | Send raw HTTP requests from a text file, with ffuf-style fuzzing and regex match/filter/extract. Burp Repeater + Intruder for the terminal. | Python |
| [**redeye**](https://github.com/3uba/redeye) | Screenshot and recon web targets into one self-contained HTML report. Native on Apple Silicon, no Docker or Selenium. | Python |
| [**skyvern-ui**](https://github.com/3uba/skyvern-ui) | Self-hosted web UI for the Skyvern browser-automation platform, adding auth, RBAC, and a secure API proxy. | Next.js / TypeScript |
| [**deploytool**](https://github.com/3uba/deploytool) | Single-binary CLI for deploying Git projects to a Linux server, with versioned backups and Docker builds. | Go |

### 🧰 Tech I reach for

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/-Next.js-000000?logo=nextdotjs&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black)

### 🛡️ Into

Web security, recon and pentest tooling, CTFs, and self-hosting. Most of my
public repos are the tools I wanted while learning.

---

<details>
<summary>🐳 A few docker aliases I keep in my <code>.bashrc</code></summary>

```bash
alias dps='docker ps --format "table {{.Names}}\t{{.Image}}\t{{.Status}}"'
alias dpp='docker ps --format "table {{.Names}}\t{{.Status}}\t{{.Ports}}"'
alias de='f() { docker exec -it "$@" bash; unset -f f; }; f'
alias deu='f() { docker exec -u root -it "$@" bash; unset -f f; }; f'
```

</details>
