<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=140&color=0:0f2027,50:203a43,100:2c5364&section=header" width="100%" alt="" />
</p>

<table>
<tr>
<td width="170" valign="top">

<img src="https://github.com/asayenju.png?size=300" width="150" alt="Ashwin Sayenju" />

</td>
<td valign="top">

# Hi, I'm Ashwin Sayenju 👋

CS senior at **UMass Amherst** (3.83 GPA, Dean's List 4×) building AI-powered and full-stack products. I like finding the real bottleneck first, then fixing it with the simplest design that holds up.

**Right now** I'm focused on agentic systems, RAG pipelines, and the backend infrastructure that keeps them reliable. I'm looking for new grad software engineering roles starting 2027.

📍 Amherst, MA

</td>
</tr>
</table>

<p align="center">
  <a href="https://github.com/asayenju">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2C9CDB&center=true&vCenter=true&width=640&lines=Agentic+systems+%26+RAG+pipelines;Cut+LLM+tokens+per+query+300K+%E2%86%92+10K;Backend+infra+that+stays+reliable;Open+to+new+grad+SWE+roles+(2027)" alt="Typing animation" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ashwin-sayenju"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:ashwinsayenju@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/asayenju"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

---

## What I've shipped

**Desmata Inc.** · AI Software Engineer Intern · Summer 2026
- Built the agent architecture and the React/TypeScript and Python stack of an unreleased AI travel planner for backpackers in remote areas.
- Cut LLM tokens per query from **300K to 10K** after finding one agent reasoning over 20 to 30 tools, then splitting it into specialized agents with a small open-source model for routing.
- Lowered latency **25%** with a Redis cache after telemetry showed repeated flight searches overloading the backend.
- Deployed flight and hotel agents as **8 services** on Kubernetes and AWS, using gRPC between internal services.
- Created an LLM-as-a-judge evaluation harness that scored agents **4.89/5** on taking the right action.

**Unlimited Cloud** · Software Engineer Intern · Summer 2025
- Delivered a money-transfer app for **5 international clients and 10K customers** with a Java backend, GraphQL, TypeScript/React Native, and Kotlin, using HTTPS and OTP authentication to meet fintech laws.
- Raised availability from **99.9% to 99.99%** with a backup microservice that fails over automatically.
- Decreased onboarding drop-off **30%** and lifted CSAT to **4.5/5** by redesigning onboarding as staged loading.

**UMass Amherst ERSP** · IoT and ML Researcher · 2024 to 2025
- Wrote C++ sensor code and a data pipeline for bike and ride-sharing driver intoxication detection.
- Streamed **100,000+ data points at 166 req/sec and 19ms latency** through Kafka with circuit breaking.
- Trained head-gesture classifiers in PyTorch and TensorFlow, reaching **94% accuracy** across 400+ datasets.

---

## Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**Memora**](https://github.com/asayenju/club_operations_slack_agent) | Slack hackathon project. An agentic AI feature that reconciles conflicting records across 3 enterprise systems, with OAuth, MCP, encrypted tokens, and human review of low-confidence decisions. Elo-style source confidence tiers reach 95% recall and precision with 452 pytest tests. | Python, Claude API, pgvector, Slack, Google APIs |
| [**Amex Developer Portal Assistant**](https://amex-developerportal-rag.vercel.app/) | RAG assistant that answers developer questions across large documentation sets. Reaches 99.3% recall@3 and 4.76/5 faithfulness on a 50-question LLM-judge harness, and uses OCR for documentation that only lives in images. | Python, FastAPI, pgvector, React, TypeScript |
| [**PM Feature Reviewer RAG**](https://github.com/asayenju/PM_review_rag) | RAG tool for reviewing product features, with 92.3% retrieval recall and Redis caching that cuts LLM latency by about 60%. | Next.js, FastAPI, pgvector, Redis |
| [**Smart Meeting Scheduler**](https://github.com/asayenju/meeting_schedule_assistant) | Agentic pipeline for intent classification, conflict resolution, and email drafting over Google Calendar and Gmail. | Python, FastAPI, React, OAuth 2.0 |
| [**Interview Practice AI**](https://github.com/asayenju/interview-practice-ai-frontend) | Voice-driven interview coaching platform that scores your responses. | TypeScript, React, Gemini API, GCP |
| [**Campus Bikes**](https://github.com/Oren-Schmerling/CampusBikes) | Real-time bike and scooter rental marketplace for 27,000 students. I led a 4-person Agile team with 24 REST endpoints and 39 tests in CI. | Java, Spring Boot, PostgreSQL, WebSockets |

---

## Tech I work with

**Languages** Python · TypeScript · Java · JavaScript · SQL · C/C++ · Go

**Backend and APIs** FastAPI · Spring Boot · REST · GraphQL · gRPC · OAuth

**Frontend** React · Next.js · React Native

**Data and cloud** PostgreSQL · MySQL · Redis · Kafka · Docker · Kubernetes · AWS · GitLab CI/CD · Prometheus

**AI and agents** Agentic systems · RAG · MCP · LLM evaluations · Claude API · Claude Code · Cursor · Copilot

---

## How I like to work

- **Start from the problem.** I read telemetry, competitor flows, and failure cases before writing code.
- **Measure it.** Every project above has a number attached, from token counts to recall to availability.
- **Own the handoff.** I document what I built, how to improve it, and then teach the next person.

Open to chat about agents, RAG, or infrastructure. Feel free to reach out.
