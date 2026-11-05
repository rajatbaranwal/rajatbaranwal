<p align="center">
  <img src="https://raw.githubusercontent.com/rajatbaranwal/rajatbaranwal/main/pixel-jeff-matrix-s.gif" alt="Welcome GIF">
</p>

<h1 align="center">Rajat Baranwal</h1>

<p align="center">
  <a href="https://rajat-portfolio-lime.vercel.app/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=7AA2F7&center=true&vCenter=true&width=720&lines=Software+Engineer+%C2%B7+Backend+%26+AI+Integration;I+build+real-time+speech+%26+translation+pipelines;FastAPI+%C2%B7+WebSockets+%C2%B7+PostgreSQL+%C2%B7+Next.js;IEEE+co-author+%C2%B7+Oracle+Certified+Java+Developer;Open+to+full-time+SWE+roles+%F0%9F%9A%80" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://rajat-portfolio-lime.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-7AA2F7?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/rajat-baranwal"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:rajat123baranwal@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://ieeexplore.ieee.org/abstract/document/11576810/"><img src="https://img.shields.io/badge/IEEE-Publication-00629B?style=for-the-badge&logo=ieee&logoColor=white" alt="IEEE Publication"/></a>
  <a href="https://www.leetcode.com/rajat_bar"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=rajatbaranwal&label=Profile%20views&color=7aa2f7&style=flat-square" alt="Profile views" />
</p>

---

### `$ whoami`

```python
class Rajat:
    role       = "Software Engineer · Backend & AI Integration"
    education  = "B.Tech CSE @ SRM University AP ('26) · CGPA 8.24 · Merit Scholar"
    experience = "SWE Intern @ XiPHI AI, Seattle (Remote) · Apr – Oct 2026"
    builds     = ["real-time speech pipelines", "FastAPI services", "LLM workflows", "full-stack apps"]
    research   = "Co-author · IEEE CI2A 2026"
    certified  = ["Oracle Certified Professional: Java SE 11", "AWS Fundamentals"]
    status     = "Open to full-time Software Engineer roles 🚀"
```

---

### 💼 Experience: Software Engineer Intern @ XiPHI AI

I worked on **[myEventz.ai](https://myeventz.ai)**, building live transcription and translation for events, and **onboard.myeventz.ai**, the attendee onboarding platform.

```mermaid
flowchart LR
    A["🎙️ Live audio"] -->|WebSocket stream| B["⚡ FastAPI<br/>async service"]
    B --> C["ElevenLabs<br/>Scribe v2 Realtime"]
    C -->|partial + final<br/>transcripts| D[("PostgreSQL<br/>translation cache")]
    D -->|hit| F["🖥️ Next.js<br/>live captions"]
    D -->|miss| E["Gemini via n8n"]
    E -.->|cache result| D
    E --> F
```

- ⚡ **Real-time speech-to-text**: async audio streaming over WebSockets, handling both partial and final transcription events
- 🗄️ **LLM cost control**: a PostgreSQL translation cache that skips redundant Gemini / n8n workflow runs
- 📈 **Performance**: load-tested APIs with Apache JMeter + Grafana to find failures and latency bottlenecks under concurrent load
- 🔐 **Production**: integrated Cloudflare Turnstile and fixed deployment issues across Next.js, Docker, and containers
- 🧪 **R&D**: benchmarked Faster-Whisper with audio chunking, overlapping windows, and VAD; validated QR check-in with duplicate-scan detection

---

### 🚀 Featured projects

| | Project | Highlights | Stack |
|:-:|---|---|---|
| 🚗 | **[RoadResQ](https://github.com/rajatbaranwal/roadresq)** | Connects stranded drivers with mechanics; live GPS tracking during active requests; separate customer and mechanic dashboards | MERN · Socket.IO · Leaflet · JWT |
| 🏥 | **[MediQ](https://github.com/rajatbaranwal/mediq-platform)** | Global hospital discovery with geospatial search; appointments, OPD queues, bed and blood-inventory tracking; real-time updates | Next.js · TypeScript · Express · MongoDB · Socket.IO |
| ⚡ | **[Real-Time Sales Pipeline](https://github.com/rajatbaranwal/real-time-sales-streaming-pipeline)** | Kafka producer–consumer streaming into PostgreSQL, with a live Streamlit KPI dashboard | Kafka · PostgreSQL · Python · Streamlit |

---

### 📄 Research

> **Co-author**: research paper published at **IEEE CI2A 2026** · [Read on IEEE Xplore →](https://ieeexplore.ieee.org/abstract/document/11576810/)

---

### 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,cpp,js,ts&theme=dark" alt="Languages"/><br/>
  <img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,kafka,postgres,mongodb,mysql&theme=dark" alt="Backend & data"/><br/>
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css&theme=dark" alt="Frontend"/><br/>
  <img src="https://skillicons.dev/icons?i=docker,aws,git,linux,postman,grafana,vercel&theme=dark" alt="DevOps & tools"/>
</p>

<p align="center">
  <b>AI & Speech</b>&nbsp; Gemini · ElevenLabs Scribe v2 · Faster-Whisper · VAD · n8n
</p>

---

### 📊 GitHub activity

<p align="center">
  <img width="100%" src="./profile-summary-card-output/tokyonight/0-profile-details.svg" alt="Profile details"/>
</p>

<p align="center">
  <img width="49%" src="./profile-summary-card-output/tokyonight/3-stats.svg" alt="GitHub stats"/>
  <img width="49%" src="./profile-summary-card-output/tokyonight/2-most-commit-language.svg" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=rajatbaranwal&hide_border=true&theme=tokyonight" alt="GitHub streak"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rajatbaranwal/rajatbaranwal/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/rajatbaranwal/rajatbaranwal/output/github-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/rajatbaranwal/rajatbaranwal/output/github-snake-dark.svg" />
  </picture>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,100:bb9af7&height=110&section=footer&text=Let's%20build%20something%20real-time&fontSize=20&fontColor=ffffff&fontAlignY=70" alt="Footer"/>
</p>
