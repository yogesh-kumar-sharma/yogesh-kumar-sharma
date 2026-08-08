<div align="center">
<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0D1117,100:0D1117&height=90&section=top"/>
</div>

<div align="center">

# Yogesh Kumar Sharma

<sub>PYTHON BACKEND ENGINEER</sub>

<img src="https://img.shields.io/badge/-Available%20for%20Opportunities-1A1F26?style=flat-square&labelColor=1A1F26&color=1A1F26"/>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=14&duration=3600&pause=1200&color=A8B3BF&center=true&vCenter=true&width=620&lines=Designing+backend+systems%2C+not+just+endpoints;Repository+Pattern+%C2%B7+Service+Layer+%C2%B7+Dependency+Injection;JWT+%C2%B7+RBAC+%C2%B7+Redis+%C2%B7+Docker+%C2%B7+PostgreSQL" alt="typing"/>

<br/>

<a href="https://github.com/yogesh-kumar-sharma">GitHub</a> ·
<a href="https://linkedin.com/in/yogesh-kumar0">LinkedIn</a> ·
<a href="https://portfolio-zeta-six-vrbq18bmw9.vercel.app/">Portfolio</a> ·
<a href="mailto:yogesh.kumar.sharma.dev@gmail.com">Email</a>

</div>

<br/>

> Backend engineering that holds up outside the tutorial: token rotation that survives concurrent sessions, RBAC that doesn't break on the edge case, Docker images that behave the same in staging and production. Repository pattern and a service layer aren't ceremony — they're what keeps a system changeable a year in.

<br/>

<div align="center">

`Production APIs` `Backend Architecture` `Authentication & RBAC` `Repository Pattern` `Dependency Injection` `API Design` `AI Integration`

</div>

<br/>

<table width="100%">
<tr>
<td width="20%"><sub>PRINCIPLE</sub></td>
<td><sub>HOW IT SHOWS UP</sub></td>
</tr>
<tr><td>Security first</td><td>JWT access + refresh rotation, RBAC scoped per role, no secrets in source</td></tr>
<tr><td>Layered by design</td><td>Route → Service → Repository, wired through dependency injection</td></tr>
<tr><td>Typed contracts</td><td>Pydantic on every request and response boundary</td></tr>
<tr><td>Built to ship</td><td>Dockerized, migration-versioned, documented via OpenAPI on every route</td></tr>
</table>

<br/>

<div align="center"><sub>· · ·</sub></div>

<br/>

## Featured System

<table width="100%">
<tr>
<td>

### CampusOS ERP
<sub>Flagship — production college ERP behind a single secured API surface</sub>

A multi-tenant academic backend serving three roles — student, faculty, admin — each with its own permission boundary, dashboard scope, and session lifecycle, all behind one FastAPI service.

<table width="100%">
<tr>
<td width="50%" valign="top">

**Architecture**
```
Client
  → FastAPI (routes + middleware)
    → Auth layer (JWT validation, RBAC)
      → Service layer (business logic)
        → Repository (SQLAlchemy 2.0)
          → PostgreSQL (Neon)
```
Redis sits in front of high-read endpoints. Alembic owns every schema change.

</td>
<td width="50%" valign="top">

**Shipped**
- Role-scoped dashboards, three permission tiers
- Refresh-token session lifecycle
- Pydantic-validated contracts on every route
- Full Swagger / OpenAPI documentation
- Dockerized, deployed on Railway

</td>
</tr>
</table>

<img src="https://img.shields.io/badge/FastAPI-1A1F26?style=flat-square"/> <img src="https://img.shields.io/badge/PostgreSQL-1A1F26?style=flat-square"/> <img src="https://img.shields.io/badge/SQLAlchemy_2.0-1A1F26?style=flat-square"/> <img src="https://img.shields.io/badge/Redis-1A1F26?style=flat-square"/> <img src="https://img.shields.io/badge/Docker-1A1F26?style=flat-square"/> <img src="https://img.shields.io/badge/JWT-1A1F26?style=flat-square"/> <img src="https://img.shields.io/badge/RBAC-1A1F26?style=flat-square"/>

<br/><br/>

