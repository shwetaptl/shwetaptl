# Shweta Patel

**Software Engineer | Backend, Cloud & Full-Stack**

Software Engineer with 6+ years building backend systems, REST APIs, and event-driven applications across the .NET, Azure, AWS, and GCP stack, including production work in regulated healthcare and enterprise SaaS environments. Recently completed an M.S. in Computer Information Science, extending that foundation into applied Python, cloud data pipelines, and AI-assisted engineering through the independent projects below.

---

## Selected Engineering Work

### [Queue Backlog Intelligence System](https://github.com/shwetaptl/QueueBacklogIntelligence)
Monitoring Azure Service Bus queues for backlog growth or SLA breaches usually means watching a dashboard with no fast way to tell a real breach from a blip, or to diagnose why it's happening.

A serverless pipeline of Azure Functions that polls queue metrics every 60 seconds, classifies the trend and likely root cause, and dispatches deduplicated Teams alerts — surfaced through a React dashboard with OAuth2 login (Azure AD + MSAL).

**Stack:** C#, .NET 8, Azure Functions, Service Bus, Table Storage, React 18, Docker

Design choice worth calling out: alerts require two consecutive clean readings before clearing, added after early testing showed severity "flapping" on borderline queues — alongside a noise-floor threshold that scales with queue size instead of one fixed cutoff for all queues.

### [Job Search Automation Pipeline](https://github.com/shwetaptl/job-search-automation)
Screening relevant software engineering postings across scattered sources — aggregator repos, individual company boards — means hours of manual reading every day.

A Python CLI that pulls listings from several GitHub-tracked job lists plus the Greenhouse public API, scrapes full descriptions (falling back to a headless browser for JS-rendered pages), and scores each posting against a persistent candidate profile via the Gemini API, with Groq as a fallback provider.

**Stack:** Python, Gemini API, Playwright, BeautifulSoup

Design choice worth calling out: the script auto-detects which LLM provider to use from whichever API key is set in the environment, so switching providers needs no code change, and it filters out non-matching seniority levels before scoring to cut API cost.

---

## Professional Engineering Highlights

- Diagnosed a backend issue causing roughly 4 in 10 requests to time out, and improved API response time by 40% through async processing, fewer database calls, and targeted indexing.
- Built the backend event-processing worker for an IoT medication-dispensing workflow, handling real-time pub/sub messages for 500+ patients (~7,500+ messages/day) while enforcing dose-timing business rules.
- Implemented JWT authentication and role-based access control across API endpoints, and built monitoring dashboards that cut incident-detection time from roughly two hours to fifteen minutes.
- Led and mentored a team of 6–8 engineers through structured code reviews, while delivering features in regulated healthcare and enterprise SaaS applications.

---

## Technical Stack

**Languages:** C#, Python, TypeScript, JavaScript, SQL, PowerShell

**Frameworks & Libraries:** .NET / ASP.NET Core, ASP.NET MVC, Entity Framework, React, Redux, SignalR

**Databases & Storage:** SQL Server, Azure SQL, Redis, Azure Table Storage, BigQuery

**Cloud Platforms:**
- Azure — Functions, App Service, Service Bus, Key Vault, Application Insights
- AWS — IoT Core, Lambda
- Google Cloud — Pub/Sub, Dataflow, Cloud Storage, BigQuery (project experience)

**AI & Automation:** Gemini API, Groq API, Playwright, BeautifulSoup, LLM integration, structured prompting

**Testing & Delivery:** NUnit, xUnit, Azure DevOps, GitHub Actions, Docker, Git

**Engineering Practices:** REST API design, event-driven architecture, CQRS, SOLID principles, database performance tuning, authentication and authorization, observability

---

## Algorithms & System Design

Algorithm practice solutions live in [leetcode-solutions](https://github.com/shwetaptl/leetcode-solutions).

For system design grounded in a real implementation rather than practice problems, see the [QBIS architecture notes](https://github.com/shwetaptl/QueueBacklogIntelligence/blob/main/docs/ARCHITECTURE.md).

---

## Education & Credentials

- M.S., Computer Information Science — Harrisburg University of Science and Technology — Aug 2026 — GPA 4.0/4.0
- B.E., Computer Engineering — LDRP Institute of Technology & Research — 2018 — GPA 8.3/10
- Microsoft Certified: Azure Fundamentals (AZ-900)
- HackerRank SQL Gold Badge
