<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,60:1E293B,100:4C1D95&height=190&section=header&text=Nour%20Elden%20Ashraf&fontColor=ffffff&fontSize=44&fontAlignY=38&desc=Mid-Level%20Backend%20Engineer%20%C2%B7%20Laravel%20%C2%B7%20AI%20Systems&descAlignY=60&descSize=18" width="100%" />

<div align="center">

<a href="https://github.com/noureldenashraf"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=22D3EE&center=true&vCenter=true&width=600&lines=Multi-tenant+SaaS+architecture;Laravel+APIs+built+for+production;AI+automation+pipelines+that+stay+up;Top+Rated+on+Upwork+%C2%B7+100%25+JSS" alt="Typing intro" /></a>

<br/>

<a href="https://www.linkedin.com/in/nour-elden-ashraf/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" /></a>
<a href="https://www.upwork.com/freelancers/~01b5b2a1615b0d1dfd"><img src="https://img.shields.io/badge/Upwork-Top_Rated-14A800?logo=upwork&logoColor=white" /></a>
<a href="mailto:n.ashraf956@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?logo=gmail&logoColor=white" /></a>
<a href="https://github.com/noureldenashraf"><img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" /></a>

Cairo, Egypt &nbsp;|&nbsp; Available for remote roles

</div>

---

## About

Backend engineer building production-grade Laravel APIs, multi-tenant SaaS platforms, and AI-powered automation systems for international clients. I design the architecture, own delivery, and hold the code to a measurable quality bar.

<div align="center">

| 100% | 12+ | 10,000+ | 1,700+ |
|:---:|:---:|:---:|:---:|
| Upwork job success | projects delivered | messages/day in one pipeline | Pest tests in one codebase |

</div>

---

## How I Work

| Area | What that looks like |
|:--|:--|
| **Architecture** | Modular monoliths with DDD and ports and adapters, multi-tenant isolation at the scope and database level, OpenAPI-documented REST APIs |
| **Reliability** | Queue-first ingestion, job isolation, exponential backoff, state machines for long-running jobs, 202 responses in under 100ms |
| **Quality** | PHPStan level 7, 1,700+ Pest tests, standardized Git workflows and code review |
| **Delivery** | Every freelance project shipped 1-2 weeks early with zero rework, leading to 5+ referrals and repeat contracts |

---

## Tech Stack

**Languages and Frameworks**

<img src="https://skillicons.dev/icons?i=php,laravel,nodejs,js,html&theme=dark" />

**Databases and Infrastructure**

<img src="https://skillicons.dev/icons?i=mysql,postgres,redis,aws,docker,githubactions&theme=dark" />

**APIs, Tools and Integrations**

<img src="https://skillicons.dev/icons?i=wordpress,git,postman&theme=dark" />

![OpenAI API](https://img.shields.io/badge/OpenAI_API-1F2937?style=flat-square)
![Stripe](https://img.shields.io/badge/Stripe-1F2937?style=flat-square&logo=stripe&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger%2FOpenAPI-1F2937?style=flat-square&logo=swagger&logoColor=white)

---

## Experience

<table>
<tr>
<td width="180"><b>Aug 2026 - Present</b><br/>Full-time, Remote (Saudi Arabia)</td>
<td>

**Backend Software Engineer**, Birthofdream for Consulting & Research

- Architected the backend of a multi-tenant AI SaaS platform in **Laravel 13 / PHP 8.3**: modular monolith, DDD, ports and adapters, OpenAPI-documented REST APIs
- Built multi-tenancy with global Eloquent scopes and **RBAC (Spatie)**, including secure workspace switching
- Fixed gateway timeouts on 90-240s LLM jobs with queues, a state machine, and adaptive polling, returning **202 in under 100ms**
- Enforced quality with **PHPStan level 7** and **1,700+ Pest tests**

</td>
</tr>
<tr>
<td><b>May 2025 - Present</b><br/>Upwork, Top Rated, 100% JSS</td>
<td>

**Freelance Backend Developer**

- Delivered 12+ backend projects for international startups and agencies, focused on API-heavy apps and backend automation
- Built an AI content management system that cut manual file packaging by **60%**, so the client could handle **10x more** monthly content
- Integrated the OpenAI API into WordPress, automating content workflows and cutting production time by **70%**
- Delivered every project 1-2 weeks early with zero rework, which led to 5+ referrals and repeat contracts

</td>
</tr>
<tr>
<td><b>Apr 2025 - Oct 2025</b><br/>Part-time, Remote (New Zealand)</td>
<td>

**Backend Software Engineer**, GRASPED Digital

- Engineered 4+ AI-integrated PHP applications with a focus on reliability and pipeline stability
- Optimized queries and API response logic, taking average endpoint latency from **850ms to 580ms** (32% faster)
- Standardized Git workflows and code review, cutting merge conflicts by **80%** and speeding up team delivery 3x

</td>
</tr>
</table>

---

## Featured Projects

### CPA Client Collaboration Platform

<img src="https://skillicons.dev/icons?i=laravel,aws&theme=dark" height="40" />

`Laravel 12` `Livewire` `AWS S3` `DomPDF` `Stripe`

Multi-tenant SaaS for accounting firm operations, serving 50+ CPA practitioners.

- Modular multi-tenant system (DDD) with **database-level isolation**: 100% data separation across workspaces
- Full invoice lifecycle automated (PDF generation, scheduled reminders, async email), saving **40 hours/month** of manual work
- 2FA via Laravel Fortify, automatic suspension on failed logins, and S3 signed URLs for file access

### WhatsApp Event Monitoring System

<img src="https://skillicons.dev/icons?i=nodejs,laravel,redis&theme=dark" height="40" />

`Node.js` `Laravel` `Redis` `WebSockets` `Supervisor/PM2`

A dual-stack pipeline turning **10,000+ daily WhatsApp messages** into structured telemetry.

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#1E293B','primaryTextColor':'#E2E8F0','primaryBorderColor':'#22D3EE','lineColor':'#8B5CF6','secondaryColor':'#1E293B','tertiaryColor':'#0F172A'}}}%%
flowchart LR
    A[WhatsApp] --> B[Node.js<br/>WebSocket listener]
    B -->|queue-first| C[(Redis)]
    C --> D[Laravel worker]
    D --> E[AnalyzeMessage]
    E --> F[ForwardEvent]
    F --> G[5+ downstream systems]
```

- Sub-**20ms** response times under burst traffic
- Redis queue-first ingestion offloads payloads immediately and prevents socket backpressure
- Job isolation plus exponential backoff retries: **99.9% delivery reliability**

### AI PLR Content Generation System

<img src="https://skillicons.dev/icons?i=php,react&theme=dark" height="40" />

`PHP (MVC)` `OpenAI API` `React`

An AI content pipeline that lets creators produce **100+ articles/week**.

- Throughput up **65%** with async multi-cURL requests, per-article API cost down **40%**
- Multi-format export (DOCX/HTML/TXT) with streaming and batch processing, server latency down **50%**
- Fault-tolerant retry logic holding a **99.9% job success rate** on long-running AI jobs

---

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=noureldenashraf&show_icons=true&hide_border=true&bg_color=0D1117&title_color=22D3EE&icon_color=8B5CF6&text_color=C9D1D9" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=noureldenashraf&layout=compact&hide_border=true&bg_color=0D1117&title_color=22D3EE&text_color=C9D1D9" />

</div>

---

<div align="center">

**Open to:** Remote Backend Roles | AI Automation Projects | SaaS Architecture | Long-term Freelance

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4C1D95,60:1E293B,100:0F172A&height=100&section=footer" width="100%" />

</div>
