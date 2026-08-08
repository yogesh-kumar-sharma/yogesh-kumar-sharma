<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,100:161B22&height=3&section=header" width="100%"/>

<br/>

# Yogesh Kumar Sharma

### Backend Engineer — FastAPI · PostgreSQL · Production Systems

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=17&duration=3000&pause=1200&color=8B949E&center=true&vCenter=true&width=600&lines=Designing+production-ready+backend+systems;FastAPI+%C2%B7+PostgreSQL+%C2%B7+SQLAlchemy+2.0;Repository+Pattern+%C2%B7+RBAC+%C2%B7+Docker+%C2%B7+CI%2FCD" alt="Typing SVG" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-0D1117?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-zeta-six-vrbq18bmw9.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D1117?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yogesh-kumar0)
[![GitHub](https://img.shields.io/badge/GitHub-0D1117?style=flat-square&logo=github&logoColor=white)](https://github.com/yogesh-kumar-sharma)
[![Email](https://img.shields.io/badge/Email-0D1117?style=flat-square&logo=gmail&logoColor=white)](mailto:yogesh.kumar.sharma.dev@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,100:161B22&height=3&section=header" width="100%"/>

</div>

<br/>

## About

I design and ship backend systems where correctness, security, and maintainability aren't afterthoughts — they're the architecture. My core stack is **FastAPI**, **PostgreSQL**, and **SQLAlchemy**, built around repository pattern, service-layer separation, and dependency injection, so systems stay testable as they grow.

I've worked through the parts of backend engineering that don't show up in tutorials: refresh-token rotation that doesn't break active sessions, RBAC that holds up under real permission edge cases, and containerized deployments that behave the same in staging as they do in production. I've also integrated AI-driven features — like resume parsing and scoring — into REST APIs, treating them as just another service layer to design around.

I build for production, not for demos.

<br/>

## Tech Stack

<table>
<tr>
<td><strong>Languages</strong></td>
<td><img src="https://skillicons.dev/icons?i=python,ts,js" /></td>
</tr>
<tr>
<td><strong>Backend</strong></td>
<td><img src="https://skillicons.dev/icons?i=fastapi,nodejs" /></td>
</tr>
<tr>
<td><strong>Database</strong></td>
<td><img src="https://skillicons.dev/icons?i=postgres,sqlite" /></td>
</tr>
<tr>
<td><strong>ORM & Migrations</strong></td>
<td><img src="https://img.shields.io/badge/SQLAlchemy-0D1117?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Alembic-0D1117?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Pydantic-0D1117?style=flat-square&logo=pydantic&logoColor=white" /></td>
</tr>
<tr>
<td><strong>Authentication</strong></td>
<td><img src="https://img.shields.io/badge/JWT-0D1117?style=flat-square&logo=jsonwebtokens&logoColor=white" /> <img src="https://img.shields.io/badge/OAuth2-0D1117?style=flat-square&logo=auth0&logoColor=white" /> <img src="https://img.shields.io/badge/RBAC-0D1117?style=flat-square" /></td>
</tr>
<tr>
<td><strong>Caching</strong></td>
<td><img src="https://skillicons.dev/icons?i=redis" /></td>
</tr>
<tr>
<td><strong>DevOps & CI/CD</strong></td>
<td><img src="https://skillicons.dev/icons?i=docker,githubactions,git,github,linux" /></td>
</tr>
<tr>
<td><strong>Cloud & Deployment</strong></td>
<td><img src="https://skillicons.dev/icons?i=aws,vercel" /> <img src="https://img.shields.io/badge/Railway-0D1117?style=flat-square&logo=railway&logoColor=white" /> <img src="https://img.shields.io/badge/Neon-0D1117?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Render-0D1117?style=flat-square&logo=render&logoColor=white" /></td>
</tr>
<tr>
<td><strong>API Tools & Docs</strong></td>
<td><img src="https://skillicons.dev/icons?i=postman" /> <img src="https://img.shields.io/badge/OpenAPI-0D1117?style=flat-square&logo=swagger&logoColor=white" /></td>
</tr>
<tr>
<td><strong>Testing</strong></td>
<td><img src="https://img.shields.io/badge/Pytest-0D1117?style=flat-square&logo=pytest&logoColor=white" /></td>
</tr>
<tr>
<td><strong>Dev Tools</strong></td>
<td><img src="https://skillicons.dev/icons?i=vscode" /></td>
</tr>
</table>

<br/>

## Featured Projects

### CampusOS ERP
<sub>Flagship Project</sub>

Production College ERP backend built to manage multi-role academic operations — students, faculty, and administration — behind a single, secured API.

**Architecture**
- Repository Pattern → Service Layer → API Layer, decoupled through Dependency Injection
- JWT authentication with RBAC scoped across student, faculty, and admin roles
- PostgreSQL on Neon, managed with SQLAlchemy 2.0 and Alembic migrations
- Redis caching on high-read endpoints
- Dockerized and deployed to production on Railway

**Key Features**
- Role-scoped dashboards and permission boundaries
- Secure session and token lifecycle management
- Pydantic-validated request/response contracts
- Full interactive OpenAPI documentation

**Stack:** `FastAPI` `PostgreSQL` `SQLAlchemy 2.0` `Alembic` `Redis` `Docker` `JWT` `RBAC`

[![Repository](https://img.shields.io/badge/Repository-0D1117?style=flat-square&logo=github&logoColor=white)](https://github.com/yogesh-kumar-sharma/campusos)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-0D1117?style=flat-square&logo=vercel&logoColor=white)](https://campusos-lac.vercel.app/login)
[![API Docs](https://img.shields.io/badge/API%20Docs-0D1117?style=flat-square&logo=swagger&logoColor=white)](https://campusos-production-26bf.up.railway.app/docs)

---

### Authentication API

Standalone, production-ready authentication service — the kind of system most products build on top of.

**Architecture & Features**
- JWT access tokens with refresh-token rotation
- RBAC for scoped route protection
- Email verification and secure password reset flows
- Alembic-managed schema migrations
- Fully Dockerized

**Stack:** `FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `JWT` `Docker`

[![Repository](https://img.shields.io/badge/Repository-0D1117?style=flat-square&logo=github&logoColor=white)](https://github.com/yogesh-kumar-sharma/authentication-api-fastapi)

---

### AI Resume Analyzer

AI-powered backend that parses and scores resumes against ATS (Applicant Tracking System) criteria.

**Key Features**
- PDF parsing and text-extraction pipeline
- ATS-style scoring and keyword-gap analysis
- AI-integrated evaluation layer for structured feedback

**Stack:** `Python` `FastAPI` `PDF Parsing` `AI Integration`

[![Repository](https://img.shields.io/badge/Repository-0D1117?style=flat-square&logo=github&logoColor=white)](https://github.com/yogesh-kumar-sharma/AI_Resume_Analyzer)

---

### Portfolio Website

Personal developer portfolio presenting backend projects, live deployments, and production architecture.

**Stack:** `Next.js` `TypeScript` `Tailwind CSS` `Framer Motion`

[![Live Demo](https://img.shields.io/badge/Live%20Demo-0D1117?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-zeta-six-vrbq18bmw9.vercel.app/)
[![Repository](https://img.shields.io/badge/Repository-0D1117?style=flat-square&logo=github&logoColor=white)](https://github.com/yogesh-kumar-sharma)

---

### Blog Platform API
<sub>Status: Coming Soon</sub>

Production-grade blogging backend in development.

**Planned Features**
- JWT authentication
- Comments, likes, and bookmarks
- Tagging and full-text search
- Dockerized deployment

**Stack:** `FastAPI` `PostgreSQL` `SQLAlchemy` `Docker`

<br/>

## Current Focus

- Production API design and backend architecture
- System design for distributed, high-availability services
- Redis-backed caching strategies
- CI/CD pipelines and cloud deployment on AWS

<br/>

## GitHub Analytics

<table align="center">
<tr>
<td><img src="https://github-readme-stats.vercel.app/api?username=yogesh-kumar-sharma&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=8B949E&icon_color=8B949E&text_color=C9D1D9" /></td>
<td><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yogesh-kumar-sharma&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=8B949E&text_color=C9D1D9" /></td>
</tr>
</table>

<div align="center">
<img src="https://streak-stats.demolab.com?user=yogesh-kumar-sharma&theme=dark&hide_border=true&background=0D1117&ring=8B949E&fire=8B949E&currStreakLabel=8B949E" />
</div>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=yogesh-kumar-sharma&theme=github-compact&hide_border=true&bg_color=0D1117&color=8B949E&line=8B949E&point=C9D1D9" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/yogesh-kumar-sharma/yogesh-kumar-sharma/output/github-contribution-grid-snake-dark.svg" />
</div>

<br/>

## Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-zeta-six-vrbq18bmw9.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yogesh-kumar-sharma)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yogesh-kumar0)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yogesh.kumar.sharma.dev@gmail.com)

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,100:161B22&height=3&section=footer" width="100%"/>

<div align="center">
<sub>FastAPI · PostgreSQL · Systems built to run in production, not just in demos.</sub>
</div>
