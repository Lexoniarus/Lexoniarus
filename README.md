<div align="center">

# Alex · Lexoniarus

### Software Engineering · Applied AI · Realtime Systems · Simulation

I build software around **real workflows, structured data and complex system behavior** — from AI-assisted business applications to realtime simulations with autonomous agents.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-Realtime-4B5563?style=flat-square)
![AI Engineering](https://img.shields.io/badge/AI_Engineering-Applied_AI-6D28D9?style=flat-square)

</div>

## About

I'm currently completing a software engineering program with a focus on **AI Engineering**.

Before moving deeper into software development, I worked with business processes, sales controlling, CRM/ERP systems, Excel/VBA automation and BI/reporting. That background still strongly influences how I build software: I care about the domain model, the data behind it and what a system actually needs to accomplish for its users.

My current work is centered around two larger projects that explore very different engineering problems.

## Featured projects

### BENNO — Voice-assisted B2B visit report assistant

[![View BENNO](https://img.shields.io/badge/View_BENNO-Repository-181717?style=for-the-badge&logo=github)](https://github.com/Lexoniarus/BENNO)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-LLM-4285F4?style=flat-square&logo=google&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Speech](https://img.shields.io/badge/STT_%2F_TTS-Local-0F766E?style=flat-square)

BENNO turns natural-language meeting notes into structured, reviewable CRM/ERP-ready visit reports.

The project combines an AI-assisted conversation flow with deterministic application logic. The LLM can interpret and propose information, but validation, workflow state, CRM references and final writeback remain under application control.

**Engineering focus**

- structured LLM output and provider abstraction
- deterministic validation around probabilistic AI
- human review before business-system writeback
- local Speech-to-Text and Text-to-Speech
- CRM/ERP gateway abstraction with Mock-eNVenta
- authentication and role-based application flows
- observability and automated regression tests
- privacy-oriented path toward local AI providers

---

### TV Manager 2000 — Realtime TV management simulation

[![View TV Manager 2000](https://img.shields.io/badge/View_TV_Manager_2000-Repository-181717?style=for-the-badge&logo=github)](https://github.com/Lexoniarus/tv-manager-2000)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-Multiplayer-4B5563?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-Testing-2EAD33?style=flat-square&logo=playwright&logoColor=white)

TV Manager 2000 is a browser-based management game set in the DACH television market around 1990.

What started as a game prototype has grown into a larger realtime simulation: multiple competing television stations share markets, content, advertising opportunities and a running game world. Human players and autonomous bot-controlled stations operate under the same underlying rules.

**Engineering focus**

- authoritative Python/FastAPI realtime backend
- WebSocket multiplayer and shared world state
- 6–18 competing television stations
- utility-based autonomous bot decision systems
- programme scheduling and advertising economy
- content licensing and market simulation
- audience, transmitter and population modelling
- persistent seasons and reconnectable player ownership
- multi-day automated simulation and browser playtests
- separate content, population, rules and runtime data boundaries

## Engineering interests

I'm particularly interested in software where several layers meet:

- **Applied AI** — using language models for interpretation without handing them uncontrolled business decisions
- **Backend architecture** — clear ownership of state, domain rules and external-system boundaries
- **Simulation and agents** — systems whose behavior emerges over time instead of producing only one request/response result
- **Data engineering** — turning external and heterogeneous data into stable internal models
- **Testing and observability** — making complex or probabilistic behavior inspectable and reproducible

I tend to prefer **hybrid systems**: deterministic code where rules can be known, AI where interpretation is genuinely useful, and explicit boundaries between the two.

## Background

My earlier work includes business controlling, process development, CRM/ERP introduction and BI/reporting across heterogeneous data sources.

That experience is one reason I am interested in the space between pure software development and domain-heavy applications: understanding the process first, modelling it clearly, and then deciding which parts benefit from automation, AI or conventional software logic.

I also have a long-running background in music production and audio engineering. It remains an important creative part of my life, but it is no longer the focus of this profile.

## Current direction

My goal is to work on **AI-enabled software systems that are useful beyond the demo stage**.

That means not only connecting an API to an interface, but thinking about state, data quality, validation, failure modes, privacy, integration boundaries, testing and the people who eventually have to trust the result.
