<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,100:161B22&height=2&section=header" width="100%"/>
</div>

<br/>

<h1 align="center">Yogesh Kumar Sharma</h1>
<p align="center"><sub>PYTHON BACKEND ENGINEER</sub></p>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=3200&pause=1400&color=8B949E&center=true&vCenter=true&width=620&lines=Backend+systems+built+for+production;FastAPI+%C2%B7+PostgreSQL+%C2%B7+SQLAlchemy+2.0;Repository+Pattern+%C2%B7+RBAC+%C2%B7+Docker" alt="Typing SVG" />
</p>

<p align="center">
<img src="https://img.shields.io/badge/Status-Open%20to%20Work-3FB950?style=flat-square&labelColor=0D1117" />
</p>

<p align="center">
<a href="https://portfolio-zeta-six-vrbq18bmw9.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-6E40C9?style=flat-square&logo=vercel&logoColor=white&labelColor=0D1117" /></a>
<a href="https://www.linkedin.com/in/yogesh-kumar0"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0D1117" /></a>
<a href="https://github.com/yogesh-kumar-sharma"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white&labelColor=0D1117" /></a>
<a href="mailto:yogesh.kumar.sharma.dev@gmail.com"><img src="https://img.shields.io/badge/Email-D93025?style=flat-square&logo=gmail&logoColor=white&labelColor=0D1117" /></a>
</p>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,100:161B22&height=2&section=header" width="100%"/>
</div>

<br/>

## About

I build backend systems the way they're meant to be built for production — not for a demo. My stack centers on **FastAPI**, **PostgreSQL**, and **SQLAlchemy 2.0**, structured through repository pattern, service-layer separation, and dependency injection, so the codebase stays testable as scope grows.

I think about the parts that don't show up in a tutorial: token rotation that survives concurrent sessions, RBAC that holds under real permission edge cases, and Docker images that behave identically in staging and production. I've also wired AI-driven features — resume parsing and scoring — into REST APIs, treated as just another service boundary to design around, not a special case.

**Architecture philosophy:**

| Principle | Practice |
|---|---|
| Separation of concerns | Repository Pattern · Service Layer |
| Testability | Dependency Injection |
| Security | JWT · RBAC · Scoped permissions |
| Reliability | Docker · Versioned migrations · Structured errors |
| Clarity | OpenAPI documentation on every service |

<br/>

## Tech Stack

<table>
<tr><td width="140"><b>Languages</b></td><td><img src="https://skillicons.dev/icons?i=python,ts,js" /></td></tr>
<tr><td><b>Backend</b></td><td><img src="https://skillicons.dev/icons?i=fastapi,nodejs" /></td></tr>
<tr><td><b>Database</b></td><td><img src="https://skillicons.dev/icons?i=postgres,sqlite" /></td></tr>
<tr><td><b>ORM & Migrations</b></td><td><img src="https://img.shields.io/badge/SQLAlchemy_2.0-0D1117?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Alembic-0D1117?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Pydantic-0D1117?style=flat-square&logo=pydantic&logoColor=white" /></td></tr>
<tr><td><b>Authentication</b></td><td><img src="https://img.shields.io/badge/JWT-0D1117?style=flat-square&logo=jsonwebtokens&logoColor=white" /> <img src="https://img.shields.io/badge/OAuth2-0D1117?style=flat-square&logo=auth0&logoColor=white" /> <img src="https://img.shields.io/badge/RBAC-0D1117?style=flat-square" /></td></tr>
<tr><td><b>Caching</b></td><td><img src="https://skillicons.dev/icons?i=redis" /></td></tr>
<tr><td><b>DevOps</b></td><td><img src="https://skillicons.dev/icons?i=docker,githubactions,git,github,linux" /></td></tr>
<tr><td><b>Cloud & Deploy</b></td><td><img src="https://skillicons.dev/icons?i=aws,vercel" /> <img src="https://img.shields.io/badge/Railway-0D1117?style=flat-square&logo=railway&logoColor=white" /> <img src="https://img.shields.io/badge/Neon-0D1117?style=flat-square&logo=postgresql&logoColor=white" /></td></tr>
<tr><td><b>Testing</b></td><td><img src="https://img.shields.io/badge/Pytest-0D1117?style=flat-square&logo=pytest&logoColor=white" /></td></tr>
<tr><td><b>Documentation</b></td><td><img src="https://img.shields.io/badge/OpenAPI-0D1117?style=flat-square&logo=swagger&logoColor=white" /></td></tr>
<tr><td><b>AI Integration</b></td><td><img src="https://img.shields.io/badge/LLM_APIs-0D1117?style=flat-square&logo=openai&logoColor=white" /></td></tr>
<tr><td><b>Tools</b></td><td><img src="https://skillicons.dev/icons?i=postman,vscode" /></td></tr>
</table>

