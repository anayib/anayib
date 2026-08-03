# Nayib Abdala

**Lead / Senior Software Engineer — Distributed Backends, Data Platforms & Applied AI**
📍 Barcelona · Paris · 🌍 Remote-first · 🗣️ Spanish (native) · English & French (full professional)

I design and ship software for organizations that operate in **sensitive, high-impact environments** — primarily NGOs raising funds for their causes, where a dropped message, a mis-ordered transaction or a silently wrong number has consequences beyond a dashboard.

Ten-plus years building and leading tech ventures (one acquired, scaled to customers in **36 countries**), now deliberately **hands-on in an engineering career**. That combination is the whole point: I write the production code, and I can also sit with a customer, understand their workflow, security requirements and business objectives, and translate them into an architecture that survives contact with reality.

---

## What I do

- **Build reliable, secure, maintainable and performance-accurate products** — with a strong bias toward *correctness you can prove*, not correctness you assume.
- **Lead the development and optimization of AI systems** — currently Fundraising AI Software Services: LLM integrations, RAG, and agentic workflows in production.
- **Work directly with customers** to surface their real workflows, technical constraints, security requirements, and strategic product and business objectives.
- **Software architecture & software development** — distributed services, message-driven pipelines, and the data layer underneath them.
- **Solve problems end to end.** Ambiguous symptom → reproducible cause → durable fix → a check that stops it recurring. I've built a career out of the middle two steps, and I work from an explicit method rather than intuition alone.

---

## Currently

**Lead AI Product Engineer | Software Engineer** — *Afrus Impact Technologies Corporation* · Oct 2025 → present

Leading AI product engineering on a multi-tenant SaaS platform, working across API services, background workers, message-driven pipelines and the data layer underneath them.

Where I bring the most value:

- **Data-integrity engineering** — treating the write path as a contract rather than a convention: explicit invariants on every service that produces data others depend on, enforced at the boundary and verified continuously. Large-scale historical backfills done conservatively — an unknown value stays unknown.
- **Distributed systems in Go and TypeScript** — service and worker design, queue-driven architectures, idempotency and retry semantics, and the observability to know they're behaving.
- **Data platform & ETL engineering** — batch and incremental extraction, watermark strategies, warehouse modelling, and modernizing legacy pipeline tooling into maintainable, tested, instrumented services.
- **Root-cause forensics** — the bug that only appears in production. Depth across the failure classes that make data systems lie: time-window and watermark arithmetic, load idempotency, query plans that degrade at real volume, and database configuration whose true effect on constraint behavior differs from what a surface-level check suggests. Findings get written up, so the next engineer inherits knowledge instead of a mystery.
- **Performance & correctness of the numbers** — reconciling systems where two "sources of truth" disagree, and making reported figures defensible. Including the counter-intuitive work: relational storage internals where a table's apparent size and its actual scan cost have little to do with each other, and adding an index is the wrong answer.
- **Security engineering as routine practice** — the quiet failure modes: secret and token handling across service boundaries, configuration traps where a missing value silently weakens a guarantee instead of failing loudly, write paths that bypass application-layer validation, and swallowed errors. I find these by reading code adversarially, and I verify a fix by breaking the guard and confirming the test goes red.
- **Spec-driven delivery** — requirement/scenario specs that double as the test suite, so behavior is agreed before code exists.
- **Applied AI in production** — LLM integrations, RAG, and agentic workflows built to the same reliability bar as the rest of the platform.

---

## Tech

