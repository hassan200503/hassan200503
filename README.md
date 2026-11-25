<!-- Hero -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg">
  <img src="./assets/hero-dark.svg" width="100%" alt="Hassan Tsuma â€” Full-Stack Software Engineer">
</picture>

<br/>
<hr/>
<br/>

## About Me

**Hassan Tsuma Karungwa** â€” full-stack software engineer with 3+ years of freelance experience (since 2023). Based in Kenya (UTC+3), available immediately for remote work in any timezone, and willing to relocate for the right role.

I build **multi-tenant business software where money and data have to stay correct** â€” payments, ledgers, access control, and the tests that prove they work.

My flagship project, **RentManager**, is a live SaaS with **20 backend modules, 100+ database migrations, and ~1,600 automated tests**.

My second, **Automata**, is a **voice-first Windows AI assistant with 46 OS-level tools and multi-model ensemble reasoning** across 8+ AI providers.

I gravitate toward problems where **correctness matters more than speed**: money, records, and things businesses can't afford to get wrong.

I'm honest about where I'm still growing â€” running systems under real production load and distributed systems â€” which is why RentManager is a **modular monolith on purpose**, not premature microservices.

### Engineering Principles

> **Money is append-only** â€” never edited or deleted; corrections are new linked entries
>
> **Don't reach for distributed complexity you don't need** â€” modular monolith with DB-backed outbox
>
> **Fail closed on anything legal or financial** â€” tax module defaults off until a human confirms
>
> **The schema is a historical record, not a draft** â€” 100 sequential migrations, never edited after running
>
> **If it isn't tested, assume it's broken** â€” ~2,400+ tests across all projects

**My process:** Understand the problem â†’ Map the domain â†’ Design architecture & write down trade-offs â†’ Build in focused, tested increments â†’ Test money paths first â†’ Ship, then say what's still open

<br/>
<hr/>
<br/>

## GitHub in Numbers

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=hassan200503&show_icons=true&theme=github_dark&hide_border=true&count_private=true&title_color=1f6feb&icon_color=238636&text_color=c9d1d9&bg_color=0d1117" height="170" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hassan200503&layout=compact&theme=github_dark&hide_border=true&title_color=1f6feb&text_color=c9d1d9&bg_color=0d1117&langs_count=10" height="170" alt="Top languages" />

</div>

<br/>
<hr/>
<br/>

## Skills & Tech Stack

### Backend Engineering

<table>
<tr>
<td align="left" valign="top" width="180"><strong>Core</strong></td>
<td><code>Java 21</code> Â· <code>Spring Boot 3</code> Â· <code>Spring Security</code> Â· <code>Node.js</code> Â· <code>TypeScript</code> Â· <code>REST / OpenAPI</code> Â· <code>JWT / JWKS</code></td>
</tr>
<tr>
<td align="left" valign="top"><strong>Architecture</strong></td>
<td>Hexagonal (ports & adapters) Â· Domain-Driven Design Â· Clean Architecture Â· Modular monolith Â· Transactional outbox Â· SOLID Â· Object-oriented design</td>
</tr>
</table>

<br/>

### Data & Persistence

<table>
<tr>
<td align="left" valign="top" width="180"><strong>Core</strong></td>
<td><code>PostgreSQL 16</code> Â· <code>Flyway</code> Â· <code>JPA / Hibernate</code> Â· <code>Drizzle ORM</code> Â· <code>PGlite</code> Â· <code>Neon</code></td>
</tr>
<tr>
<td align="left" valign="top"><strong>Data engineering</strong></td>
<td>Schema & constraint design Â· Append-only ledger patterns Â· Idempotency keys Â· Database triggers Â· Pessimistic locking Â· Keyset pagination Â· Transactional integrity</td>
</tr>
</table>

<br/>

### Frontend & Mobile

