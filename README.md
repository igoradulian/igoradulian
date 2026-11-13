![Profile View Counter](https://komarev.com/ghpvc/?username=igoradulian)

<img src="https://capsule-render.vercel.app/api?type=wave&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Hi,%20I'm%20Igor%20Adulyan&fontSize=42&fontColor=ffffff&fontAlignY=38" width="100%" />

<p align="center">
  <b>Java / Spring &nbsp; •&nbsp; Python &nbsp;•&nbsp; Go &nbsp;•&nbsp; AI Automation &nbsp;•&nbsp; Distributed Systems</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/igor-adulyan/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:i.adulian@gmail.com"><img src="https://img.shields.io/badge/Gmail-C5221F?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/igoradulian?tab=repositories"><img src="https://img.shields.io/badge/Projects-24292F?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

---

## 💡 What I Do

|                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Focus**      | Backend engineering — streaming pipelines, distributed services, API design, AI automation                                                                                                                                                                                                                                                                                                                                                                                       |
| **Experience** | Go and Spring Boot services, HIPAA-compliant healthcare systems, EHR integration, AI inference APIs                                                                                                                                                                                                                                                                                                                                                                              |
| **Teaching**   | 3 years as Java Technical Instructor at Per Scholas — 90%+ cohort graduation rate![](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white) ![](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) |
| **Location**   | Los Angeles, CA · English / Russian / Armenian                                                                                                                                                                                                                                                                                                                                                                                                                                   |

---

## 🛰️ Featured: Satellite Telemetry Pipeline

Three repos, one system — GPS hardware to live browser dashboard:

```
gpsd → [Python collector] → MQTT/TLS → [Spring WebFlux] → SSE → [React dashboard]
```

| Stage | Repo | What it does |
|---|---|---|
| **Collect** | [python-data-sattelite-processing](https://github.com/igoradulian/python-data-sattelite-processing) | Reads `SKY` messages off the `gpsd` socket, publishes satellite payloads to MQTT over TLS |
| **Stream** | [spring-reactive-backend-SSE](https://github.com/igoradulian/spring-reactive-backend-SSE) | Reactive Spring Boot service on HiveMQ Cloud / MQTT v5, rebroadcasting as Server-Sent Events |
| **Visualize** | [satellite-tracking-dashboard-demo](https://github.com/igoradulian/satellite-tracking-dashboard-demo) | React 19 + Vite dashboard — signal quality, per-satellite telemetry, custom SVG sky plot |

Built to work through the hard parts of real-time delivery: backpressure, resilient stream subscription, and reconnect behavior when the source drops.

---

## 🛠️ Main Stack

<p align="center">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/WebFlux-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Gin-008ECF?style=for-the-badge&logo=gin&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

---

## 📚 Skills

- Distributed backend services in Go and Spring Boot
- Real-time streaming — MQTT, Server-Sent Events, reactive pipelines
- Async processing architecture with retry, timeout, and backpressure handling
- Systems integration — third-party EHRs (Epic, PointClickCare), HIPAA-compliant data flows
- Performance profiling and latency optimization across distributed components
- Test-driven development with JUnit, Mockito, and WebTestClient
- Technical instruction and mentorship — Java, microservices, clean code

---

## 📦 Other Projects

| Project | What it is | Stack |
|---|---|---|
| [multimodal-image-recognition-api](https://github.com/igoradulian/multimodal-image-recognition-api) | Routes text + image input to Ollama, OpenAI, and Gemini behind one interface | Go, Gin |
| [disk-cloning-tool](https://github.com/igoradulian/disk-cloning-tool) | Forensic disk duplicator — logical and raw imaging, parallel multi-target writes | Go, Wails, Svelte |
| [zetabooking-demo-project](https://github.com/igoradulian/zetabooking-demo-project) | Full-stack booking app — reservations, auth, admin, checkout | Spring Boot 3, MySQL |

---

<!-- OPTIONAL — uncomment if you're actively looking for work:
<p align="center">
  <b>Open to backend and platform engineering roles.</b>
</p>
-->

<img src="https://capsule-render.vercel.app/api?type=wave&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%" />