[**Live**](https://campusos-lac.vercel.app/login) &nbsp;·&nbsp; [**API Docs**](https://campusos-production-26bf.up.railway.app/docs) &nbsp;·&nbsp; [**Repository**](https://github.com/yogesh-kumar-sharma/campusos)

</td>
</tr>
</table>

<br/>

## Also Shipped

<table width="100%">
<tr>
<td width="50%" valign="top">

**Authentication API**
<sub>Standalone service</sub>

The system most products end up building on top of, pulled out on its own — access + refresh rotation, RBAC, email verification, password reset.

[Repository →](https://github.com/yogesh-kumar-sharma/authentication-api-fastapi)

</td>
<td width="50%" valign="top">

**AI Resume Analyzer**
<sub>AI-integrated service</sub>

Parses and scores resumes against ATS criteria. The model sits behind the same API contract as everything else — one more service boundary, not a special case.

[Repository →](https://github.com/yogesh-kumar-sharma/AI_Resume_Analyzer)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Portfolio**
<sub>Product site</sub>

Next.js front for the work above — live deployments, architecture notes.

[Live site →](https://portfolio-zeta-six-vrbq18bmw9.vercel.app/)

</td>
<td width="50%" valign="top">

**Blog Platform API**
<sub>Currently building</sub>

`JWT` `Comments` `Likes` `Bookmarks` `Tags` `Search` `Docker`

</td>
</tr>
</table>

<br/>

<div align="center"><sub>· · ·</sub></div>

<br/>

## Toolchain

<table width="100%">
<tr><td width="150"><sub>LANGUAGES</sub></td><td><img src="https://skillicons.dev/icons?i=python,ts,js" theme="dark"/></td></tr>
<tr><td><sub>BACKEND</sub></td><td><img src="https://skillicons.dev/icons?i=fastapi,nodejs" theme="dark"/></td></tr>
<tr><td><sub>DATA</sub></td><td><img src="https://skillicons.dev/icons?i=postgres,sqlite,redis" theme="dark"/> <img src="https://img.shields.io/badge/SQLAlchemy_2.0-1A1F26?style=flat-square"/> <img src="https://img.shields.io/badge/Alembic-1A1F26?style=flat-square"/></td></tr>
<tr><td><sub>INFRASTRUCTURE</sub></td><td><img src="https://skillicons.dev/icons?i=docker,githubactions,git,linux" theme="dark"/></td></tr>
<tr><td><sub>DEPLOYMENT</sub></td><td><img src="https://img.shields.io/badge/Railway-1A1F26?style=flat-square"/> <img src="https://img.shields.io/badge/Vercel-1A1F26?style=flat-square"/> <img src="https://img.shields.io/badge/Neon-1A1F26?style=flat-square"/></td></tr>
<tr><td><sub>CLOUD</sub></td><td><img src="https://skillicons.dev/icons?i=aws" theme="dark"/></td></tr>
<tr><td><sub>TESTING</sub></td><td><img src="https://img.shields.io/badge/Pytest-1A1F26?style=flat-square"/></td></tr>
<tr><td><sub>DOCUMENTATION</sub></td><td><img src="https://img.shields.io/badge/OpenAPI%20%2F%20Swagger-1A1F26?style=flat-square"/></td></tr>
<tr><td><sub>AI APIS</sub></td><td><img src="https://img.shields.io/badge/LLM%20APIs-1A1F26?style=flat-square"/></td></tr>
<tr><td><sub>DEV TOOLS</sub></td><td><img src="https://skillicons.dev/icons?i=postman,vscode" theme="dark"/></td></tr>
</table>

<sub>Currently learning — Celery · Nginx · CI/CD · WebSockets · Microservices</sub>

<br/>

<div align="center"><sub>· · ·</sub></div>

<br/>

## Engineering Metrics

<table align="center"><tr>
<td><img src="https://github-readme-stats.vercel.app/api?username=yogesh-kumar-sharma&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=A8B3BF&icon_color=A8B3BF&text_color=8B949E"/></td>
<td><img src="https://streak-stats.demolab.com?user=yogesh-kumar-sharma&theme=dark&hide_border=true&background=0D1117&ring=A8B3BF&fire=A8B3BF&currStreakLabel=A8B3BF"/></td>
</tr></table>

<div align="center">
<img src="https://raw.githubusercontent.com/yogesh-kumar-sharma/yogesh-kumar-sharma/output/github-contribution-grid-snake-dark.svg"/>
</div>

<br/>

<div align="center">

**yogesh.kumar.sharma.dev@gmail.com**

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0D1117,100:0D1117&height=70&section=bottom"/>

</div>