<table>
<tr>
<td align="left" valign="top" width="180"><strong>Core</strong></td>
<td><code>React 19</code> Â· <code>Next.js 16</code> Â· <code>TypeScript</code> Â· <code>TanStack Query</code> Â· <code>Vite</code> Â· <code>TailwindCSS</code> Â· <code>React Native 0.86</code> Â· <code>Expo 57</code></td>
</tr>
</table>

<br/>

### AI, ML & LLMs

<table>
<tr>
<td align="left" valign="top" width="180"><strong>Providers</strong></td>
<td><code>Gemini</code> Â· <code>Claude / Anthropic</code> Â· <code>OpenAI</code> Â· <code>OpenRouter</code> Â· <code>Groq</code> Â· <code>DeepSeek</code> Â· <code>NVIDIA</code> Â· <code>Perplexity</code></td>
</tr>
<tr>
<td align="left" valign="top"><strong>Capabilities</strong></td>
<td>Multi-model ensemble reasoning Â· LLM integration Â· Voice recognition & speech synthesis Â· Autonomous systems Â· Prompt engineering (layered L0â€“L7 compilation) Â· Circuit breakers & failover Â· Speaker verification Â· Learning engines</td>
</tr>
</table>

<br/>

### Payments & Integrations

<table>
<tr>
<td align="left" valign="top" width="180"><strong>Providers</strong></td>
<td><code>M-Pesa Daraja</code> Â· <code>PayPal</code> Â· <code>Clerk</code> Â· <code>Africa's Talking</code> Â· <code>Cloudinary</code> Â· <code>WebRTC</code></td>
</tr>
<tr>
<td align="left" valign="top"><strong>Payment engineering</strong></td>
<td>STK Push Â· B2C payouts Â· Callback handling Â· Idempotency Â· Reconciliation jobs Â· Per-tenant encrypted credentials Â· AES-GCM encryption</td>
</tr>
</table>

<br/>

### Security

<table>
<tr>
<td align="left" valign="top" width="180"><strong>Tools</strong></td>
<td><code>SQLCipher</code> Â· <code>Windows Credential Manager</code> Â· <code>OAuth2</code> Â· <code>JWT</code> Â· <code>RBAC</code> Â· <code>DPAPI</code> Â· <code>Semgrep</code> Â· <code>gitleaks</code></td>
</tr>
<tr>
<td align="left" valign="top"><strong>Security engineering</strong></td>
<td>Risk-classified policy engine (Class 1â€“4) Â· Rate limiting (sliding window) Â· Tenant isolation Â· Audit trails Â· Untrusted content boundaries Â· Dependency audit policies</td>
</tr>
</table>

<br/>

### Desktop & OS

<table>
<tr>
<td align="left" valign="top" width="180"><strong>Core</strong></td>
<td><code>Electron 45</code> Â· <code>Win32 APIs</code> Â· <code>WinRT</code> Â· <code>PowerShell</code> Â· <code>UI Automation</code> Â· <code>electron-builder</code></td>
</tr>
</table>

<br/>

### Testing & Delivery

<table>
<tr>
<td align="left" valign="top" width="180"><strong>Core</strong></td>
<td><code>JUnit 5</code> Â· <code>Testcontainers</code> Â· <code>Mockito</code> Â· <code>ArchUnit</code> Â· <code>Vitest 5</code> Â· <code>Jest</code> Â· <code>Docker</code> Â· <code>GitHub Actions</code> Â· <code>Maven</code> Â· <code>Turborepo</code></td>
</tr>
</table>

<br/>

### Infrastructure & Hosting

<table>
<tr>
<td align="left" valign="top" width="180"><strong>Core</strong></td>
<td><code>Cloudflare Workers</code> Â· <code>Render</code> Â· <code>Neon</code> Â· <code>Vercel</code> Â· <code>Prometheus</code> Â· <code>Sentry</code></td>
</tr>
<tr>
<td align="left" valign="top"><strong>Ops</strong></td>
<td>Actuator health probes Â· Graceful shutdown Â· CI/CD pipelines Â· `render.yaml` blueprints Â· EAS Build Â· Lighthouse 95+</td>
</tr>
</table>

