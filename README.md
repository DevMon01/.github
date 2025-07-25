# 👋 Welcome to DevMon

**DevMon** (short for *DevOps Monitor*) is an open-source platform designed to give DevOps, SRE, and Platform teams a real-time, unified view of the operational status of all critical developer tools — such as GitHub, Jenkins, DockerHub, Azure DevOps, and more.

No more checking multiple status pages manually. DevMon centralizes, normalizes, and alerts you when your tools have incidents — so you can focus on building.

---

## 🚀 What We're Building

| Feature                            | Description |
|------------------------------------|-------------|
| 🔄 **Status Polling**              | Real-time aggregation from public APIs, RSS feeds, and HTML scrapers |
| 📊 **Unified Dashboard**           | Web-based UI showing current tool status and incident history |
| 🔔 **Alerts & Notifications**      | Slack, Email, Webhook alerts when outages occur |
| 🕒 **Historical Insights**         | Track past incidents and tool uptime trends |
| 🛠️ **Admin UI**                    | Manage tool integrations and polling intervals easily |
| 🧩 **Pluggable Architecture**      | Easily add support for new tools and integrations |
| 🌐 **Open Source & Self-Hostable** | Fully containerized, bring-your-own-infra ready |

---

## 🧱 Microservices Architecture

DevMon is built using Spring Boot, Docker, MongoDB, and MySQL, and follows Domain-Driven Design (DDD) and OOP principles. Services are decoupled and scalable using a Microservice Design Architecture.

| Microservice           | Role |
|------------------------|------|
| `status-collector`     | Polls external tools and normalizes data |
| `notification-service` | Sends alerts to subscribed channels |
| `incident-log`         | Stores and exposes historical incident data |
| `admin-config`         | Administers tool configs and schedules |
| `dashboard-api`        | API gateway for the frontend interface |

---

## 🐳 Tech Stack

- 🧠 **Backend**: Java, Spring Boot
- 🎨 **Frontend**: React + Next.js
- 🗃️ **Databases**: MongoDB (status), MySQL (logs/configs)
- 📦 **Containerization**: Docker, Docker Compose
- 🔎 **Monitoring**: Prometheus + Grafana (planned)
- 🔔 **Alerts**: Slack API, Email (SendGrid/Mailgun), Webhooks

---

## 👥 Who is DevMon For?

- **DevOps Teams** needing fast insights into tool availability.
- **SREs** wanting to filter low-noise and respond to critical outages.
- **Platform Engineers** building internal observability tools.
- **Open-source contributors** interested in real-world microservices.

---

## 📅 Project Status

DevMon is in **active development** and is approaching MVP milestones. You can follow our progress on the [roadmap](https://github.com/orgs/DevMon01/projects).

---

## 🌐 Links

- 📘 [Project Overview Wiki](https://github.com/DevMon01/wiki)
- 🧠 [Architecture Diagrams](https://github.com/DevMon01/assets)
- 🛠️ [Microservice Repos](https://github.com/orgs/DevMon01/repositories)
- ✉️ Contact: [ongeziwejunior6@gmail.com](mailto:ongeziwejunior6@gmail.com)

---

> Made with ❤️ by DevMon. Making DevOps status monitoring effortless.
