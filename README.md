# Subscription Management API

Build and deploy a **production-ready Subscription Management System** that handles real users, real money, and real business logic.  
This project follows the step-by-step **Backend Crash-Course** from *JavaScript Mastery* on YouTube. :contentReference[oaicite:0]{index=0}

---

## ✨ Features

| Area | Highlights |
|------|------------|
| **Auth & Security** | JWT authentication, role-based access, bcrypt password hashing, rate-limiting & bot-protection (Arcjet) |
| **Subscriptions** | CRUD for plans, pricing, and active user subscriptions + Stripe webhooks for billing events |
| **Users** | Self-service account endpoints, profile management, password reset e-mails |
| **Data Layer** | MongoDB + Mongoose models, schema validation, transaction-safe updates |
| **Productivity** | Centralised error-handler, request/response logging, typed config loader, nodemon dev server |
| **Automation** | GitHub Actions CI, Prettier + ESLint, Husky commit hooks |
| **Workflows** | Upstash QStash for scheduled tasks and e-mail reminders |

*(Feature list adapted from the official course repo) :contentReference[oaicite:1]{index=1}*

---

## ⚙️ Tech Stack

- **Node.js 20 LTS** & **Express 5**
- **MongoDB Atlas** + **Mongoose**
- **Stripe API** for payments
- **Arcjet**, **Upstash QStash**
- **Docker** (optional) for local Postgres/Mongo containers
- **GitHub Actions** for CI/CD
