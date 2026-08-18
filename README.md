<div align="center">

# Alex · Lexoniarus

### Software Engineering · AI Engineering · Backend & Realtime Systems

I build software that turns **messy real-world input or complex system state into reliable, testable behavior**.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-Realtime-4B5563?style=flat-square)

</div>

## About

I'm currently completing a software engineering program with a focus on **AI Engineering**.

My earlier work was rooted in business IT: sales controlling, process development, CRM/ERP systems, Excel/VBA automation and BI/reporting. That background still shapes how I build software today — I tend to start with the domain, the data and the actual workflow before choosing the technology.

My public projects also show a fairly visible progression: from a small, contained game MVP to larger systems involving AI, realtime state, autonomous agents, external data and much broader test coverage.

## Featured projects

### BENNO — Voice-assisted B2B visit report assistant

[![View BENNO](https://img.shields.io/badge/View_BENNO-Repository-181717?style=for-the-badge&logo=github)](https://github.com/Lexoniarus/BENNO)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-LLM-4285F4?style=flat-square&logo=google&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![Speech](https://img.shields.io/badge/STT_%2F_TTS-Local-0F766E?style=flat-square)

BENNO turns natural-language meeting notes into structured, reviewable CRM/ERP-ready visit reports.

The key design decision is that the AI **interprets and proposes**, while application code remains responsible for validation, workflow state and writeback.

**Focus:** structured LLM output · deterministic validation · provider abstraction · local STT/TTS · CRM/ERP gateway boundaries · human review · regression testing

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

It has grown from a game prototype into a server-authoritative realtime simulation with shared markets, multiplayer state and autonomous competing stations operating under the same rules as human players.

**Focus:** FastAPI/WebSocket runtime · authoritative shared state · utility-based bot decisions · scheduling/economy simulation · content and population data · persistence · multi-day simulation and browser playtests

## Earlier MVP · visible progression

### Tavernenbank

[![View Tavernenbank](https://img.shields.io/badge/View_Tavernenbank-Repository-181717?style=for-the-badge&logo=github)](https://github.com/Lexoniarus/tavern_blackjack)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Arcade](https://img.shields.io/badge/Arcade-3.x-2E8B57?style=flat-square)
![Status](https://img.shields.io/badge/Status-Archived_MVP-6B7280?style=flat-square)

Tavernenbank is a small playable Python/Arcade card-game MVP with NPC opponents, graphical and command-line interfaces, integrated assets and unit tests.

I keep it public deliberately. It represents an earlier stage of my development and makes the progression toward BENNO and TV Manager 2000 much easier to see: from finishing a contained game loop to designing larger systems with clearer boundaries, more state, broader testing and substantially more backend responsibility.

## How I tend to build

Different domains, same underlying principles:

- use **deterministic code** for rules that can be known
- use **AI** where interpretation of ambiguous input is actually useful
- keep one clear owner for important state and business decisions
- separate source data, runtime state and presentation concerns
- test complete behavior, not only individual functions

I am less interested in adding technology for its own sake than in deciding **where a responsibility belongs and how to make the result observable and reliable**.

## Background

I am a trained business IT assistant for information processing (`Wirtschaftsassistent für Informationsverarbeitung`). My earlier work included sales controlling, CRM/ERP introduction, process development and BI/reporting across heterogeneous data sources.

I also have a long-running background in music production and audio engineering. It remains an important creative part of my life, but the professional focus here is software and AI engineering.
