<div align="center">

# Evandro Fonseca Junior

**Backend engineer building production systems, integrations, and local-first AI tooling.**

Garuva, Santa Catarina, Brazil · UTC-3 · Remote

**Open to backend engineering roles and technical collaborations.**

[Work](#selected-work) · [Stack](#stack) · [Gitea](https://git.evandro.dev.br/evandro) · [Portfolio](https://evandro.dev.br) · [LinkedIn](https://www.linkedin.com/in/evandrodevbr/) · [Contact](#contact)

</div>

> **Where my work lives now**
>
> My former GitHub account was suspended after one of my repositories was flagged. I take responsibility for the repository: it was a mistake, not bad faith, and I was not trying to harm anyone. I offered to remove it immediately so it could not affect anyone else.
>
> The offer did not change the outcome. There was no path to remove the repository and keep the account, and the suspension did not distinguish between the flagged repository and the years of unrelated work around it. I lost access to my personal repositories and to the repositories I maintained for the companies I worked with.
>
> I had backups. The code survived; the account, the issues, the reviews and the history did not. Since then my development operation has been entirely local and self-hosted. **[Gitea](https://git.evandro.dev.br/evandro) is the public door** — the canonical place to find my work, follow what I am building, and collaborate on projects I believe in. If you are hiring or evaluating me, the work below is the evidence; the account that no longer exists is not.

## What I do

I build software end to end: understanding the problem, choosing the trade-offs, modeling the data, writing the APIs and the interfaces, testing, deploying and following it in production.

| Area | What it covers |
| --- | --- |
| **Custom systems** | Web applications, mobile apps and internal tools, from discovery to production |
| **Integrations** | REST APIs, third-party services and IoT devices talking to the rest of the stack |
| **Backend engineering** | API design, data modeling, authentication and authorization, automated tests, CI/CD |
| **AI and agents** | MCP servers and agent tooling, local-first and self-hosted |
| **Diagnostics** | Performance, security and maintainability reviews of existing systems |

Five years of software work, with a longer background in hardware and infrastructure. That background helps when a problem leaves the application layer.

## Selected work

> Most of these repositories are private. I can walk you through the code, the trade-offs and the production setup in a call.

### AI and developer tooling

- **PiAgentUI** — desktop and web workspace for AI coding agents: streaming sessions, MCP and skills panels, terminal and file explorer. React 19, TypeScript, Vite, Tauri 2.
- **gemini-nexus** — multi-account gateway for Gemini and Claude exposing OpenAI- and Anthropic-compatible endpoints, with SSE streaming, usage analytics and credentials in the OS keychain. Electron, React 19.
- **orelhIA** — local PT-BR audio transcription MCP server on Parakeet TDT, with LRU cache, VAD, metrics, SSRF protection and automated tests. Python, Docker.
- **latebra** — self-hosted MCP server for private web access, search and extraction, with a three-layer anti-bot pipeline, TLS impersonation, proxy rotation and a pytest suite covering the pipeline, proxy manager and stealth layers. Python.

### Client and product work

- **[SEV Moda Íntima](https://evandro.dev.br/cases/sev-modaintima)** — catalog, storefront and operations panel for a lingerie brand, with products, orders and stock by size. [Live site](https://sevmodaintima.com.br).
- **[Lavação 047](https://evandro.dev.br/cases/lavacao-047)** — site and admin panel for an automotive wash, with WhatsApp ordering and editable prices, text and photos. [Live site](https://landing-page-lavacao047.vercel.app).
- **[AS Serviços](https://evandro.dev.br/cases/as-servicos)** — institutional site for an engineering company, with a procedural Three.js scene that follows the page scroll. Next.js 16, React 19, TypeScript.
- **[SC Plus Aquicultura](https://evandro.dev.br/cases/sc-plus)** — institutional site with areas, projects and contact for an aquaculture company.

Also: **bthaven** (native Windows 11 Bluetooth device and audio hub in C#), **cursorAI_install.sh** (Linux installer for Cursor that chooses AppImage, DEB or RPM from the detected distribution and architecture), and **dev-workflows** (code review workflows shipped as agent skills for frontend, backend, architecture and security).

## Professional work

> Part of my work lives in private repositories. This is the scope, without the code.

- **Apolo Energia** (since 2022): web and mobile applications, APIs and IoT integrations for the company's internal routines and renewable energy operations, including operations dashboards.
- A modular **NestJS platform** (TypeScript, PostgreSQL, Drizzle ORM) split into 8+ isolated domains, with OpenAPI documentation, S3-compatible storage, health checks and automated tests with coverage thresholds of 80% of lines and 70% of branches.
- An **offline-first TypeScript SDK** with auth, sync, media and transaction modules, including retry with backoff, dead-letter handling and SHA-256 deduplication.
- **E-commerce systems** with ACID inventory transactions, separate customer and admin authentication and relevance-ranked product search.
- **Innovo** (December 2024 to February 2025): Angular front-end components and Node.js back-end logic over PostgreSQL and MySQL, internal libraries and maintenance of legacy systems.

## Stack

| Area | Technologies |
| --- | --- |
| Languages | TypeScript, JavaScript, Python, SQL, Bash, C# |
| Backend | Node.js, NestJS, Fastify, Express, REST APIs, OpenAPI, PHP, Laravel |
| Frontend and mobile | React, Next.js, Astro, React Native, Expo, Tailwind CSS |
| Data | PostgreSQL, MySQL, SQLite, MongoDB, Prisma, Drizzle ORM |
| Infrastructure | Docker, Linux, S3-compatible storage, CI/CD, Firebase |
| Quality and security | Jest, Vitest, pytest, Playwright, OAuth2, JWT, RBAC, Zod |

## How I work

- **Own the whole path.** I would rather understand the problem, model the data, write the API and follow it in production than hand off a layer I cannot see.
- **Verify before calling it done.** If I cannot run it, I do not claim it works.
- **Local-first by default.** Local models, local data, self-hosted services and backups I control. Cloud when it earns its place.

## Contact

For backend roles, technical collaborations or conversations about architecture, APIs and reliable systems, use any of these. I work in Portuguese and English.

- **Gitea (canonical):** [git.evandro.dev.br/evandro](https://git.evandro.dev.br/evandro)
- **Portfolio:** [evandro.dev.br](https://evandro.dev.br)
- **LinkedIn:** [linkedin.com/in/evandrodevbr](https://www.linkedin.com/in/evandrodevbr/)
- **Email:** [evandrofonsecajunior@gmail.com](mailto:evandrofonsecajunior@gmail.com)
- **WhatsApp:** [+55 47 99274-2365](https://wa.me/5547992742365)

If you maintain a project you believe in, send me the link. I would rather contribute through Gitea, on infrastructure we can inspect.

*This page is versioned at [evandro/.profile](https://git.evandro.dev.br/evandro/.profile).*
