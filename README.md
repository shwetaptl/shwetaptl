<div align="center">

# Shweta Patel

![Role](https://img.shields.io/badge/Software%20Engineer-Backend%20%7C%20Cloud%20%7C%20Full--Stack-FF6B35?style=for-the-badge)

![Location](https://img.shields.io/badge/📍-Seattle,_WA-0078D4?style=flat-square)
![Experience](https://img.shields.io/badge/💼-6%2B_Years_Experience-2EA043?style=flat-square)
![GitHub](https://img.shields.io/badge/GitHub-shwetaptl-181717?style=flat-square&logo=github&logoColor=white)

Software Engineer with 6+ years building backend systems, REST APIs, and event-driven applications across the .NET, Azure, AWS, and GCP stack, including production work in regulated healthcare and enterprise SaaS environments. Recently completed an M.S. in Computer Information Science, extending that foundation into applied Python, cloud data pipelines, and AI-assisted engineering through the independent projects below.

</div>

---

<div align="center">

| ⚡ 40% | 📨 7,500+/day | ⏱️ 2hrs → 15min | 🔒 500+ |
|:---:|:---:|:---:|:---:|
| API response time improved | messages processed<br>(IoT event workflow) | incident detection<br>time cut | patients served via<br>real-time event processing |

</div>

---

## 🎓 Certifications

<div align="center">

![AZ-900](https://img.shields.io/badge/Microsoft-Azure%20Fundamentals%20(AZ--900)-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![HackerRank](https://img.shields.io/badge/HackerRank-SQL%20Gold%20Badge-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)

</div>

---

## 🚀 Selected Engineering Work

### [Queue Backlog Intelligence System](https://github.com/shwetaptl/QueueBacklogIntelligence)

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![.NET 8](https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Azure Functions](https://img.shields.io/badge/Azure_Functions-0062AD?style=flat-square&logo=azurefunctions&logoColor=white)
![React](https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Stars](https://img.shields.io/github/stars/shwetaptl/QueueBacklogIntelligence?style=flat-square&color=F5A623)

Monitoring Azure Service Bus queues for backlog growth or SLA breaches usually means watching a dashboard with no fast way to tell a real breach from a blip, or to diagnose why it's happening.

A serverless pipeline of Azure Functions that polls queue metrics every 60 seconds, classifies the trend and likely root cause, and dispatches deduplicated Teams alerts — surfaced through a React dashboard with OAuth2 login (Azure AD + MSAL).

> **Design choice worth calling out:** alerts require two consecutive clean readings before clearing, added after early testing showed severity "flapping" on borderline queues — alongside a noise-floor threshold that scales with queue size instead of one fixed cutoff for all queues.

### [Job Search Automation Pipeline](https://github.com/shwetaptl/job-search-automation)

![Python](https://img.shields.io/badge/Python_3.11-3776AB?style=flat-square&logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4B8BBE?style=flat-square&logo=python&logoColor=white)
![Stars](https://img.shields.io/github/stars/shwetaptl/job-search-automation?style=flat-square&color=F5A623)

Screening relevant software engineering postings across scattered sources — aggregator repos, individual company boards — means hours of manual reading every day.

A Python CLI that pulls listings from several GitHub-tracked job lists plus the Greenhouse public API, scrapes full descriptions (falling back to a headless browser for JS-rendered pages), and scores each posting against a persistent candidate profile via the Gemini API, with Groq as a fallback provider.

> **Design choice worth calling out:** the script auto-detects which LLM provider to use from whichever API key is set in the environment, so switching providers needs no code change, and it filters out non-matching seniority levels before scoring to cut API cost.

---

## 💡 Professional Engineering Highlights

- Diagnosed a backend issue causing roughly 4 in 10 requests to time out, and improved API response time by 40% through async processing, fewer database calls, and targeted indexing.
- Built the backend event-processing worker for an IoT medication-dispensing workflow, handling real-time pub/sub messages for 500+ patients (~7,500+ messages/day) while enforcing dose-timing business rules.
- Implemented JWT authentication and role-based access control across API endpoints, and built monitoring dashboards that cut incident-detection time from roughly two hours to fifteen minutes.
- Led and mentored a team of 6–8 engineers through structured code reviews, while delivering features in regulated healthcare and enterprise SaaS applications.

---

## 🛠️ Technical Stack

**Languages**
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

**Frameworks & Libraries**
![.NET](https://img.shields.io/badge/.NET_/_ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET MVC](https://img.shields.io/badge/ASP.NET_MVC-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity_Framework-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![SignalR](https://img.shields.io/badge/SignalR-512BD4?style=flat-square&logo=dotnet&logoColor=white)

**Databases & Storage**
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Azure SQL](https://img.shields.io/badge/Azure_SQL-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Azure Table Storage](https://img.shields.io/badge/Azure_Table_Storage-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)

**Cloud Platforms**

*Azure*
![Functions](https://img.shields.io/badge/Functions-0062AD?style=flat-square&logo=azurefunctions&logoColor=white)
![App Service](https://img.shields.io/badge/App_Service-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Service Bus](https://img.shields.io/badge/Service_Bus-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Key Vault](https://img.shields.io/badge/Key_Vault-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![App Insights](https://img.shields.io/badge/App_Insights-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

*AWS*
![IoT Core](https://img.shields.io/badge/IoT_Core-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)

*Google Cloud (project experience)*
![Pub/Sub](https://img.shields.io/badge/Pub%2FSub-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Dataflow](https://img.shields.io/badge/Dataflow-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Cloud Storage](https://img.shields.io/badge/Cloud_Storage-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)

**AI & Automation**
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_API-F55036?style=flat-square&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4B8BBE?style=flat-square&logo=python&logoColor=white)

**Testing & Delivery**
![NUnit](https://img.shields.io/badge/NUnit-000000?style=flat-square)
![xUnit](https://img.shields.io/badge/xUnit-512BD4?style=flat-square)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Engineering Practices:** REST API design · event-driven architecture · CQRS · SOLID principles · database performance tuning · authentication and authorization · observability

---

## 🧩 Algorithms & System Design

Algorithm practice solutions live in [leetcode-solutions](https://github.com/shwetaptl/leetcode-solutions).

For system design grounded in a real implementation rather than practice problems, see the [QBIS architecture notes](https://github.com/shwetaptl/QueueBacklogIntelligence/blob/main/docs/ARCHITECTURE.md).

---

## 🎓 Education

- **M.S., Computer Information Science** — Harrisburg University of Science and Technology — Aug 2026 — GPA 4.0/4.0
- **B.E., Computer Engineering** — LDRP Institute of Technology & Research — 2018 — GPA 8.3/10
