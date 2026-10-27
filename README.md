# Enzo Vaccaro

**Senior AI Automation Engineer · Backend & Integrations** · Brazil, remote (UTC-3, overlaps US Eastern)

I build AI systems that run real operations: WhatsApp agents that answer and qualify leads, back offices that act on
their own, and the infrastructure that keeps them up. 4+ years shipping LLM workflows to production for businesses,
end to end, from discovery to support.

[LinkedIn](https://www.linkedin.com/in/enzo-vaccaro-63915732b) · [YouTube (Claude Code tutorials, PT-BR)](https://www.youtube.com/@EnzoVaccaro-AI) · enzovaccaro112@gmail.com

---

### Public repositories

| Repository | What it shows |
|---|---|
| [**ssa-framework**](https://github.com/Sataker/ssa-framework) | Open-source core of the multi-agent system I run 24/7: one specialist agent per Discord channel on Claude Code CLI, persistent memory, LLM-as-judge evaluation, task pipelines, delegation between agents, circuit breaker and tracing. Node.js, SQLite (WAL). |
| [**contabot**](https://github.com/Sataker/contabot) | WhatsApp automation for accounting firms: Claude reads receipts and tax forms (vision + PDF), returns structured JSON, files them in Drive, logs to Sheets, answers simple questions and escalates the rest. Confidence threshold sends low-certainty documents to human review. n8n, Python, LLM APIs. |
| [**contabot-saas**](https://github.com/Sataker/contabot-saas) | Multi-tenant dashboard for the same product: every query scoped by tenant, cross-tenant access tested with curl attacks, auth with Auth.js. Next.js, TypeScript, Prisma. |
| [**agroinsight-api**](https://github.com/Sataker/agroinsight-api) | AI advisor for farmers: scheduled pipelines pull public market and climate data, build a per-farm context and get prioritized actions from an LLM, validated against a strict output contract before saving. Python, FastAPI, async SQLAlchemy, pytest + GitHub Actions. |
| [**ssa-framework-claude-code**](https://github.com/Sataker/ssa-framework-claude-code) | Claude Code setup with persistent memory, a cascade of specialist subagents with contracts between phases, a quality hook after every edit and a Playwright QA crawler. |
| [**trello-claude-code**](https://github.com/Sataker/trello-claude-code) | Claude Code skill for Trello with an OAuth 2.0 flow (local callback, token refresh) in standard-library Python. |

### Client work (private repositories)

Most of my production work belongs to clients, so the code is private. Architecture walkthroughs on request.

- **AI admissions platform, 12 universities (Spain):** answers and qualifies ~125,000 leads a year on WhatsApp.
  n8n, Python, Zoho CRM API, Woztell, Directus back office where staff edit courses, prices and the AI's instructions.
- **Public-health medication delivery (Brazil, SUS):** serverless API on AWS Lambda, PostgreSQL + PostGIS, route
  optimization with OR-Tools; designing the FHIR-integrated successor.
- **E-commerce back office with 12 AI agents:** purchasing, pricing, invoicing, marketplaces and receivables; the
  purchasing agent projects demand, nets out stock and builds the supplier order on its own.
- **AI sales funnels on WhatsApp:** LLM agents on n8n and Chatwoot that qualify, follow up and hand off with context.

### Stack

**AI:** Claude / Anthropic API, OpenAI, Gemini, Claude Code (subagents, hooks, skills, MCP), structured output, prompt caching, LLM evaluation
**Automation & integrations:** n8n, WhatsApp APIs, Chatwoot, Zoho CRM, Google Workspace APIs, REST/webhooks, OAuth 2.0
**Backend:** Python (FastAPI), Node.js / TypeScript, Next.js, PostgreSQL, SQLite, Prisma, SQLAlchemy
**Infra:** Linux, Docker / Compose / Swarm, Traefik, AWS Lambda, Redis, RabbitMQ, CI/CD (GitHub Actions)

English fluent · Italian advanced · Portuguese native
