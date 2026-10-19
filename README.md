<div align="center">

# Aleksandr Piletskii

**Senior Fullstack QA Engineer** · Test automation & test infrastructure · TypeScript / Playwright

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aleksandrpiletskii/)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/aleksandrpiletskii)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:aleksandrpiletskii@gmail.com)

</div>

---

### 👋 About

I own test automation for a web analytics platform with marketplace integrations at **[TrueStats](https://truestats.ru/)**: the e2e framework, the infrastructure it runs on, and the coverage strategy behind it.

Most of my work sits in test infrastructure: deterministic stubs for external APIs, parallel runs, CI/CD and observability. I work across repos, adding `data-testid`s to the React/TS frontend and agreeing stub contracts with backend, so a run behaves the same locally and in CI.

### ⚡ Recent work

- **2000+ e2e tests** in the full run, covering the key product areas; part of the manual regression now runs automatically before every release
- **Framework architecture:** rewrote a large part of the codebase and unified the Page Object / Component Object layers
- **Reusable component library:** filters, tables, date pickers, modals, exports; a typical scenario is assembled from ready blocks, not written from scratch
- **Flake-free runs:** extended the stub layer isolating e2e from CloudPayments, Wildberries, Ozon and GrowthBook; fixed cursor pagination, date-window drift and fixture expiry
- **Honest coverage:** code tag ↔ TMS case mapping with regular audits, plus mutation checks: inject a defect into a calculation and make sure the run fails
- **CI:** nightly and pre-release runs in GitLab CI; now designing parallel execution on user pools and layered fixtures to cut the full run from hours to minutes

### 🧭 How I think about tests

> A green test that checks nothing is worse than no test.
> Coverage counts only what is actually asserted.
> A flaky run is an infrastructure bug, not bad luck.

### 🛠 Stack

| | |
|---|---|
| **Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=databricks&logoColor=white) |
| **Testing** | ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black) ![TestIT](https://img.shields.io/badge/TestIT-1F6FEB?style=flat-square) ![Allure](https://img.shields.io/badge/Allure_Report-FF6F00?style=flat-square) |
| **CI/CD & Infra** | ![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black) |
| **Observability** | ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![SigNoz](https://img.shields.io/badge/SigNoz-E75536?style=flat-square) |
| **AI** | ![MCP](https://img.shields.io/badge/MCP_%2F_AI_tools-191919?style=flat-square) |

---

<div align="center">
<sub>🌍 Remote · English C1 · Open to a good conversation about testing</sub>
</div>
