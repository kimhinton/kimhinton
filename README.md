# Kim M. Hinton

Backend engineer building developer tools and automation. Working mostly in Python and TypeScript.

---

## Currently Building

### [endpulse](https://github.com/kimhinton/endpulse) — async Python CLI for multi-endpoint API health checks

[![PyPI](https://img.shields.io/pypi/v/endpulse.svg)](https://pypi.org/project/endpulse/)
[![Downloads](https://img.shields.io/pepy/dt/endpulse?label=downloads)](https://pepy.tech/project/endpulse)
[![Docs](https://img.shields.io/badge/docs-online-blue)](https://kimhinton.github.io/endpulse/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/kimhinton/endpulse/blob/main/LICENSE)

Lightweight CLI for running concurrent HTTP health checks with response-body assertions, SSL certificate expiry tracking, and webhook alerts — all from a single `pip install`. Built on `aiohttp` + `click` + `rich`. Runs in CI pipelines, cron jobs, on-call terminals, and Kubernetes init containers — anywhere a post-deploy health gate is needed without standing up a monitoring server.

### [keystrum](https://keystrum.app) — browser-based QWERTY guitar chord strum machine

[![Live](https://img.shields.io/badge/app-keystrum.app-black?style=flat-square)](https://keystrum.app)
[![Stars](https://img.shields.io/github/stars/kimhinton/keystrum?style=flat-square&logo=github)](https://github.com/kimhinton/keystrum)
[![Stack](https://img.shields.io/badge/Next.js_16-React_19-000000?style=flat-square&logo=next.js)](https://github.com/kimhinton/keystrum)

A browser-based virtual guitar that maps your QWERTY keyboard to a 6-chord strum machine. Four rows become four strings, six columns become six diatonic chords (Am/C/Em/G/Dm/F). Real strum detection (sweep 3+ keys in 90 ms) and Karplus-Strong physical-modeling synthesis run live in Web Audio — no install, no samples, no account. Ships as a PWA and as native iOS / Android apps via Capacitor from the same source.

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Web Audio](https://img.shields.io/badge/Web_Audio-FF6B35?style=flat-square&logo=webassembly&logoColor=white)

---

## What I Build

- **CLI tools and developer tooling** — endpulse-style utilities that replace ad-hoc shell pipelines
- **Async Python for I/O-bound workloads** — `aiohttp`, `httpx`, `asyncio` concurrency patterns
- **Web audio experiments** — keystrum is a creative outlet when backend work leaves room
- **Automation pipelines** — CI/CD, deployment, and monitoring workflows on GitHub Actions

---

## Related projects

- [til](https://github.com/kimhinton/til) — Today I Learned: daily dev notes across Python, Go, JavaScript, Docker, databases, and more.
- [awesome-devops](https://github.com/kimhinton/awesome-devops) — Fork of the community-curated DevOps resource list.
- [awesome-cli-apps](https://github.com/kimhinton/awesome-cli-apps) — Fork of the community-curated CLI applications list.
- [awesome-webaudio](https://github.com/kimhinton/awesome-webaudio) — Fork of the community-curated Web Audio resource list.

---

## GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=kimhinton&show_icons=true&theme=default&hide_border=true&count_private=true&hide_title=true" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kimhinton&layout=compact&theme=default&hide_border=true" alt="Top Languages" height="165" />
</p>

---

<sub>Open to backend tooling collaborations. Currently most active in <a href="https://keystrum.app">keystrum.app</a> — design feedback or first contributions welcome (<a href="https://github.com/kimhinton/keystrum/issues">open an issue</a> or DM).</sub>
