<div align="center">

# Oleksandr Stepanov

### AI Automation · Backend Development · Full-Stack

Building practical systems with AI, APIs, databases and automation.

<br>

<img src="https://img.shields.io/badge/n8n-Automation-FF6D5A?style=for-the-badge&logo=n8n&logoColor=white">
<img src="https://img.shields.io/badge/OpenAI-AI-412991?style=for-the-badge&logo=openai&logoColor=white">
<img src="https://img.shields.io/badge/PostgreSQL-Database-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/.NET-Backend-512BD4?style=for-the-badge&logo=dotnet&logoColor=white">
<img src="https://img.shields.io/badge/Next.js-Full--Stack-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">

<br><br>

**AI Automation** · **REST APIs** · **PostgreSQL** · **n8n** · **OpenAI** · **Next.js** · **ASP.NET Core**

<br>

[![GitHub](https://img.shields.io/badge/GitHub-DayDreamingg--g-181717?style=flat-square&logo=github)](https://github.com/DayDreamingg-g)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-daydreamingg-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/daydreamingg)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:oleksandr.stepanov.tech@gmail.com)

<br>

### ⚡ Quick Navigation

[About Me](#-about-me) ·
[AI Automation](#-ai--automation) ·
[Full-Stack](#-full-stack-development) ·
[Cybersecurity](#-cybersecurity) ·
[Tech Stack](#️-tech-stack) ·
[Current Focus](#-current-focus) ·
[Contact](#-contact)

<br>

### 🚀 Quick Project Links

[AI Customer Support](https://github.com/DayDreamingg-g/AI-Customer-Support-Automation) ·
[AI Lead Automation](https://github.com/DayDreamingg-g/n8n-ai-lead-automation) ·
[Telegram AI Generator](https://github.com/DayDreamingg-g/n8n-telegram-ai-script-generator) ·
[Beauty Booking](https://beauty-booking-site.vercel.app/) ·
[MiniBank API](https://github.com/DayDreamingg-g/MiniBank-Ledger-API) ·
[CyberLab](https://github.com/DayDreamingg-g/CyberLab)

</div>

---

# 👋 About Me

I'm a Computer Science student from Ukraine focused on **AI automation, backend development, and practical software engineering**.

I build projects that go beyond tutorial examples — from AI-powered automation workflows and backend APIs to full-stack web applications that connect external services, databases, messaging platforms, and AI models.

- 🤖 **AI & Automation:** n8n, OpenAI, AI Agents, LLM workflows
- 💻 **Full-Stack:** React, Next.js, TypeScript, JavaScript
- ⚙️ **Backend:** ASP.NET Core, REST APIs, CQRS, MediatR
- 🗄️ **Data:** PostgreSQL, SQLite, SQL, Prisma, Entity Framework Core
- 🔗 **Integrations:** Telegram Bot API, Google Sheets, OAuth 2.0, Webhooks
- 🛠️ **Tools:** Git, GitHub, GitHub Actions, Docker, Linux, Vercel
- 🔐 **Additional interest:** Cybersecurity & Application Security
- 🌍 **Languages:** Ukrainian, Russian, English (B1)
- 💼 **Open to:** Remote Junior Developer, AI Automation, and Internship opportunities

---

# 🚀 Featured Projects

## 🤖 AI & Automation

### 🎧 AI Customer Support Automation

**n8n · OpenAI · PostgreSQL · SQL · REST API · Webhooks**

AI-powered customer support automation that receives support tickets through an authenticated webhook and automatically processes them using AI.

The workflow validates and stores incoming tickets, generates dynamic tags, determines priority, creates a concise support summary, and marks completed tickets as processed.

```text
Support Ticket
      ↓
Authenticated Webhook
      ↓
Validation
      ↓
PostgreSQL
      ↓
AI Tag Generation
      ↓
Store Tags
      ↓
AI Priority Classification
      ↓
AI Summary Generation
      ↓
Mark as Processed
```

**Key features:**

- Authenticated REST webhook
- Input validation
- PostgreSQL ticket persistence
- Dynamic AI-generated tags
- Structured LLM outputs
- AI-based priority classification
- AI-generated ticket summaries
- Relational ticket/tag storage
- Automatic processing status updates
- Multi-step n8n workflow orchestration

➡️ **[View Repository](https://github.com/DayDreamingg-g/AI-Customer-Support-Automation)**

---

### 🔥 AI Lead Qualification Automation

**n8n · OpenAI · Google Sheets · Telegram · OAuth 2.0**

Automated lead qualification workflow that receives new leads from Google Forms, scores them based on **budget and urgency**, classifies them as **Cold / Warm / Hot**, analyzes the client's request with AI, stores the processed result, and sends priority Telegram alerts.

```text
Google Form
      ↓
Google Sheets
      ↓
Budget Scoring
      ↓
Urgency Scoring
      ↓
Total Score
      ↓
Cold / Warm / Hot
      ↓
OpenAI Analysis
      ↓
Processed Leads
      ↓
Telegram Alerts
```

**Key features:**

- Event-driven lead processing
- Budget and urgency scoring
- Cold / Warm / Hot classification
- Multi-branch workflow routing
- AI-generated request summaries
- AI-generated categories and recommended actions
- Google Sheets integration through OAuth 2.0
- Data normalization
- Processed lead storage
- Hot and Warm Telegram notifications

➡️ **[View Repository](https://github.com/DayDreamingg-g/n8n-ai-lead-automation)**

---

### 🎬 Telegram AI Script Generator

**n8n · OpenAI · Telegram Bot API · AI Agent**

AI-powered Telegram bot that generates structured short-form video scripts from user topics and stores generation history.

The workflow implements bot command routing, persistent per-chat history, aggregation, fallback handling, and automatic response delivery.

```text
Telegram Message
      ↓
Command Detection
      ↓
      ├── /start
      ├── /help
      ├── /history
      └── Regular Message
              ↓
          OpenAI Agent
              ↓
          Save History
              ↓
        Telegram Response
```

**Key features:**

- AI-powered script generation
- Telegram event trigger
- OpenAI integration
- Command detection and routing
- `/start`, `/help`, `/history`
- Persistent generation history
- History filtering and aggregation
- Unknown-command fallback
- Automatic Telegram responses

➡️ **[View Repository](https://github.com/DayDreamingg-g/n8n-telegram-ai-script-generator)**

---

## 🌐 Full-Stack Development

### 💇 Beauty Booking Platform

**Next.js · React · TypeScript · Tailwind CSS · Prisma · PostgreSQL**

Full-stack booking platform designed for beauty salons and barbershops.

Clients can browse services and specialists, select a date and time, and submit booking requests online.

**Key features:**

- Responsive user interface
- Service and specialist selection
- Online booking workflow
- REST API
- PostgreSQL database integration
- Prisma ORM
- Administration functionality
- Production deployment

➡️ **[Live Demo](https://beauty-booking-site.vercel.app/)**

---

### 🏦 MiniBank Ledger API

**C# · ASP.NET Core · REST API · CQRS · MediatR · Entity Framework Core**

Backend banking API focused on API architecture, business logic, persistence, and separation of responsibilities.

**Focus areas:**

- REST API design
- ASP.NET Core
- CQRS
- MediatR
- Entity Framework Core
- Database persistence
- Backend architecture

➡️ **[View Repository](https://github.com/DayDreamingg-g/MiniBank-Ledger-API)**

---

### ⏱️ TimeMachine Agent

**C# · .NET**

Productivity tracking application designed to monitor different activity states and generate productivity reports.

The project tracks:

- Focus sessions
- Deep work
- Idle time
- Distractions
- Activity switching
- Productivity statistics

➡️ **[View Repository](https://github.com/DayDreamingg-g/TimeMachine.Agent)**

---

## 🔐 Cybersecurity

### 🧪 CyberLab

Practical cybersecurity learning repository containing hands-on labs, networking exercises, Linux practice, technical notes, and security reports.

**Current areas of study:**

- Networking fundamentals
- TCP/IP
- DNS
- DHCP
- ARP
- NAT
- Linux
- Kali Linux
- SOC fundamentals
- Web Security
- Application Security

➡️ **[View Repository](https://github.com/DayDreamingg-g/CyberLab)**

---

# 🛠️ Tech Stack

### 🤖 AI & Automation

`n8n` · `OpenAI` · `AI Agents` · `LLM Workflows` · `Workflow Automation`

### 💻 Web Development

`React` · `Next.js` · `TypeScript` · `JavaScript` · `HTML` · `CSS` · `Tailwind CSS`

### ⚙️ Backend

`C#` · `.NET` · `ASP.NET Core` · `REST APIs` · `CQRS` · `MediatR`

### 🗄️ Data

`PostgreSQL` · `SQLite` · `SQL` · `Prisma` · `Entity Framework Core`

### 🔗 Integrations

`Webhooks` · `Telegram Bot API` · `Google Sheets` · `OAuth 2.0`

### 🛠️ Tools

`Git` · `GitHub` · `GitHub Actions` · `Docker` · `Linux` · `Vercel`

---

# 🎯 Current Focus

I'm currently developing my skills across:

- AI-powered workflow automation
- n8n workflow design
- AI Agent and LLM integration
- API and SaaS integrations
- Backend API architecture
- PostgreSQL and relational data
- Full-stack application development
- Cybersecurity fundamentals
- Web Security & Application Security

I particularly enjoy building systems where multiple technologies communicate with each other — **APIs, databases, AI models, messaging platforms, and automation tools**.

---

# 📫 Contact

- **Email:** [oleksandr.stepanov.tech@gmail.com](mailto:oleksandr.stepanov.tech@gmail.com)
- **LinkedIn:** [linkedin.com/in/daydreamingg](https://linkedin.com/in/daydreamingg)
- **GitHub:** [github.com/DayDreamingg-g](https://github.com/DayDreamingg-g)
- **Live Project:** [Beauty Booking Platform](https://beauty-booking-site.vercel.app/)

---

<div align="center">

### 💼 Open to Remote Junior Developer, AI Automation, and Internship opportunities.

</div>
