<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:24283b,100:7aa2f7&height=210&section=header&text=Jo%C3%A3o%20Pedro%20Cardoso&fontSize=44&fontColor=c0caf5&fontAlignY=35&desc=Senior%20Full-Stack%20Developer%20%E2%80%A2%20PHP%20%E2%80%A2%20Laravel%20%E2%80%A2%20Vue%20%E2%80%A2%20Node&descSize=16&descAlignY=55" width="100%" alt="banner"/>

  <p>
    <a href="https://www.linkedin.com/in/eupedrocardoso/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
    <a href="mailto:pedroecomp@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
    </a>
    <a href="https://www.instagram.com/eu.pedrocardoso" target="_blank">
      <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
    </a>
  </p>

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&color=7AA2F7&center=true&vCenter=true&width=600&lines=Building+Metrics+Kit+%26+Startup+Kit;8%2B+years+shipping+PHP%2C+Laravel+%26+Vue;Turning+legacy+systems+into+scalable+platforms" alt="typing"/>
</div>

## 👨‍💻 About Me

Software engineer with **8+ years of experience**, specialized in the **PHP, Laravel and Vue.js** ecosystems. Proven track record in legacy-system modernization, performance optimization and delivering scalable applications. Currently focused on **software architecture** and **high-performance full-stack development**.

- 🌍 **Location:** Conceição do Jacuípe — BA, Brazil (remote)
- 🗣️ **Languages:** Portuguese (native), English (intermediate)
- 💼 **Now:** Full-Stack Developer at **MaxFinance** (Portugal) — rewriting a legacy C# platform in Laravel + Vue
- 📫 **Reach me:** [pedroecomp@gmail.com](mailto:pedroecomp@gmail.com)

---

## 🔨 Featured Projects

### 📊 Metrics Kit

Chart-ready **metrics & trends from your database** through a single fluent TypeScript API. One ORM-agnostic engine with adapters for **TypeORM, Prisma and Drizzle**, running on PostgreSQL, MySQL/MariaDB and SQLite — published on npm with CI, dual CJS/ESM builds and full type declarations.

<p>
  <a href="https://www.npmjs.com/package/nestjs-metrics"><img src="https://img.shields.io/npm/v/nestjs-metrics?style=flat-square&logo=npm" alt="npm"/></a>
  <a href="https://github.com/PedroPCardoso/metrics-kit/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/PedroPCardoso/metrics-kit/ci.yml?style=flat-square&logo=githubactions&logoColor=white" alt="CI"/></a>
  <img src="https://img.shields.io/npm/l/nestjs-metrics?style=flat-square" alt="license"/>
</p>

```ts
this.metrics
  .query(orderRepo.createQueryBuilder('orders'))
  .sumByMonth('amount', 12)
  .fillMissingData()
  .trends();
// → { labels: ['January', ...], data: [1200, ...] }
```

### 🧱 Startup Kit

A **modular backend foundation for SaaS products** in PHP 8.4 / Laravel 12 — clean architecture (DDD + CQRS + ports & adapters), an event bus with transactional outbox, resilient drivers and swappable persistence (Postgres, MySQL, Mongo, in-memory), all contract-tested.