<br/>

### Tooling & Workflow

<table>
<tr>
<td align="left" valign="top" width="180"><strong>Core</strong></td>
<td><code>Git</code> Â· <code>GitHub</code> Â· <code>MapStruct</code> Â· <code>Springdoc OpenAPI</code> Â· <code>Swagger UI</code> Â· <code>gitleaks</code></td>
</tr>
<tr>
<td align="left" valign="top"><strong>Practices</strong></td>
<td>ADRs for key decisions Â· Hexagonal architecture enforced via ArchUnit Â· Convention over configuration Â· Contract-first API design Â· Separation of concerns (`api â†’ application â†’ domain â†’ infrastructure`) Â· Zero type/lint errors as a gate</td>
</tr>
</table>

<br/>
<hr/>
<br/>

## Featured Projects

### RentManager â€” Multi-tenant Rental SaaS for Kenya

> **20 modules Â· 100+ migrations Â· ~1,600 tests Â· M-Pesa Daraja STK Push**
>
> Property management for Kenya: rent collection, digital leases, real-time analytics.
> Three surfaces shipped: web (63 routes), mobile (27 screens), API (20 modules).

**[Backend](https://github.com/hassan200503/rentmanager-backend)** Â· **[Frontend â€” Live Demo](https://www.rentmanagerke.workers.dev)** Â· **[Mobile](https://github.com/hassan200503/rentmanager-mobile)**

<details>
<summary><b>Full project breakdown & engineering decisions</b></summary>

**Product scope:** 20 domain modules â€” property, leasing, rent ledger, deposits, maintenance, subscriptions, reviews, tax, platform administration

**Surfaces shipped:**

| Surface | Scope | Stack |
|---|---|---|
| **Web** | 63 routes â€” landlord dashboard, tenant portal, public listings, admin console | Next.js 16, React 19, TanStack Query |
| **Mobile** | 27 screens â€” push notifications, offline detection, secure token storage, crash reporting | Expo 57, React Native 0.86, Expo Router |
| **API** | 20 modules behind one contract â€” tenant isolation via verified token | Java 21, Spring Boot 3, PostgreSQL 16 |

**Engineering decisions I'm proud of:**

- **Modular monolith, on purpose.** 20 modules in one deployable, with no microservices, message broker, Kafka or Redis, because the problem doesn't need them yet.
- **Tenant isolation from verified identity.** The tenant is derived from a verified Clerk JWT and enforced again at repository level.
- **Append-only financial ledger**, enforced by a PostgreSQL trigger so history can't be quietly rewritten.
- **Idempotent M-Pesa STK Push:** a repeated request within a 3-minute window returns the existing pending payment instead of sending a second one (ADR-0016).
- **Pessimistic locking on disbursements** to prevent concurrent double payouts (ADR-0018).
- **Per-landlord encrypted M-Pesa credentials.** The platform never takes custody of funds.
- **Transactional outbox pattern** â€” durable retry path without a message broker, with a clear future migration path.
- **Provider capability is optional, not silently mocked** â€” integrations fail closed when required credentials are absent.

**Test evidence:** ~1,600 backend tests (JUnit 5, Testcontainers, ArchUnit) Â· 100+ Flyway migrations Â· Key decisions recorded as ADRs

**Status, stated plainly:** deployed demo, with M-Pesa running against the Safaricom sandbox. Not commercially live yet. Runs on free-tier hosting, so the first load can be slow.

</details>

<br/>
<hr/>
<br/>

### Automata â€” Voice-First Windows AI Assistant

> **46 OS-level tools Â· 8+ AI providers Â· ensemble reasoning Â· 539 tests Â· 26,600 lines**
>
> A Windows-first, voice-first personal AI companion. Speak or type; it runs real OS actions
> and is honest about what it did. Only claims an action succeeded when the result was actually observed.

**[Download Release](https://github.com/hassan200503/automata/releases)** Â· **[Source](https://github.com/hassan200503/automata)**

**Core capabilities:**

- **46 typed, risk-classified tools** â€” system control, window management, text input, file ops, media capture, communication, web & email
- **Multi-model ensemble reasoning** â€” fans out to 8+ AI providers, scores each answer, keeps the strongest
- **Voice-first by default** â€” speech-to-text + text-to-speech with real-time transcription
- **Learning engine** â€” episode logging, pattern consolidation, recipe learning, weekly review
- **Enterprise-grade safety** â€” risk classes 1â€“4, rate limits, audit trail, global emergency stop (`Ctrl+Shift+Esc`)

**Security & privacy:**

- SQLCipher-encrypted storage with DPAPI-wrapped keys
- Windows Credential Manager for API keys â€” never hardcoded, never logged
- Untrusted content boundary â€” web/email text tagged and sanitized
- Per-action confirmation flows based on risk class

| Metric | Value |
|---|---|
| Source | ~26,600 lines, 154 files |
| Tests | 539 passing |
| Type errors | 0 |
| Lint errors | 0 |
| OS tools | 46 |
| AI providers | 8 + ensemble |

<details>
<summary><b>Full feature breakdown</b></summary>

**OS Control (37 OS tools + 9 Web/Email/Memory = 46 total):**

| Category | Example Commands |
|---|---|
| System | "set volume to 50", "next track", "lock screen", "restart in 2 minutes" |
| Windows | "close notepad", "switch to chrome", "move the window to 100,100" |
| Text input | "type hello world", "press ctrl+c", "read clipboard" |
| Files | "search for *.pdf", "copy report.txt to backup", "create folder Reports" |
| Media & capture | "play Bohemian Rhapsody", "read that aloud", "take a screenshot" |
| Communication | "call John on WhatsApp", "message Sarah hello" |
| Web & email | "read example.com aloud", "read my important email" |
| Memory | "what did I say about the budget?" |

**Multi-Model Reasoning:** Gemini, OpenRouter, Groq, NVIDIA, DeepSeek, OpenAI, Anthropic, Perplexity + custom OpenAI-compatible endpoints. Ensemble mode with circuit breakers, quota tracking, retries, automatic provider switching, streaming, and full audit logging.

**Cognition:** Layered prompt compilation (L0â€“L7): safety â†’ persona â†’ context â†’ memory â†’ tools â†’ style â†’ policy â†’ output. Decision orchestrator + style normalizer + response cache (100 entries, 5-min TTL, LRU).

</details>

<br/>
<hr/>
<br/>

### Lovora â€” Private Shared World for Two

> **302 tests Â· tested sync protocol Â· WebRTC calls Â· realtime chat**
>
> A couples app: realtime chat, encrypted calls, synchronised watch/listen rooms,
> memories and live discoveries. Next.js + TypeScript, PGlite/Postgres.

**[Live](https://lovora-app.vercel.app)** Â· **[Source](https://github.com/hassan200503/Lovora)**

**Features:**
- Realtime chat â€” typing, delivery/read receipts, reactions, edits, voice notes
- Encrypted 1:1 WebRTC calls with ICE restart & web-push alerts
- Together room â€” shared queue, clock estimation, drift correction
- Shared gallery â€” signed reads, EXIF stripping, media validation
- Discovery browser â€” RSS/Atom, iNaturalist, curated source cards
- AI research â€” OpenAlex study search + Gemini-assisted lessons

**Engineering highlights:**
- Framework-free sync protocol with deterministic virtual-time tests (clock skew, latency, jitter, packet loss)
- Couple-owned data scoped by <code>couple_id</code> â€” request input never decides tenant
- bcrypt(12), signed httpOnly JWTs, session versioning for revocation
- Single-use hashed invitations, expire 7 days, consumed transactionally
- GitHub Actions CI with gitleaks + Semgrep SARIF

<br/>
<hr/>
<br/>

## All Public Repositories

| Repository | Description | Primary Language | License |
|---|---|---|---|
| [rentmanager-backend](https://github.com/hassan200503/rentmanager-backend) | RentManager API: rental management for Kenyan landlords and renters. Spring Boot 3, Java 21, PostgreSQL, M-Pesa Daraja, Clerk auth, multi-tenant. 20 modules, 100+ Flyway migrations, ~1,600 tests. | Java | â€” |
| [rentmanager-frontend](https://github.com/hassan200503/rentmanager-frontend) | Kenya's trusted rental platform \| Full-stack Property Management SaaS with M-Pesa integration, digital leases, real-time analytics, and automated rent collection. 63 routes, deployed on Cloudflare Workers. | TypeScript | MIT |
| [rentmanager-mobile](https://github.com/hassan200503/rentmanager-mobile) | RentManager mobile app for landlords and renters in Kenya. Expo 57, React Native 0.86, TypeScript. 27 screens, M-Pesa STK Push, push notifications, offline detection. | TypeScript | MIT |
| [automata](https://github.com/hassan200503/automata) | Windows-first, voice-first personal AI companion. 46 OS-level tools, multi-model ensemble reasoning (8+ providers), SQLCipher encryption, 539 tests, 26.6k lines. | TypeScript | MIT |
| [Lovora](https://github.com/hassan200503/Lovora) | A private shared world for two: realtime chat, encrypted WebRTC calls, synchronised watch/listen rooms, memories and live discoveries. Tested sync protocol, 302 tests. | TypeScript | â€” |
| [personal-companion-bot](https://github.com/hassan200503/personal-companion-bot) | Voice-first AI companion (now evolved into Automata). Electron 45, React 19, TypeScript, autonomous capabilities. | TypeScript | â€” |
| [hassan200503](https://github.com/hassan200503/hassan200503) | This profile README â€” personal information and portfolio. | Markdown | â€” |

<br/>
<hr/>
<br/>

## What I'm Looking For

| Role type | Details |
|---|---|
| **Full-time** | Junior / entry-level backend or full-stack roles â€” remote or Kenya-based |
| **Freelance & contract** | SaaS products, business workflow systems, backend/API work, M-Pesa integrations, AI-powered systems |
| **Open source** | Want to work alongside more experienced engineers. Code review is valued more than pay right now. |

**Where:** Remote (any timezone) Â· On-site in Kenya Â· Willing to relocate for the right role

**Timezone overlap:** UTC+3 â€” 1â€“2 hours ahead of CET, same morning window as EET, and a natural 4-hour overlap with US East Coast afternoons.

<br/>
<hr/>
<br/>

## Currently

- **Automata** â€” enhancing autonomous capabilities, voice interaction, and plugin system
- **RentManager** â€” polishing deployment story and preparing for commercial launch
- **AI exploration** â€” building intelligent business automation and voice-first assistants
- **Open to** junior / entry-level backend or full-stack roles (remote or Kenya-based) and freelance work on payments, SaaS backends, and AI-powered systems

<br/>
<hr/>
<br/>

## Let's Talk

<div align="center">

<a href="mailto:karungwahassan03@gmail.com">
<img src="https://img.shields.io/badge/Email-karungwahassan03@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
<a href="https://wa.me/254714931575">
<img src="https://img.shields.io/badge/WhatsApp-+254%20714%20931%20575-25D366?style=flat-square&logo=whatsapp&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/hassan-karungwa">
<img src="https://img.shields.io/badge/LinkedIn-Hassan%20Karungwa-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="https://hassan200503.github.io/">
<img src="https://img.shields.io/badge/Portfolio-hassan200503.github.io-000000?style=flat-square&logo=vercel&logoColor=white" /></a>

<br/><br/>

**Fastest response:** WhatsApp (+254 714 931 575) â€” replies same day Â· **Better for longer messages:** Email

</div>

<br/>
<hr/>

<div align="center">

*"I'm building depth through increasingly complex systems, not claiming expertise I haven't earned yet."*

</div>
