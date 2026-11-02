<h1 align="center">Nursultan Dauletkan</h1>

<p align="center">
  <b>DevOps · Backend Engineer</b><br>
  Almaty, Kazakhstan
</p>

<p align="center">
  <a href="https://t.me/Goslinuly">Telegram @Goslinuly</a> ·
  <a href="https://hackathon.kz">hackathon.kz</a>
</p>

---

Hey girl. I know you came here looking for a senior SRE with 10 years of on-call trauma and a MIT degree. I'm just a guy from Almaty who said "it works on my machine" one too many times, so now I ship the machine. In a Docker container. With a Jenkinsfile.

I'm just DevOps. Anywhere else I'd be a 10. 🩷

By day I run [hackathon.kz](https://hackathon.kz), the home of every hackathon in Kazakhstan, and handle the 3 AM fixes nobody thanks me for. When production catches fire I sit in the middle of it, sip my coffee and say "this is fine". Then I actually fix it, add a test, and make sure it never happens again.

I don't always test my code. But when I do, it's 180+ pytest tests, Playwright on every page and a fuzzer pointed at my own production API. I'm literally him.

---

## What I do

**Infrastructure and DevOps**
- CI/CD pipelines in Jenkins: checkout, build, test, Docker image build and run, credentials from the Jenkins store
- Docker and Docker Compose for local and production setups, multi-service projects
- Deploys on Railway: web service, Telegram bot, cron workers, PostgreSQL, persistent volumes
- Cloudflare in front of the API: own subdomain, DNS, proxy and cache rules
- Database backups and restore scripts with checksums and row-count verification
- Linux and Bash scripting, system reports, automation

**Backend**
- Python: FastAPI, SQLAlchemy 2, Alembic migrations, Flask, pytest
- Java: Spring Boot 3, Gradle, REST APIs with PostgreSQL
- PostgreSQL: schema design, migrations, query tuning, JSON columns
- Telegram bots on aiogram, integrations with the GitHub API and LLM APIs (Claude, OpenAI)
- Security basics: OAuth with one-time state, SSRF-safe fetchers, rate limits, CSRF, open-redirect fixes, fuzz testing of public endpoints

**Testing and quality**
- pytest suites, end-to-end and visual checks with Playwright
- Mutation-style fuzzing of production endpoints, layout-shift and mobile checks before every release

---

## Stack

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat&logo=railway&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bots-26A5E4?style=flat&logo=telegram&logoColor=white)

![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)

---

## Projects

### [hackathon.kz](https://hackathon.kz)
The platform with every hackathon in Kazakhstan: event catalog, team registration and a Telegram bot for participants.

### [Student API](https://github.com/Goslinuly/goslinuly-student-api)
Spring Boot CRUD API with PostgreSQL, Docker Compose and a Jenkins pipeline (build, test, Docker image, verify).

**Stack:** `Java 17` `Spring Boot 3` `Gradle` `PostgreSQL 16` `Docker Compose` `Jenkins`

### [DevOps Lab](https://github.com/Goslinuly/goslinuly-devops)
Python service with a Dockerfile, Compose setup, Linux system report script and a Jenkins pipeline from checkout to running container.

**Stack:** `Python` `Docker` `Jenkins` `Bash`

### [MedRate](https://github.com/Goslinuly/MedRate)
Turns clinic price lists in any format (Excel, PDF, Word, scanned photos, Russian and Kazakh) into one searchable database.

**Stack:** `Python` `FastAPI` `Gemini API` `pdfplumber` `pandas` `TypeScript`

---

## Work projects

- **Aviation sourcing platform** · B2B procurement workflow for aviation parts (closed pilot): backend, workspace, WhatsApp integration
- **Vivid CRM** · PWA for automotive parts sales: smart pricing, WhatsApp inbox, notifications, virtual PBX
- **Plait (QR-cafe)** · QR menu and restaurant system: guest menu, staff panel, real-time kitchen board
- **School olympiads catalog** · catalog of school olympiads in Kazakhstan with calendar, practice tasks and reminders (diploma project)
- **QADAM** · platform where students, developers and founders find teammates and projects
- **Aqmamyq Luxe Linen** · company website on Express, hosted on Railway
- **Volunteer platform** · volunteer management with three roles, moderation, events and hours tracking (Node.js, Express, SQLite, JWT)
- **2GIS parser** · collects Almaty companies across 26 categories, deduplicates and exports to Excel

---

## Hackathons

Team **Hahathon Devs**

- **NASA Space Apps** · *Martian Map*: interactive guide across the whole map of Mars with route planning (FastAPI, PostGIS, Celery, React, Docker Compose)
- **Decentrathon 6.0** · *Soup Kernel Challenge*: custom Triton kernels for LoRA fine-tuning of Qwen2.5-1.5B on a free Kaggle T4, 1.6–1.7x faster and 4.9x less memory
- **HACKALEM AI 2026** · AI shopping assistant for an electrical goods retailer: catalog search, specs, stock, analogs and cart checks on PostgreSQL
- **NU Hackathon** · participant with *TechVision*: Aqıqat, a Telegram bot against misinformation in Kazakh and Russian that explains manipulation techniques instead of a bare "fake" verdict
- **Organizer side** · [hackathon.kz](https://hackathon.kz)

---

## Education

Bachelor's in Software Engineering

**Courses:** AWS Storage · Python Data Structures · Algorithmic Toolbox · English for IT

---

## Languages

| Language | Level |
|---|---|
| Kazakh | Native |
| Russian | Fluent |
| English | Technical |