| Module | What it provides |
| --- | --- |
| [`startup-kit-core`](https://github.com/PedroPCardoso/startup-kit-core) | CQRS buses & middleware, event bus + outbox, resilient drivers, tracing, logging, health endpoints |
| [`startup-kit-users`](https://github.com/PedroPCardoso/startup-kit-users) | User registration & management domain |
| [`startup-kit-payments`](https://github.com/PedroPCardoso/startup-kit-payments) | Payment processing with multi-gateway support (Stripe, Mercado Pago) |
| [`startup-kit-orders`](https://github.com/PedroPCardoso/startup-kit-orders) | Order & order-line management domain |
| [`startup-kit-subscriptions`](https://github.com/PedroPCardoso/startup-kit-subscriptions) | Recurring subscription management |
| [`startup-kit-notifications`](https://github.com/PedroPCardoso/startup-kit-notifications) | Multi-channel notifications (SendGrid, Twilio, Telegram) |

### 🚗 OmniAuto

Full-featured **driving-school CRM** — students, instructors, vehicles, scheduling, exams, finance and a pipeline kanban. **Laravel 11 · Vue 3 · Inertia v2 · Tailwind · PostgreSQL · Redis · Docker.**

<div align="center">
  <a href="https://github.com/PedroPCardoso/metrics-kit">
    <img src="https://opengraph.githubassets.com/1/PedroPCardoso/metrics-kit" width="49%" alt="metrics-kit"/>
  </a>
  <a href="https://github.com/PedroPCardoso/OmniAuto">
    <img src="https://opengraph.githubassets.com/1/PedroPCardoso/OmniAuto" width="49%" alt="OmniAuto"/>
  </a>
</div>

---

## 🚀 Tech Stack

<div align="center">

### Backend & Core
<img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
<img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white"/>

### Frontend
<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white"/>
<img src="https://img.shields.io/badge/Ionic-3880FF?style=for-the-badge&logo=ionic&logoColor=white"/>

### Database & Cloud
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white"/>

</div>

---

## 💼 Experience

**MaxFinance** — Full-Stack Developer · *Nov 2023 – present*
Credit intermediation platform in Portugal. Rewriting a legacy C# system in **Laravel + Vue**, building an integrated webmail (Outlook support) and back-office, and setting up CI/CD for continuous deployment.

**Infracommerce** — Full-Stack Developer · *Apr 2022 – Nov 2023*
White-label e-commerce for major brands (Samsung, Nike, Arno). Dynamic cart-pricing features, high-volume query optimization, and codebase standardization with PSRs and design patterns.

**TrackerUp** — Full-Stack Developer · *Aug 2021 – Apr 2022*
Field-team management. Modernized a legacy API to **Laravel** with tests (PHPUnit/Jest) and Swagger; integrated payment gateways and media/ads management systems.

<details>
<summary><b>Earlier roles (2016 – 2021)</b></summary>
<br/>

**Absam** — Full-Stack Developer · *Dec 2019 – Aug 2021*
Cloud computing & deploy automation platform. Elastic Stack integrations, CI automation for GitHub/GitLab, affiliate area and payment integrations (Cielo).

**BenMelhor** — Software Engineer · *Jul 2017 – Nov 2019*
Relationship-management platform. Led **PHP & Laravel** version upgrades, refactored legacy code for performance, and built a gamification/scoring system fed by external data.

**Gerenciagram** — Backend Developer · *Jan 2016 – Dec 2016*
Instagram marketing automation. Automated tasks and TDD with Python and PHP.

</details>

Full history on [LinkedIn](https://www.linkedin.com/in/eupedrocardoso/).

---

## ⚡ GitHub Stats

<div align="center">
  <img src="https://raw.githubusercontent.com/PedroPCardoso/PedroPCardoso/master/profile-summary-card-output/tokyonight/0-profile-details.svg" width="100%" alt="profile details"/>
  <img src="https://raw.githubusercontent.com/PedroPCardoso/PedroPCardoso/master/profile-summary-card-output/tokyonight/3-stats.svg" width="49%" alt="stats"/>
  <img src="https://raw.githubusercontent.com/PedroPCardoso/PedroPCardoso/master/profile-summary-card-output/tokyonight/1-repos-per-language.svg" width="49%" alt="repos per language"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=PedroPCardoso&theme=tokyonight" alt="streak"/>
</div>

<br/>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PedroPCardoso/PedroPCardoso/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/PedroPCardoso/PedroPCardoso/output/github-snake.svg"/>
    <img alt="contribution snake" src="https://raw.githubusercontent.com/PedroPCardoso/PedroPCardoso/output/github-snake.svg"/>
  </picture>
</div>

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=pedropcardoso&style=for-the-badge&color=blueviolet" alt="Profile Views"/>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,50:24283b,100:1a1b27&height=120&section=footer" width="100%" alt="footer"/>