<br/>

## Current Focus

`Production API Design` · `Backend Architecture` · `System Design` · `Redis Caching` · `CI/CD` · `Cloud Deployment`

<br/>

## Featured Work

<br/>

<table width="100%">
<tr><td>

### CampusOS ERP
<sub>Flagship Project</sub>

Production College ERP backend managing multi-role academic operations — students, faculty, and administration — behind a single, secured API surface.

**Architecture**
- Repository Pattern → Service Layer → API Layer, decoupled through Dependency Injection
- JWT authentication with RBAC scoped across student, faculty, and admin roles
- PostgreSQL on Neon, managed with SQLAlchemy 2.0 and Alembic migrations
- Redis caching on high-read endpoints
- Dockerized, deployed to production on Railway

**Production Highlights**
- Role-scoped dashboards and permission boundaries
- Secure session and refresh-token lifecycle
- Pydantic-validated request/response contracts
- Full interactive Swagger/OpenAPI documentation

**Stack**
<br/>
<img src="https://img.shields.io/badge/FastAPI-0D1117?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/SQLAlchemy_2.0-0D1117?style=flat-square" /> <img src="https://img.shields.io/badge/Redis-0D1117?style=flat-square&logo=redis&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-0D1117?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/JWT-0D1117?style=flat-square" /> <img src="https://img.shields.io/badge/RBAC-0D1117?style=flat-square" />

<br/><br/>

[![Live Demo](https://img.shields.io/badge/Live%20Demo-3FB950?style=for-the-badge&logo=vercel&logoColor=white)](https://campusos-lac.vercel.app/login)
[![API Docs](https://img.shields.io/badge/API%20Docs-6E40C9?style=for-the-badge&logo=swagger&logoColor=white)](https://campusos-production-26bf.up.railway.app/docs)
[![Repository](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yogesh-kumar-sharma/campusos)

</td></tr>
</table>

---

### Authentication API

Standalone, production-ready authentication service — the kind of system most products build on top of.

`JWT Access + Refresh Rotation` · `RBAC` · `Email Verification` · `Password Reset` · `Alembic Migrations` · `Docker`

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/yogesh-kumar-sharma/authentication-api-fastapi)

---

### AI Resume Analyzer

AI-powered backend that parses and scores resumes against ATS (Applicant Tracking System) criteria.

`PDF Parsing` · `ATS Scoring` · `AI Integration` · `FastAPI`

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/yogesh-kumar-sharma/AI_Resume_Analyzer)

---

### Portfolio Website

Personal developer portfolio presenting backend projects, live deployments, and production architecture.

`Next.js` · `TypeScript` · `Tailwind CSS` · `Framer Motion`

[![Live Demo](https://img.shields.io/badge/Live%20Demo-3FB950?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-zeta-six-vrbq18bmw9.vercel.app/)

---

### Blog Platform API
<sub>Coming Soon</sub>

Production-grade blogging backend, currently in development.

`JWT` · `Comments` · `Likes` · `Bookmarks` · `Tags` · `Search` · `Docker`

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

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,100:161B22&height=2&section=footer" width="100%"/>
</div>

<p align="center">
<a href="https://portfolio-zeta-six-vrbq18bmw9.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-6E40C9?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://github.com/yogesh-kumar-sharma"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/yogesh-kumar0"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:yogesh.kumar.sharma.dev@gmail.com"><img src="https://img.shields.io/badge/Email-D93025?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p align="center"><sub>Designed for production. Built with precision.</sub></p>
