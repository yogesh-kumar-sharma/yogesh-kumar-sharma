<div align="center">

```
$ whoami
```

<h1>Yogesh Kumar Sharma</h1>

<sub>PYTHON BACKEND ENGINEER — FASTAPI / POSTGRESQL / SYSTEM DESIGN</sub>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=15&duration=2800&pause=1000&color=2DD4BF&center=true&vCenter=true&width=560&lines=repository+pattern+%E2%80%94+service+layer+%E2%80%94+dependency+injection;jwt+auth+%E2%80%A2+rbac+%E2%80%A2+redis+%E2%80%A2+docker;built+for+production%2C+not+for+demos" alt="typing" />

</div>

<br/>

<table width="100%">
<tr>
<td width="50%" valign="top">

**Based in** Greater Noida, India
**Studying** MCA — AI & ML, Galgotias University
**Status** `open_to_work: true`
**Building toward** Backend Developer roles shipping real production APIs

</td>
<td width="50%" valign="top">

```yaml
stack:
  language:  python
  framework: fastapi
  database:  postgresql (neon)
  orm:       sqlalchemy 2.0 + alembic
  cache:     redis
  auth:      jwt · oauth2 · rbac
  ship_via:  docker → railway
```

</td>
</tr>
</table>

<p>
<a href="https://portfolio-zeta-six-vrbq18bmw9.vercel.app/"><img src="https://img.shields.io/badge/portfolio-6E40C9?style=flat-square&logo=vercel&logoColor=white&labelColor=0D1117"/></a>
<a href="https://www.linkedin.com/in/yogesh-kumar0"><img src="https://img.shields.io/badge/linkedin-0969DA?style=flat-square&logo=linkedin&logoColor=white&labelColor=0D1117"/></a>
<a href="https://github.com/yogesh-kumar-sharma"><img src="https://img.shields.io/badge/github-000000?style=flat-square&logo=github&logoColor=white&labelColor=0D1117"/></a>
<a href="mailto:yogesh.kumar.sharma.dev@gmail.com"><img src="https://img.shields.io/badge/email-DA3633?style=flat-square&logo=gmail&logoColor=white&labelColor=0D1117"/></a>
</p>

&nbsp;

## Why I build the way I do

Most backend tutorials stop at "it works." I care about what happens after — token rotation that survives concurrent sessions, RBAC that holds under real permission edge cases, and a Docker image that behaves the same in staging as it does in production. Repository pattern and a service layer aren't ceremony to me; they're what keeps a codebase changeable six months in. I've also treated AI features — resume parsing, scoring — as just another service boundary to design around, not a special case that gets to skip the rules.

&nbsp;

## Systems

Four things I've shipped, each documented at the level it deserves.

<br/>

**`01`  CampusOS ERP** · *flagship*
College ERP backend serving three distinct roles — student, faculty, admin — behind one secured API surface.

```
layers     Repository → Service → API, wired through Dependency Injection
auth       JWT + refresh rotation, RBAC scoped per role
data       PostgreSQL (Neon) via SQLAlchemy 2.0, versioned with Alembic
perf       Redis caching on high-read endpoints
ship       Dockerized → Railway, Swagger/OpenAPI on every route
```

[`→ live`](https://campusos-lac.vercel.app/login) · [`→ api docs`](https://campusos-production-26bf.up.railway.app/docs) · [`→ source`](https://github.com/yogesh-kumar-sharma/campusos)

<br/>

**`02`  Authentication API** · *standalone service*
The system most products end up building on top of — pulled out on its own.
`access+refresh rotation` `rbac` `email verification` `password reset` `alembic` `docker`

[`→ source`](https://github.com/yogesh-kumar-sharma/authentication-api-fastapi)

<br/>

**`03`  AI Resume Analyzer** · *AI-integrated service*
Parses resumes and scores them against ATS criteria — the AI model sits behind the same API contract as everything else.
`pdf parsing` `ats scoring` `llm integration` `fastapi`

[`→ source`](https://github.com/yogesh-kumar-sharma/AI_Resume_Analyzer)

<br/>

**`04`  Portfolio** · *product site*
Next.js + TypeScript front for the work above — live deployments, architecture notes, the lot.
`next.js` `typescript` `tailwind` `framer motion`

[`→ live`](https://portfolio-zeta-six-vrbq18bmw9.vercel.app/)

<br/>

**`05`  Blog Platform API** · *in progress*
`jwt` `comments` `likes` `bookmarks` `tags` `search` `docker`

&nbsp;

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
&nbsp;

## Metrics

<table align="center"><tr>
<td><img src="https://github-readme-stats.vercel.app/api?username=yogesh-kumar-sharma&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=2DD4BF&icon_color=2DD4BF&text_color=C9D1D9"/></td>
<td><img src="https://streak-stats.demolab.com?user=yogesh-kumar-sharma&theme=dark&hide_border=true&background=0D1117&ring=2DD4BF&fire=2DD4BF&currStreakLabel=2DD4BF"/></td>
</tr></table>

<div align="center">
<img src="https://raw.githubusercontent.com/yogesh-kumar-sharma/yogesh-kumar-sharma/output/github-contribution-grid-snake-dark.svg"/>
</div>

&nbsp;

<div align="center">

**Open to Python Backend Developer / FastAPI roles.**

<a href="https://portfolio-zeta-six-vrbq18bmw9.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-6E40C9?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/yogesh-kumar0"><img src="https://img.shields.io/badge/LinkedIn-0969DA?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/yogesh-kumar-sharma"><img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="mailto:yogesh.kumar.sharma.dev@gmail.com"><img src="https://img.shields.io/badge/Email-DA3633?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<sub>Built for production. Documented like it matters.</sub>

</div>
