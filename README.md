# Thanvir Ibrahim

**Software Engineer • Go + Next.js • Backend Systems & Financial Operations**

📍 Chennai, India  •  ✉️ thanvir200@gmail.com  •  [LinkedIn](#)  •  [Portfolio](#)

---

Go backend engineer building systems that replace manual operations with measurable outcomes. I designed and own a **120-endpoint financial operations platform** that 500+ users depend on daily, and cut partner payout cycles from **3+ months to under 14 days**.

Every feature I ship is measured against one of three targets: cycle time cut, manual steps eliminated, or errors driven to zero.

---

## 🛠️ Tech Stack

**Backend:** Go • MongoDB • Redis • RabbitMQ • REST APIs  
**Frontend:** Next.js • React • React Query • Tailwind CSS  
**Infrastructure:** Docker • Kubernetes • Jenkins CI/CD  
**Integrations:** Zoho Books API • Novu • JWT + RBAC  
**Also work with:** Python • FastAPI • Qdrant • Claude APIs • AWS

---

## 🚀 Featured Projects

### 💰 Basik360 — Payout & Finance Operations Platform
**Go • Next.js • MongoDB • Zoho Books API • Redis • RabbitMQ • Kubernetes**

> 🌐 [360.basikmarketing.in](https://360.basikmarketing.in)

- Internal platform automating payouts, compliance, and financial tracking for esports events with **500+ registered partners**
- Replaced a workflow that required **4 separate tools and 6+ manual handoffs** per payment
- **120+ production REST APIs** across 5 modules — inventory, projects, estimates, file sharing, payouts
- Cut partner payout cycles from **3+ months → under 14 days**, eliminated manual reconciliation entirely
- Integrated with Zoho Books for invoice verification, partner onboarding, and automated disbursement
- Finance teams close monthly books **3x faster** than the previous manual process
- Redis caching cut API response times by **500ms/request**; RabbitMQ async queues ensure zero dropped submissions during concurrent batch payouts
- Deployed across a **60-pod Kubernetes cluster** with Jenkins CI/CD on every production push

---

### 🐞 Jira Bug Auto-Fixer
**Go • Claude Code CLI • Jira REST API • Webhooks • Git Worktrees**

> 🔗 [github.com/ThanvirXo/jira-bug-auto-solver](https://github.com/ThanvirXo/jira-bug-auto-solver)

- Webhook-driven Go server that turns Jira bug tickets into ready-to-merge code fixes with **zero manual triage**
- **Jira Automation webhooks** push assigned bugs into the service, which writes structured context (title, description, repro steps) to the target repo
- A **file watcher** detects new bug context files and automatically invokes **Claude Code sub-agents** to locate the relevant code and generate a fix
- Each fix lands in an **isolated Git worktree** per issue — review the diff, merge, done
- Collapsed the bug-fix workflow to a single human step: review and merge

---

### 🎬 Movie Suggesting Agent
**Python • FastAPI • Pydantic-AI • Qdrant • LLaMA 3.2**

> 🔗 [github.com/ThanvirXo/movie-agent](https://github.com/ThanvirXo/movie-agent)

- AI-powered movie recommendation agent supporting natural-language queries
- **Semantic vector search** over **10,000+ TMDB movies** loaded into Qdrant
- Retrieval orchestrated via **Pydantic-AI** and **LLaMA 3.2**
- Designed scalable backend with FastAPI

---

## 💼 Currently

**Software Development Engineer @ Basik Marketing Private Limited** (Mar 2023 – Present)

Owning Basik360 end-to-end: architecture, Go backend, Next.js dashboard, Kubernetes deployment, and the Zoho integration. Started as an intern, took over the platform build after 6 months.

---

## 🎓 Education

**B.E., Computer Science** — KCG College of Technology, Chennai  
Graduated April 2022 • CGPA: 7.75 / 10

---

## 📫 Let's Connect

Always open to conversations about backend systems, payment infrastructure, or LLM-driven dev tooling.

📧 thanvir200@gmail.com
