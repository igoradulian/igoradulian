![Profile View Counter](https://komarev.com/ghpvc/?username=igoradulian)

<!--**igoradulian/igoradulian** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.-->

# Igor Adulyan

**Backend Engineer — Go · Java/Spring · Distributed Systems**
Los Angeles, CA · [LinkedIn](https://www.linkedin.com/in/igor-adulyan/)

I build backends that move data reliably under load — streaming pipelines, async processing, and the APIs between them. Most of my production work has been in regulated, high-throughput environments: HIPAA-compliant healthcare microservices, EHR interoperability, and AI inference services behind mobile apps.

I also spent three years teaching Java and microservices at Per Scholas, which is where I learned that if you can't explain the design, you don't understand it yet.

---

## Satellite telemetry pipeline

Three repos, one system — GPS hardware to live browser dashboard, end to end:

```
gpsd → [Python collector] → MQTT/TLS → [Spring WebFlux] → SSE → [React dashboard]
```

| Stage | Repo | What it does |
|---|---|---|
| Collect | [python-satellite-processing](https://github.com/igoradulian/python-data-sattelite-processing) | Reads `SKY` messages off the `gpsd` socket, builds satellite payloads, publishes to MQTT over TLS |
| Stream | [spring-reactive-backend-SSE](https://github.com/igoradulian/spring-reactive-backend-SSE) | Reactive Spring Boot service subscribing to HiveMQ Cloud over MQTT v5, rebroadcasting as Server-Sent Events |
| Visualize | [satellite-tracking-dashboard-demo](https://github.com/igoradulian/satellite-tracking-dashboard-demo) | React 19 + Vite frontend consuming the SSE stream — signal quality, per-satellite telemetry, custom SVG sky plot |

Built to work through the hard parts of real-time delivery: backpressure, resilient stream subscription, and reconnect behavior when the source drops. Transmits only satellite position and quality metrics — never user coordinates.

**Stack:** Python 3.14 · Java 17 · Spring Boot WebFlux · Reactor · HiveMQ MQTT v5 · React 19 · Vite · SSE

---

## Other work

**[multimodal-image-recognition-api](https://github.com/igoradulian/multimodal-image-recognition-api)** — Go
Go/Gin API accepting text + image input and routing to three inference backends: local Ollama, OpenAI vision, and Google Gemini. Provider abstraction means swapping or adding a model doesn't touch handler code.

**[disk-cloning-tool](https://github.com/igoradulian/disk-cloning-tool)** — Go
Forensic disk duplicator with two imaging modes (logical volume and raw physical), parallel writes to multiple targets, and live throughput/ETA reporting. Go backend with a Wails v2 + Svelte desktop shell. Windows is the primary implementation path.

**[zetabooking-demo-project](https://github.com/igoradulian/zetabooking-demo-project)** — Java
Full-stack booking application on Spring Boot 3 — reservations, auth, admin management, image upload, and a simulated checkout flow. Java 17, Spring Security, Data JPA, Thymeleaf, MySQL, OpenAPI docs.

---

## Stack

**Languages** Go · Java · Python · JavaScript/TypeScript
**Backend** Spring Boot · Spring WebFlux · Spring Cloud · Gin · REST · SSE · MQTT
**Data** PostgreSQL · MySQL · Redis
**Frontend** React · Svelte · Vite
**Practice** Microservices · event-driven architecture · TDD (JUnit, Mockito) · Docker · Linux

---

## Background

**Senior Software Engineer**, Serfic — led an iOS app and its Spring Boot + Go backend with AI image recognition; designed the async upload → inference → delivery pipeline
**Java Technical Instructor**, Per Scholas — 3 years teaching Java, microservices, and TDD to career-changing engineers; 90%+ cohort graduation rate
**Senior Software Engineer**, KrypticMED — HIPAA-compliant healthcare microservices, Epic and PointClickCare EHR integrations, Redis-backed data layer
**Freelance Software Engineer** — custom software for LA-area clients, 2017–2021

English · Russian · Armenian

<!-- OPTIONAL — uncomment if you're actively looking:
---
**Open to backend and platform engineering roles.** Reach me on [LinkedIn](https://www.linkedin.com/in/igor-adulyan/).
-->
