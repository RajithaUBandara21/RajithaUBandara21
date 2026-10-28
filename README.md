<div align="center">

# Hi, I'm Rajitha Bandara

<a href="https://rajithabandara.dev">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3000&pause=1000&color=E5E5E5&center=true&vCenter=true&width=640&lines=Software+Engineer;Java+%C2%B7+Spring+Boot+%C2%B7+Microservices;Event-driven+systems+with+Kafka;React+%C2%B7+Next.js+%C2%B7+AWS">
    <img alt="Software Engineer · Java · Spring Boot · Microservices" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3000&pause=1000&color=171717&center=true&vCenter=true&width=640&lines=Software+Engineer;Java+%C2%B7+Spring+Boot+%C2%B7+Microservices;Event-driven+systems+with+Kafka;React+%C2%B7+Next.js+%C2%B7+AWS">
  </picture>
</a>

**Software Engineer** · BSc (Hons) IT, University of Moratuwa · Colombo, Sri Lanka 🇱🇰

![Open to work](https://img.shields.io/badge/Open%20to-Software%20Engineer%20roles-22c55e?style=flat-square)
![Remote](https://img.shields.io/badge/Remote-friendly-171717?style=flat-square)

[![Portfolio](https://img.shields.io/badge/Portfolio-rajithabandara.dev-171717?style=for-the-badge&logo=googlechrome&logoColor=white)](https://rajithabandara.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-171717?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rajithaubandara/)
[![Medium](https://img.shields.io/badge/Medium-171717?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@rajithaubandara)
[![Email](https://img.shields.io/badge/Email-171717?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rajithaubandara@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-171717?style=for-the-badge&logo=readdotcv&logoColor=white)](https://rajithabandara.dev/resume)

</div>

---

### 👋 About me

I build **backend-heavy, production-minded systems**: Spring Boot microservices, event-driven workflows on Kafka, secure APIs with OAuth2/OIDC, and the CI/CD and observability around them. On the frontend I work with React, Next.js and React Native.

- 💼 **Software Engineer Intern @ Sharemind** (Mar–Oct 2025): shipped React Native and .NET/C# apps, including REST APIs for a client app built for **1,000+ concurrent users**
- 🛒 Built a **10-service e-commerce platform** with a Kafka checkout saga, Keycloak security and Jenkins CI/CD
- 🧱 Currently building a **multi-tenant SaaS ERP** on Spring Boot 4 and Next.js 16
- 🤖 Exploring **local LLMs**: an offline email triage assistant running on Ollama
- 🎓 BSc (Hons) in Information Technology, University of Moratuwa (2026)
- 📫 Reach me at **rajithaubandara@gmail.com**. I'm open to Software Engineer roles, on-site or remote.

---

### 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### 🛒 [Multi-Vendor E-Commerce Platform](https://github.com/RajithaUBandara21/e-commerce-app)
10 Spring Boot microservices behind Spring Cloud Gateway, with a Next.js storefront.

- **Kafka checkout saga** (stock reservation → Stripe payment) with compensation on failure
- **Optimistic locking and idempotency keys** to prevent overselling and double charges
- Resilience4j, Redis rate limiting, **Keycloak** RBAC
- JUnit, Testcontainers and Playwright tests; Prometheus, Grafana and Zipkin for observability

`Java` `Spring Cloud` `Kafka` `Keycloak` `PostgreSQL` `Redis` `Docker`

</td>
<td width="50%" valign="top">

#### 🧱 [Multi-Tenant SaaS ERP](https://github.com/RajithaUBandara21/erp-bf) · *in progress*
Odoo-style ERP on Spring Boot 4 and Next.js 16, starting with the identity and tenancy core.

- JWT access and refresh tokens (hashed in Redis), session revocation, Google OAuth 2.0
- Custom roles with **fine-grained permissions** via Spring method security
- Org invites, org switching, OTP-protected super-admin, audit logging
- **401 JUnit tests**, 21 Flyway migrations, Playwright E2E

`Java 21` `Spring Boot 4` `Spring Security` `PostgreSQL` `Redis` `Next.js`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🤖 [Offline LLM Email Triage Assistant](https://github.com/RajithaUBandara21/Local-llm)
Classifies support emails, sets priority and drafts replies using **local LLMs via Ollama**.

- Pydantic-validated structured output with retry and a manual-review fallback
- Crash-resumable batch pipeline backed by SQLite, with a decision log
- Benchmarked Llama 3.2, Mistral and Qwen 2.5 on latency, memory and JSON validity
- Gmail OAuth 2.0 integration, **269 pytest tests**

`Python` `FastAPI` `Pydantic` `Ollama` `SQLite` `Next.js`

</td>
<td width="50%" valign="top">

#### ⚙️ [Jenkins CI/CD Shared Library](https://github.com/RajithaUBandara21/e-com-app-ci-shared-library)
Standardized pipelines for every microservice, running on AWS EC2 in a private VPC.

- Groovy shared library that cut delivery time **from hours to minutes**
- Triggered by GitHub webhooks
- **SonarQube** quality gates and **Trivy** scans block critical vulnerabilities
- Publishes to Docker Hub and Nexus

`Jenkins` `Groovy` `AWS` `Docker` `SonarQube` `Trivy`

</td>
</tr>
</table>

<sub>More: <a href="https://github.com/RajithaUBandara21/Medicare-Booking">Medicare: doctor appointment booking (MERN)</a> · all projects at <a href="https://rajithabandara.dev/projects">rajithabandara.dev/projects</a></sub>

---

### 🛠️ Tech stack

<table>
<tr><td><b>Languages</b></td><td>
<img src="https://skillicons.dev/icons?i=java,cs,ts,js,py&theme=dark" height="40" alt="Java, C#, TypeScript, JavaScript, Python">
</td></tr>
<tr><td><b>Backend</b></td><td>
<img src="https://skillicons.dev/icons?i=spring,dotnet,nodejs,express,fastapi&theme=dark" height="40" alt="Spring Boot, .NET, Node.js, Express, FastAPI">
</td></tr>
<tr><td><b>Frontend & Mobile</b></td><td>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,materialui&theme=dark" height="40" alt="React, React Native, Next.js, Tailwind CSS, Material UI">
</td></tr>
<tr><td><b>Data & Messaging</b></td><td>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,kafka&theme=dark" height="40" alt="PostgreSQL, MySQL, MongoDB, Redis, Kafka">
</td></tr>
<tr><td><b>Cloud & DevOps</b></td><td>
<img src="https://skillicons.dev/icons?i=aws,docker,jenkins,githubactions,maven,linux,git&theme=dark" height="40" alt="AWS, Docker, Jenkins, GitHub Actions, Maven, Linux, Git">
</td></tr>
<tr><td><b>Observability</b></td><td>
<img src="https://skillicons.dev/icons?i=prometheus,grafana&theme=dark" height="40" alt="Prometheus, Grafana">
</td></tr>
</table>

**Also:** Spring Cloud (Gateway, Eureka, Config) · Resilience4j · Keycloak · OAuth2/OIDC · JWT · RBAC · Saga pattern · JUnit · Mockito · Testcontainers · Playwright · Zipkin · SonarQube · Trivy · Nexus · Ollama

---

### 🏆 Highlights

- 🥇 **Top 10 Finalist**, Code Rush 2024 (INTECS, University of Moratuwa)
- 🥈 **Top 15 Finalist**, Hack Streem 3.0 (IEEE, University of Ruhuna)
- 🥉 **Top 20 Finalist**, OpenHack 2023 (IIT Sri Lanka)
- 📜 AWS Cloud Technical Essentials · Claude Code in Action (Anthropic) · Ultimate DevOps Bootcamp
- 🧭 President of the Fitmoment Media Unit · Main Coordinator, INTECS Career Fair 2024

---

### 📊 GitHub activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=RajithaUBandara21&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=0a0a0a&title_color=fafafa&text_color=a3a3a3&icon_color=fafafa">
  <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=RajithaUBandara21&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=ffffff&title_color=171717&text_color=525252&icon_color=171717">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=RajithaUBandara21&layout=compact&hide_border=true&langs_count=8&bg_color=0a0a0a&title_color=fafafa&text_color=a3a3a3">
  <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RajithaUBandara21&layout=compact&hide_border=true&langs_count=8&bg_color=ffffff&title_color=171717&text_color=525252">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=RajithaUBandara21&hide_border=true&background=0a0a0a&ring=fafafa&fire=fafafa&currStreakLabel=fafafa&sideLabels=a3a3a3&currStreakNum=fafafa&sideNums=fafafa&dates=737373&stroke=262626">
  <img alt="GitHub streak" src="https://streak-stats.demolab.com?user=RajithaUBandara21&hide_border=true&background=ffffff&ring=171717&fire=171717&currStreakLabel=171717&sideLabels=525252&currStreakNum=171717&sideNums=171717&dates=737373&stroke=e5e5e5">
</picture>

</div>

---

<div align="center">

**Hiring or collaborating?** Take a look at [my portfolio](https://rajithabandara.dev), read [my resume](https://rajithabandara.dev/resume) or [email me](mailto:rajithaubandara@gmail.com).

![Profile views](https://komarev.com/ghpvc/?username=RajithaUBandara21&color=171717&style=flat-square&label=Profile+views)

</div>
