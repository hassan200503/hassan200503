# Hi, I'm Hassan Tsuma 👋

**Full-stack software engineer, backend-focused — SaaS & systems architecture**

Based in Kenya (UTC+3) · Freelance software engineer since 2023

I build multi-tenant business software where money and data have to stay correct: payments, ledgers, access control, and the tests that prove they work. Recently, I've expanded into AI-powered systems that learn and adapt.

---

## Featured Projects

### 🤖 Companion AI

A voice-first, intelligent Windows desktop companion with autonomous capabilities. Built with Electron, TypeScript, and advanced AI integration.

**[Download →](https://github.com/hassan200503/personal-companion-bot/releases/tag/v0.1.0)** · **[Source →](https://github.com/hassan200503/personal-companion-bot)**

| Repo | What it is |
|---|---|
| [personal-companion-bot](https://github.com/hassan200503/personal-companion-bot) | Electron 45 / React 19 / TypeScript: Voice-first AI companion with autonomous capabilities |

**Key features:**
- Voice-first interaction with real-time transcription using Gemini AI
- Autonomous goal pursuit with risk-based approval workflows
- Financial management with multi-layer safeguards
- Learning engine that adapts to user behavior patterns
- Enterprise security with SQLCipher encryption and credential management
- 439+ automated tests, 0 type errors

---

### 🏠 RentManager

A property and rental management SaaS built for the Kenyan market, with M-Pesa (STK Push) rent collection.

**[Live demo →](https://www.rentmanagerke.workers.dev)** · **[Case study →](https://hassan200503.github.io/work/rentmanager.html)**

| Repo | What it is |
|---|---|
| [rentmanager-backend](https://github.com/hassan200503/rentmanager-backend) | Java 21 / Spring Boot 3 API: 20+ modules, PostgreSQL, Flyway |
| [rentmanager-frontend](https://github.com/hassan200503/rentmanager-frontend) | Next.js 16 / React 19 / TypeScript web app, deployed on Cloudflare Workers |
| [rentmanager-mobile](https://github.com/hassan200503/rentmanager-mobile) | Expo / React Native app, 27 screens |

**Engineering decisions I'm proud of**

- **Modular monolith, on purpose.** 20+ modules in one deployable, with no microservices, message broker, Kafka or Redis, because the problem doesn't need them yet.
- **Tenant isolation from verified identity.** The tenant is derived from a verified Clerk JWT and enforced again at repository level.
- **Append-only financial ledger**, enforced by a PostgreSQL trigger so history can't be quietly rewritten.
- **Idempotent M-Pesa STK Push:** a repeated request within a 3-minute window returns the existing pending payment instead of sending a second one (ADR-0016).
- **Pessimistic locking on disbursements** to prevent concurrent double payouts (ADR-0018).
- **Per-landlord encrypted M-Pesa credentials.** The platform never takes custody of funds.
- **1,500+ automated backend tests** (using Testcontainers), 90+ Flyway migrations, and key decisions recorded as ADRs.

**Status, stated plainly:** deployed demo, with M-Pesa running against the Safaricom sandbox. It is not commercially live yet, and it runs on free-tier hosting, so the first load can be slow.

---

## Stack

- **Backend:** Java 21, Spring Boot 3, PostgreSQL, Flyway, Testcontainers, REST APIs, Node.js, TypeScript
- **Frontend:** Next.js 16, React 19, TypeScript, React Query, Vite
- **Mobile:** Expo / React Native
- **Desktop:** Electron 45, Windows native APIs (WinRT)
- **AI/ML:** LLM integration (Gemini, Claude, OpenRouter), voice recognition, pattern recognition, autonomous systems
- **Payments:** M-Pesa Daraja (STK Push, callbacks, idempotency), PayPal API
- **Security:** SQLCipher encryption, Windows Credential Manager, risk-based rate limiting
- **Auth:** Clerk (JWT verification)
- **Infra & tooling:** GitHub Actions, Cloudflare Workers, Render, Neon, Git, Electron Builder

---

## Currently

- Enhancing Companion AI's autonomous capabilities and voice interaction features
- Polishing RentManager and writing up its deployment story
- Exploring AI-powered business automation and intelligent assistants
- Looking for junior / entry-level backend or full-stack roles (remote or Kenya-based) and freelance work on payments, SaaS backends, and AI-powered systems

---

## Get in touch

📧 karungwahassan03@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/hassan-karungwa) · 🌐 [Portfolio](https://hassan200503.github.io)
