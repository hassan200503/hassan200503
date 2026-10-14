# Hi, I'm Hassan Tsuma 👋

**Full-stack software engineer, backend-focused — SaaS & systems architecture**

Based in Kenya (UTC+3) · Freelance software engineer since 2023 · BSc Computer Science, Tom Mboya University (expected 2028)

I build multi-tenant business software where money and data have to stay correct: payments, ledgers, access control, and the tests that prove they work.

---

## Featured project: RentManager

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

- **Backend:** Java 21, Spring Boot 3, PostgreSQL, Flyway, Testcontainers, REST APIs
- **Frontend:** Next.js 16, React 19, TypeScript, React Query
- **Mobile:** Expo / React Native
- **Payments:** M-Pesa Daraja (STK Push, callbacks, idempotency)
- **Auth:** Clerk (JWT verification)
- **Infra & tooling:** GitHub Actions, Cloudflare Workers, Render, Neon, Git

---

## Currently

- Polishing RentManager and writing up its deployment story
- Looking for junior / entry-level backend or full-stack roles (remote or Kenya-based) and freelance work on payments and SaaS backends

## Get in touch

📧 karungwahassan03@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/hassan-karungwa) · 🌐 [Portfolio](https://hassan200503.github.io)