**Languages**
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & architecture**
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-2F855A?style=flat-square)
![REST](https://img.shields.io/badge/REST_APIs-005571?style=flat-square)
![Event_Driven](https://img.shields.io/badge/Event--Driven_Systems-6B46C1?style=flat-square)

**Data & pipelines**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![OLTP](https://img.shields.io/badge/OLTP-336791?style=flat-square)
![ETL](https://img.shields.io/badge/ETL_%26_Warehousing-C43E1C?style=flat-square)
![Drizzle](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)

**Queues & messaging**
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-E10098?style=flat-square)
![Pub/Sub](https://img.shields.io/badge/Async_Workers-455A64?style=flat-square)

**Applied AI**
![LLMs](https://img.shields.io/badge/LLMs-412991?style=flat-square&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-0F766E?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![Agents](https://img.shields.io/badge/Agentic_Systems-7C3AED?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-D97706?style=flat-square)

**Cloud & infrastructure**
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Web Components](https://img.shields.io/badge/Web_Components-29ABE2?style=flat-square)

**Practices**
`Open Specs / spec-driven development` · `TDD` · `code review` · `observability` · `incident forensics` · `secure-by-default design` · `AI-assisted engineering workflows`

---

## How I work

- **Correctness first, and prove it.** A green catalog check is not evidence. I verify the behavior — mutate the guard and watch the test go red, quote the line that returns the promise, confirm the query actually constrains what I claim it constrains.
- **Never invent data.** In a backfill, an unknown timestamp stays NULL. Fabricated values are worse than missing ones because they look like facts.
- **Write the finding down.** Incidents and non-obvious system behavior get documented where the next engineer will actually find them.
- **Specs before code.** Requirements as WHEN/THEN scenarios that become the test names — the fastest way to find out that two people meant different things.
- **Reviews are for defects, not for taste.** If I find one, I say so plainly and it blocks.
- **Small, reversible changes** over big-bang rewrites — even when the rewrite is the right destination.

---

## Entrepreneurial track record

I've been on both sides of the table: building the product and owning the business outcome.

**Make it Real** — *Founder Software Engineer (C-Corp) | Product Owner* · 2020–2025 (partner & adviser since 2014)
Built MVPs fast and scaled them. Shipped LLM-powered features including API integrations and RAG. Ran deep user research, owned the backlog, and bridged business, product and engineering.

**ConvertLoop** — *CEO | Tech Founder — acquired 2019* · 2016–2020
Designed and built a marketing-automation platform from zero: the behavior-tracking engine and the multichannel messaging MVP, written by hand. Built behavior-based messaging, API integrations across marketing channels (Facebook, Zapier, CRMs) and the data-ingestion pipelines behind them. Acquired the first 100 customers and scaled the base to **36 countries**. Built and led the tech team while staying a hands-on coder and reviewer.

**Lean Innovation Group** — *Founder Managing Partner → Adviser* · 2011–2020
Service design, product development and go-to-market for internet products, as engineer and as strategist.

**Apps.co (Colombian Ministry of ICT)** — *Co-creator & adviser* · 2012–2013
Helped create the largest internet-entrepreneurship community in Colombia and mentored hundreds of founders — including teams that went on to Y Combinator, 500 Startups, and public listings.

**Mentor & adviser:** Google (Product Strategy Mentor, 2015–2020) · Wayra · MassChallenge · Startup Weekend · Lean Startup Machine · Intel Corporation & Young Americas Business Trust

---

## Education & credentials

- **MSc, Knowledge & Information Management** — Université Paul Valéry, Montpellier III (2008–2009) — software, AI, data, NLP, neural networks
  *Researcher there 2008–2011: information systems, NLP, neural networks, data pipelines*
- **MBA, Management & Strategic Planning** — Universidad Francisco de Vitoria (2007–2008)
- **Launch School** — Computer Software Engineering (2018–2020)
- **Make it Real** — Full Stack Web Developer Bootcamp (2014–2015)
- **Harvard University** — Teaching for Understanding, certified (2012)
- Certifications: Open Source AI Models · Hugging Face Agents · Foundations of Agents · Node.js Application Development (Linux Foundation) · Python for Data Science and AI · React Bootcamp

---

## Open to

**Lead / Staff / Senior Backend & Platform Engineering** roles — distributed systems, data platforms, and applied AI — where the work is genuinely hard and correctness matters. Remote, Barcelona or Paris.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nayibabdala/)
[![Email](https://img.shields.io/badge/Email-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:nayib.abdala@protonmail.com)
[![Hashnode](https://img.shields.io/badge/Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white)](https://hashnode.com/@nayib)

<!--
GitHub note: this README lives in anayib/anayib and renders on github.com/anayib
-->
